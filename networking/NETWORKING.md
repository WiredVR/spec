# Networking

The networking model for The Wired aims for decentralization and security.

## 1. World and Avatar Loading

Worlds and avatars are addressed with URLs. In order to ensure a smooth and seamless experience for players, Wired recommends that all content is addressed through IPFS. This is to ensure that users will receive CDN-like levels of performance, while also reducing the reliance on centralized hosting providers.

## 2. Dedicated Server Hosting

World instances live on dedicated servers, which are purely used to act as relays to allow users to send information between each other. (TODO: add more details)

## Networking Protocols

The Wired uses UDP to facilitate communication between players and servers. This is suitable for realtime applications and ensures minimal latency when in-game.

## Security Measures

To ensure the security of the game and its players, all communication between players and servers **MUST** be encrypted using industry standard encryption methods such as TLS.

## Additional Networking Information

- [Search And Discovery (Search Engines)](./SEARCH_AND_DISCOVERY.md)
- [Content Loading](./CONTENT_LOADING.md)
