# Mattel Hot Wheels Stock Monitor — Web Bot Auth identity

This public repository hosts only the monitor's public Ed25519 JWKS and a
short description of its purpose. The private signing key, Telegram
credentials, product state, and monitoring code are not stored here.

The bot checks the public Mattel Creations Hot Wheels Collectors catalog for
vehicle availability changes and sends personal Telegram notifications. It
does not log in, reserve items, add items to a cart, or buy products. It uses
scheduled low-frequency requests and honors retry instructions from the site.

The operator is the GitHub account [ChiarelloB](https://github.com/ChiarelloB).
