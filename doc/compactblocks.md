BUIP051 (CompactBlocks support for BU) Development Notes
========================================================
(work in progress)

Specification
-------------

There is no up to date specification yet for Compact Blocks (CB) as
implemented by clients the Bitcoin Cash network.
The existing implementations (ABC, XT) derive from BIP152, but drop the
support of protocol version 2 (the separate version for Segwit).

There may also be a difference in the protocol where Bitcoin Cash clients
added support for more than 2^16 transactions.

Until the BIP152 protocol spec can be reduced to provide an accurate
version for the Bitcoin Cash implementation, readers should refer to
the original BIP at

https://github.com/bitcoin/bips/blob/master/bip-0152.mediawiki

It is intended that a revised version matching the common implementation
of CB across the Bitcoin Cash clients (BU, XT, ABC) will be compiled as
part of the implementation of BUIP051.
This should serve as a reference going forward.


Implementation References
-------------------------

The XT and ABC clients have working implementations of CB and will be
used as reference implementations.


END
