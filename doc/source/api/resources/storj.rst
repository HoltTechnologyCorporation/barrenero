..
    Barrenero, a set of services and tools for effective mining cryptocurrencies.
    Copyright (C) 2017  José Antonio Perdiguero López

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>.

Storj Miner Status
==================

Retrieve Storj nodes status.

Request
-------

URL
^^^

`/api/v1/storj/`

Headers
^^^^^^^

Authorization
    Token <auth_token>

Response
--------

.. code:: javascript

    [
      {
        "id": string,
        "status": string,
        "config_path": string,
        "uptime": string,
        "restarts": int,
        "peers": int,
        "offers": int,
        "data_received": int,
        "delta": int,
        "port": int,
        "shared": string,
        "shared_percent": int,
        "response_time": float,
        "reputation": int,
        "version": string
      }
    ]
