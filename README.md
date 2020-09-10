# P2P Server

A server to provide handshake for the client applications requesting to initiate peer-to-pear real-time communication (video call) connection.
This is a signalling server that forwards what it receives.

### Build JAR

Go to the directory where the project resides and execute the command
```sh
gradle clean jar
```
When the build is successful, navigate to directory `build/libs` using
```sh
cd build/libs
```

### Run

Run the following command from the terminal in the directory where the JAR file is present.

```sh
java -jar <jar_name>.jar 
```

### Tech

1. [Ktor](https://ktor.io) - Framework to create asynchronous server
2. [WebRTC](https://webrtc.org) - To add real-time communication capabilities to applications
3. [Gradle](https://gradle.org) - Building tool
