# FTPL - My FTP Like Protocol

> My implementation of FTP both Client and Server in Python3.

## Table of Contents

- [My FTP Like Custom Protocol](#ftpl---my-ftp-like-protocol)
  - [Table of Contents](#table-of-contents)
  - [General Info](#general-info)
  - [Features](#features)
  - [Usage](#usage)

## General Info

The File Transfer Protocol is a standard communication protocol used for transferring files between a server and clients on a computer network. FTP is built on a client–server model architecture using separate control and data connections between the client and the server. This implementation of FTP doesn't fully follow [RFC 959](https://datatracker.ietf.org/doc/html/rfc959) but it implements most of it.

## Features

- Multi-Threaded Server
- Colorful TUI :)
- Readable and clean code
- No external dependencies

## Usage

Put your files inside `server/files` so clients would be able to download it.
Server by default listens on port 2121.

```bash
$ python server/main.py
$ python client/main.py
```
