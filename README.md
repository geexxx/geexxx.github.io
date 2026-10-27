# Tesla Fleet public key hosting

This repository is reserved for Home Assistant's Tesla Fleet public key at `/.well-known/appspecific/com.tesla.3p.public-key.pem`.

Only the public key belongs here. Never commit the private key, Tesla Client Secret, access tokens, vehicle identifiers, or account information.

The key file will be published only after Home Assistant generates it during the Tesla Fleet integration flow.
