# Curated list of clients for SocketCluster

This is the list of SocketCluster client drivers for various languages and/or operating systems.
We cannot guarantee the quality of all clients in this list so we really appreciate your feedback.

If you wrote an open source SC client and would like to add it to this list, you should submit a PR with
the name of your client, GitHub repo URL, language/platform and the original author's GitHub username (follow the convention).

Note that the official JavaScript socketcluster-client offers a number of features - Third-party clients
may not necessarily support all these features - For this reason, we think it's important to classify
clients into different levels based on what features they offer.
Note that each level builds on top of the previous one; so a client cannot be considered L3 unless it implements all the required features of both L1 and L2.

The levels are:

- L1: Support for emitting and listening to remote events (without automatic reconnection).
- L2: Automatic reconnection
- L3: Pub/sub
- L4: Authentication (JWT)

---

## List of clients

**socketcluster-client (Official client)**  
Language: **JavaScript**  
Platform: **Web browser**  
Level: **L4**  
Authors: [jondubois](https://github.com/jondubois)  
Repo: https://github.com/SocketCluster/socketcluster-client

**SocketCluster-android-client**  
Language: **Java**  
Platform: **Android**  
Level: **L4**  
Authors: [abpopov](https://github.com/abpopov), [dark58](https://github.com/dark58)  
Repo: https://github.com/abpopov/SocketCluster-android-client

**socketcluster-client-ios**  
Language: **Objective-C**  
Platform: **iOS**  
Level: **L3**  
Authors: [lihan](https://github.com/lihan)  
Repo: https://github.com/SocketCluster/socketcluster-client-ios
