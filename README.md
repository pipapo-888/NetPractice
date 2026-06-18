_This project has been created as part of the 42 curriculum by knomura._

## Description

NetPractice is a 42 school project focused on understanding **TCP/IP networking** and **subnetting** through practical exercises.

The goal is to configure small-scale networks by solving 10 levels of network diagrams. Each level presents a broken or misconfigured network, and the task is to assign correct IP addresses, subnet masks, and routing table entries so that all hosts can communicate.

### How it works

Each level is presented as a visual network diagram in a browser-based interface. You fill in missing or incorrect values (IP addresses, masks, routes) and submit. When all devices can communicate, the level is complete. Completing all 10 levels constitutes passing the project.

## Instructions

### Installation

1. Log in to the [42 Intranet](https://intra.42.fr)
2. Navigate to the NetPractice project page
3. Download the project archive and extract it

### Execution

```zsh
./run.sh
```

This opens the NetPractice interface in your browser. Select a level from the dropdown menu and configure the network diagram until all devices can communicate.


## Resources

### Networking Concepts Studied

- **TCP/IP addressing** — IPv4 address structure, network vs. host portions, and how devices are identified on a network
- **Subnet masks** — CIDR notation (`/24`, `/28`, etc.), calculating network addresses, broadcast addresses, and valid host ranges
- **Default gateways** — how a host forwards packets destined outside its local subnet to a router
- **Routers** — layer 3 devices that forward packets between different networks using routing tables
- **Switches** — layer 2 devices that connect devices within the same network segment
- **Routing tables** — destination/next-hop entries that determine the path packets take through a network
- **OSI model layers** — particularly Layer 2 (Data Link) and Layer 3 (Network) as they relate to switching and routing

### References

- [TCP/IPプロトコルとは｜ITマネジメント](https://www.itmanage.co.jp/column/tcp-ip-protocol/)
- [ネットワーク入門：IPアドレスとサブネットマスク - Qiita](https://qiita.com/cafedrip/items/8f0cc9544910cba23be8)
- [ルーティングテーブルの見方 - Qiita](https://qiita.com/hirakei1203/items/29e0da8edaea0a81895d)
- [デフォルトゲートウェイとは｜わわわIT用語辞典](https://wa3.i-3-i.info/word1101.html)
- [サブネットマスクとは｜わわわIT用語辞典](https://wa3.i-3-i.info/word11990.html)

### AI Usage

AI tools (ChatGPT, Claude Code) were used to:

- understand TCP/IP addressing and how network/host portions are determined by subnet masks
- understand how routing tables work and how to configure correct destination/next-hop entries

All final answers and configurations were determined and validated by the author.
