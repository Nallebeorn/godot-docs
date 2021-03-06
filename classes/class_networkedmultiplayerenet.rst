.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the NetworkedMultiplayerENet.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_NetworkedMultiplayerENet:

NetworkedMultiplayerENet
========================

**Inherits:** :ref:`NetworkedMultiplayerPeer<class_networkedmultiplayerpeer>` **<** :ref:`PacketPeer<class_packetpeer>` **<** :ref:`Reference<class_reference>` **<** :ref:`Object<class_object>`

**Category:** Core

Brief Description
-----------------

PacketPeer implementation using the ENet library.

Member Functions
----------------

+------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                   | :ref:`close_connection<class_NetworkedMultiplayerENet_close_connection>`  **(** **)**                                                                                                                                          |
+------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`  | :ref:`create_client<class_NetworkedMultiplayerENet_create_client>`  **(** :ref:`String<class_string>` ip, :ref:`int<class_int>` port, :ref:`int<class_int>` in_bandwidth=0, :ref:`int<class_int>` out_bandwidth=0  **)**       |
+------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`  | :ref:`create_server<class_NetworkedMultiplayerENet_create_server>`  **(** :ref:`int<class_int>` port, :ref:`int<class_int>` max_clients=32, :ref:`int<class_int>` in_bandwidth=0, :ref:`int<class_int>` out_bandwidth=0  **)** |
+------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`  | :ref:`get_compression_mode<class_NetworkedMultiplayerENet_get_compression_mode>`  **(** **)** const                                                                                                                            |
+------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                   | :ref:`set_bind_ip<class_NetworkedMultiplayerENet_set_bind_ip>`  **(** :ref:`String<class_string>` ip  **)**                                                                                                                    |
+------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                   | :ref:`set_compression_mode<class_NetworkedMultiplayerENet_set_compression_mode>`  **(** :ref:`int<class_int>` mode  **)**                                                                                                      |
+------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

Numeric Constants
-----------------

- **COMPRESS_NONE** = **0**
- **COMPRESS_RANGE_CODER** = **1**
- **COMPRESS_FASTLZ** = **2**
- **COMPRESS_ZLIB** = **3**
- **COMPRESS_ZSTD** = **4**

Description
-----------

A connection (or a listening server) that should be passed to :ref:`SceneTree.set_network_peer<class_SceneTree_set_network_peer>`. Socket events can be handled by connecting to :ref:`SceneTree<class_scenetree>` signals.

Member Function Description
---------------------------

.. _class_NetworkedMultiplayerENet_close_connection:

- void  **close_connection**  **(** **)**

.. _class_NetworkedMultiplayerENet_create_client:

- :ref:`int<class_int>`  **create_client**  **(** :ref:`String<class_string>` ip, :ref:`int<class_int>` port, :ref:`int<class_int>` in_bandwidth=0, :ref:`int<class_int>` out_bandwidth=0  **)**

Create client that connects to a server at address ``ip`` using specified ``port``.

.. _class_NetworkedMultiplayerENet_create_server:

- :ref:`int<class_int>`  **create_server**  **(** :ref:`int<class_int>` port, :ref:`int<class_int>` max_clients=32, :ref:`int<class_int>` in_bandwidth=0, :ref:`int<class_int>` out_bandwidth=0  **)**

Create server that listens to connections via ``port``.

.. _class_NetworkedMultiplayerENet_get_compression_mode:

- :ref:`int<class_int>`  **get_compression_mode**  **(** **)** const

.. _class_NetworkedMultiplayerENet_set_bind_ip:

- void  **set_bind_ip**  **(** :ref:`String<class_string>` ip  **)**

.. _class_NetworkedMultiplayerENet_set_compression_mode:

- void  **set_compression_mode**  **(** :ref:`int<class_int>` mode  **)**


