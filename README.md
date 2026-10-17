# VIDAA client certificates (backup copy)

A backup of the client certificates that Hisense VIDAA TVs ask remote apps for on port 36669 (MQTT over TLS).
They are already public in other repositories; [TV Remote](https://github.com/HoangTran0410/tv-remote) downloads them
from there first and falls back to this copy. They belong to Hisense and are not part of TV Remote.

| File | Certificate | SHA-256 of the certificate (DER) | Copied from |
|---|---|---|---|
| `vidaa_client.pem` / `.key` | CN=VidaaAppAndroidV01 (VIDAA app, until 2034) | `31f914630f8636d6c4313e02e9eb3724b4706c6b5049c838b04213ab56905aa3` | adamazad/vidaa-remote, tombabolewski/vidaa-control |
| `remoteclientmobile.pem` / `.key` | CN=remoteclientmobile (RemoteNOW app, until 2043) | `857e4d1ad94f892404371ff1cb282c1b890f73ced3fd47051e6e20d590557c59` | Alexa-RR/ha-vidaa, amirburbea/neeo |
