# NYCU Network Programming

###### *`Course`: 112 Spring 網路程式設計 Network Programming*
###### *`Instructor`: 吳毅成*

## Project1

> Score: 100

Design a **shell** named **npshell**. The **npshell** can support the following features:

1. Execution of commands
2. Ordinary Pipe
3. Numbered Pipe
4. File Redirection

## Project2

> Score: 97

Design 3 kinds of servers:
1. Design a **Concurrent connection-oriented** server. This server allows one client connect to it.
2. Design a server of the chat-like systems, called remote working systems (rwg). In this system, users can communicate with other users. Use the **single-process concurrent** paradigm to design this server.
3. Design the rwg server using the **concurrent connection-oriented** paradigm with **shared memory** and **FIFO**.

*These three servers must support all functions in Project 1.*

## Project3

> Score: 100

The project is divided into **two parts**.  

1. Write a simple HTTP server called **http_server** and a CGI program **console.cgi**. It should run on **NP Linux Workstation**.
2. Provides the same functionality as part 1, but with some rules slightly differs:  
   - Implement one program, **cgi_server.exe**, which is a combination of **http_server**, **panel.cgi**, and **console.cgi**.
   - Should run on **Windows 10**.

*Use **Boost.Asio** library to accomplish this project.*

## Project4

> Score: 100

Implement the **SOCKS 4/4A protocol** in the application layer of the OSI model.

*Use **Boost.Asio** library to accomplish this project.*

## Clone Project

```
git clone --recursive https://github.com/pf-lin/NYCU_Network_Programming.git
```
