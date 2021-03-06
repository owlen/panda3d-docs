.. _distributed-networking:

Distributed Networking
======================

Distributed Networking is Panda3D's high-level network API. When a distributed
object is created all interested clients will automatically create a copy of
that object. Updates to the object will automatically propagate to the copies.

The distributed network is composed of several layers: the dc file which
defines the communication, ServerRepositories which handle communication
between clients, ClientRepositories which interact and manage the distributed
objects, and the distributed objects themselves.

Several abbreviations will be used in the following pages and my come accross
you when using the system. To not repeat them every time or for you to look up
whenever you stumble upon one, we'll list them here.

| DO = Distributed Object
| doId = Distributed Object Identifier
| AI = Artificial Intelligence
| UD = Uber Dog
| OV = Owner View
| DC = Distributed Class
| SR = Server Repository
| CR = Client Repository

.. note::
   The following parts which are rarely used are not documented yet.

   * Uber Dog servers and objects
   * Owner View objects

.. toctree::
   :maxdepth: 2

   servers
   server-repositories
   ai-repositories
   clients
   client-repositories
   dc-definition-files
   client-created-objects
   ai-created-objects
   time-manager
   distributed-object
   distributed-node
   distributed-smooth-node
