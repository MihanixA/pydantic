 - added `KafkaDsn` to the `pydantic/networks.py`
 - added `get_default_parts` and `apply_default_parts` methods to `AnyUrl`
 - `HttpUrl` now inherits `AnyHttpUrl` instead of `AnyUrl`
 - `HttpUrl` now has default port 80 for http and 443 for https
 - added `hidden_parts` field to hide parts from url representation
