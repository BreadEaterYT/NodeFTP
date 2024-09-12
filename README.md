# NodeFTP

**NodeFTP** is a customizable alternative to FileZilla and FileZilla Server, built using Node.js. It offers private-use FTP server and client capabilities, allowing for extensive customization.

For contributing, you can fork the project and free to modify it, if you want it to be published as a official release, you can contact me at contact@breadeater.fr

## Features / Objectives

- SSL/TLS self-signed certificate generation at each start of the server.
- Fully customizable FTP server via modifying the code.
- Developed using Node.js for maximum flexibility.
- Compatible on Windows, Linux and Android.
- Remote administration with WebSocket.
- User friendly interface for client.

More to come in future updates.

## Modules Used

- **Bcrypt**: For user password hashing.
- **Child_Process**: For SSL/TLS self-signed certificate generation.
- **FTPD**: For the FTP server.
- **HTTPS**: For securing the WebSocket server.
- **Path / Fs**: For interactions with the file system.
- **ws**: For the WebSocket server

## Installation

1. Download the source code.
2. Open a terminal and navigate to the project directory.
3. Run the following command to install dependencies:

```bash
npm install
```

4. Run the server using:

```bash
npm run start
```
OR
```bash
node .
```

5. Done!

## Config

- To config without accessing via the NodeFTP Client, modify the config.json file located at config/config.json in the project directory
- To add / remove users, modify the users.json file located at config/users.json in the project directory

## Contributors

No contributors for now, i’m the sole developer of NodeFTP.