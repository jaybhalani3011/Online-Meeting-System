# WebRTC Online Meeting System

Simple Web Application that offer you to create video meeting room using WebRTC and Socket

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 

### Prerequisites

You have to install [Node.js](https://nodejs.org/en/) in your machine.

### Installing

After installing node clone the repo by using git

```
https://github.com/jaybhalani3011/Online-Meeting-System.git
                        or
git@github.com:jaybhalani3011/Online-Meeting-System.git
```

Or you can download the zip file.

Then open cmd or git bash on the project folder to install some modules that I used to build this project

Install Once

```
npm install
```

[Nodemon](https://www.npmjs.com/package/nodemon) For automatically restart the server as a dev dependency (optional)

```
npm i --sav-dev nodemon
```

## Setting Database

For the database I use [mongodb](https://www.mongodb.com/) [Atlas](https://www.mongodb.com/cloud/atlas). But you can use the local also.

If you don't have any account in [Atlas](https://www.mongodb.com/cloud/atlas). Visit the page and create a free account then get your connection string. More at [Documentation](https://docs.atlas.mongodb.com/tutorial/create-new-cluster/).

Use the file .env then replace "connection string" to your personal connection string

Example

```
DB_URI=mongodb+srv://omsdb:<password>@cluster0.kxj0d.mongodb.net/omsdb?retryWrites=true&w=majority
```

## Running the App

If you install nodemon then you can use. (dev script is already added to the package.json)

```
npm run dev
```

or

```
node server.js
```

## Built With

- [Node Js](https://nodejs.org/en/) - The Backend
- [Peer JS](https://peerjs.com/) - PeerJS simplifies WebRTC peer-to-peer data, video, and audio calls.
- [SocketIo](https://socket.io/) - For realtime communication
- [NPM](https://www.npmjs.com/) - Dependency Management
- [GIT](https://git-scm.com/) - Used for version control

## License

Video Chat is released under the [MIT license](LICENSE.txt).
