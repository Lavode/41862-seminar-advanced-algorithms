# B-Trees (2021-12-07)

- Tree depth log(n), where n number of keys
- Balanced-ness: Common bound of children per nodes

## Performance vs binary search tree

Slower in main memory as B-Tree has more than 2 children per node, so we must
read (at worst) every child in every level. Compare BST: Only read node values,
then immediately go left or right.

But in secondary storage: B-tree benefits from spatial locality. Related keys
(i.e. those we want to search next) will always be in proximity to each other,
so benefit from bulk load of secondary storage.

*Much* faster on HDD than BSTs.


## Insert, update, delete

- Always ensure that no node will becoem too small / too large. If needed, will
  rebalance.
