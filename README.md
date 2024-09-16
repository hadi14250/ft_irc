<div align="center">
<a href="https://github.com/hadi14250">
    <img src="github_gifs/client-server.gif" alt="client server gif gif" width="150" height="150">
  </a>
  <h3 align="center">IRC: Internet Relay Chat</h3>
  Create Servers, chat with indidviduals or groups, connect to a gui client (irssi).
  <br>
  <br>
</div>


<div align="center">
<a href="https://github.com/hadi14250">
    <img src="github_gifs/chat.gif" alt="chat gif"  width="600" height="400">
  </a>


</div>

<br>


# IRC

 A project in the advanced stages of the 42 curriculum. The goal is to implement a functional IRC (Internet Relay Chat) server, providing a deep dive into network programming and client-server architecture. Throughout the project, we adhered to strict requirements, building the server from scratch using `C++` without relying on modern networking libraries. This experience sharpened our understanding of sockets, concurrency, and the intricacies of the IRC protocol.

<br>

## How to run locally

#### To create a server:

- Go to root directory and run `make`
- Run `./ircserv 1234 1234`
- The areguments are: `./ircserv <<port_number>> <<server_password>>`

#### To Join the server as client:

- Open a new terminal (shell)
- Run `nc localhost 1234`
- The areguments are: `nc <<port_number>>`
- After joining server, type `PASS 1234` and `enter`.
- After joining server, type `PASS 1234` and `enter`.
- Type `NICK <<your_name>>` and `enter`
- Type `USER <<USER_NAME>> <<REAL_NAME>>` and `enter`
- Create other clients and chat with them (see full list of commands below)


## Connect to a GUI