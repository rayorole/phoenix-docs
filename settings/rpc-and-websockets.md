---
description: This enables Phoenix to communicate with the Solana blockchain
icon: brackets-curly
---

# RPC & Websockets

### What is an RPC? <a href="#what-is-an-rpc" id="what-is-an-rpc"></a>

The Remote Procedure Call (RPC) protocol allows DogWifTools to interact directly with the Solana blockchain. It acts as a bridge, enabling the software to send requests and receive responses from the blockchain network.

### What is a WebSocket? <a href="#what-is-a-websocket" id="what-is-a-websocket"></a>

WebSockets provide a real-time communication channel between your application and the Solana blockchain. Unlike RPC, which is request-response based, WebSockets allow for continuous, two-way interaction.

### Obtaining RPC & Websockets

To obtain RPC URLs and WebSocket endpoints for the Solana blockchain, you'll typically need to set up an account with a Solana infrastructure provider, such as Project Serum, Alchemy, or QuickNode. These providers will offer the necessary connection details, which can then be configured in your software settings for interaction with Solana.

### Configuring RPC and WebSocket Connections <a href="#configuring-rpc-websocket" id="configuring-rpc-websocket"></a>

Once you have obtained the necessary RPC URLs and WebSocket endpoints, you'll need to configure your Phoenix to establish these connections. This can be easily done in the [RPC settings page](https://dashboard.phoenixtools.app/settings/rpc). If you require any more assistance, reach us out in our Discord!
