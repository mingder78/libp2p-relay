# libp2p-relay

## run

```
ming-ders-MacBook.local💩➜  libp2p-relay git:(main)
bun dev
$ node index.js
PeerID:  12D3KooWMpTVZuVQKuqzrMX8DsCX41XG1LV89jwSZZRcRWyuHJYc
Multiaddrs:  [
  Multiaddr(/ip4/127.0.0.1/tcp/9001/ws/p2p/12D3KooWMpTVZuVQKuqzrMX8DsCX41XG1LV89jwSZZRcRWyuHJYc),
  Multiaddr(/ip4/192.168.1.113/tcp/9001/ws/p2p/12D3KooWMpTVZuVQKuqzrMX8DsCX41XG1LV89jwSZZRcRWyuHJYc),
  Multiaddr(/ip4/10.147.20.194/tcp/9001/ws/p2p/12D3KooWMpTVZuVQKuqzrMX8DsCX41XG1LV89jwSZZRcRWyuHJYc),
  Multiaddr(/ip4/127.0.0.1/tcp/9002/p2p/12D3KooWMpTVZuVQKuqzrMX8DsCX41XG1LV89jwSZZRcRWyuHJYc),
  Multiaddr(/ip4/192.168.1.113/tcp/9002/p2p/12D3KooWMpTVZuVQKuqzrMX8DsCX41XG1LV89jwSZZRcRWyuHJYc),
  Multiaddr(/ip4/10.147.20.194/tcp/9002/p2p/12D3KooWMpTVZuVQKuqzrMX8DsCX41XG1LV89jwSZZRcRWyuHJYc)
]

```


## build

To install dependencies:

```bash
bun install
```

To run:

```bash
bun run index.ts
```

This project was created using `bun init` in bun v1.1.20. [Bun](https://bun.sh) is a fast all-in-one JavaScript runtime.
