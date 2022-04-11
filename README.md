# B_Plus_Trees

• Values in the nodes are arranged in the ascending order from left to right.

• There are no duplicates to handle.

• When a data node splits, it creates two data nodes: left node and right node. The left node will have d records. The right node will have d+1 records. Separator sent to the parent node will be the smallest record stored in the right node.

• When an index node splits, it creates two index nodes: left node and right node. The left node will have t keys. The right node will have t+1 keys and one key is sent to the parent node.
