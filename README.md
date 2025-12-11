# Chatted
Chatted — application for creating chats within local networks.

### How to create local network?
To create a local network, you can use free applications like Radmin VPN, ZeroTier, and similar tools.

**Example using Radmin VPN:**
1. Install [Radmin VPN](https://www.radmin-vpn.com/en/).
2. Create a network (Network → Create Network).
3. Share the connection details for your network.
4. Provide your Radmin VPN IP address to those who need to connect.
5. Start chatting!

### What is ChattedTerminalServer?
This is the terminal/command-line version for creating chat servers.

**Usage:**
To start the server, simply move the folder to any location and run `start.bat`. A window will open showing possible launch arguments for the file.

**Example of creating a server:**
```batch
@echo off
java -jar ChattedServer.jar --server 8888
pause
```
* `--server` indicates launching a server.
* `8888` is the port for your server; you should change this value.
