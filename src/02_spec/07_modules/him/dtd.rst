Debug Transport Datagram (DTD)
------------------------------

The Host Interface Module transfers data between the host and the device as Debug Transport Datagrams (DTD).
Every DTD encapsulates one Debug Packet by prefixing it with the the number of words the packet consists of (the size).

.. flat-table:: Debug Transport Datagram (DTD) Structure
  :widths: 2 10
  :header-rows: 1

  * - word index
    - data

  * - 0
    - size *n* of the Debug Packet in 16 bit words

  * - 1
    - word 0 of the Debug Packet

  * - 2
    - word 1 of the Debug Packet

  * - ...
    - ...

  * - *n* + 1
    - word *n* of the Debug Packet
