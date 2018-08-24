# [https://totp.info](https://totp.info)

Simple self-contained, single-file, 100% in-browser [Time-based One-time Password (TOTP)](https://en.wikipedia.org/wiki/Time-based_One-time_Password_algorithm) client that even works offline.

I made this because I needed a better way for a support vendor to be able to verify my users than CallerID or nothing.

The vendor couldn't provide each of their support staff with an actual TOTP client, so having them save a [totp.info](https://totp.info) URL in their password manager for us was a sufficient improvement.

Other solutions like [https://totp.io](https://totp.io) either sent the secret to the server, couldn't be conveyed in a simple URL, or weren't a single self-contained file that could be downloaded and work offline.

Alternate implementations:
  - [https://totp.io](https://totp.io)
  - [https://gauth.apps.gbraad.nl/](https://gauth.apps.gbraad.nl/)

