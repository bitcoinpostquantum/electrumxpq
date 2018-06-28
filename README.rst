=================================================
ElectrumxPQ - Reimplementation of electrum-server
=================================================

For a future network with bigger blocks.

  :Licence: MIT
  :Language: Python (>= 3.6)
  :Author: Neil Booth

Documentation
=============

See `readthedocs <https://electrumx.readthedocs.io/>`_.


Using with BPQ
==============

example of environment variables::

    COIN=BPQ
    NET=testnet
    DAEMON_URL=http://<username>:<password>@<bpqd_rpc_host>:<port>/
    DB_DIRECTORY=<path/to/electrumxpq/database>
    DB_ENGINE=leveldb
    HOST=0.0.0.0
    TCP_PORT=51011

