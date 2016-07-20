# Nodes, Clusters & Federations

A **BigchainDB node** is a server or set of closely-linked servers running RethinkDB Server, BigchainDB Server, and other BigchainDB-related software. Each node is controlled by one person or organization.

A set of BigchainDB nodes can connect to each other to form a **cluster**. Each node in the cluster runs the same software. A cluster contains one logical RethinkDB datastore. A cluster may have additional servers to do things such as cluster monitoring.

The people and organizations that run the nodes in a cluster belong to a **federation** (i.e. another organization). A federation must have some sort of governance structure to make decisions. If a cluster is run by a single company, then the federation is just that company.

**What's the Difference Between a Cluster and a Federation?**

A cluster is just a bunch of connected nodes (computers). A cluster might be operated by just one person. A federation is an organization which has a cluster, and where each node in the cluster has a different operator.

Confusingly, we sometimes call a federation's cluster its "federation." You can probably tell what we mean from context.