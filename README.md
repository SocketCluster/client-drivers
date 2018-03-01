# Curated list of clients for SocketCluster

This is the list of SocketCluster client drivers for various languages and/or operating systems.

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

Feedback on existing clients is welcome.

---

## List of clients

**socketcluster-client (Official client)**  
Language: **JavaScript**  
Platform: **Web browser**  
Level: **L4**  
Authors: [jondubois](https://github.com/jondubois)  
Repo: https://github.com/SocketCluster/socketcluster-client

**socketcluster-client-java (Official Android client)**  
Language: **Java**  
Platform: **Any Java platform (including Android)**  
Level: **L4**  
Authors: [sacOO7](https://github.com/sacOO7)  
Repo: https://github.com/sacOO7/socketcluster-client-java

**SocketCluster-ios-client**  
Language: **Objective-C**  
Platform: **iOS**  
Level: **L4**  
Authors: [abpopov](https://github.com/abpopov)  
Repo: https://github.com/abpopov/SocketCluster-ios-client

**socketcluster-client-swift (Official iOS client)**  
Language: **Swift**  
Platform: **iOS**  
Level: **L4**  
Authors: [sacOO7](https://github.com/sacOO7)  
Repo: https://github.com/sacOO7/socketcluster-client-swift

**socketcluster-client-python (Official Python client)**  
Language: **Python**  
Platform: **Any Python platform**  
Level: **L4**  
Authors: [sacOO7](https://github.com/sacOO7)  
Repo: https://github.com/sacOO7/socketcluster-client-python

**socketcc (Unofficial Python3.6 client)**  
Language: **Python**  
Platform: **Any Python platform**  
Level: **L4**  
Authors: [Ramazan Polat](https://github.com/ramazanpolat)  
Repo: https://github.com/ramazanpolat/socketcc

**socketcluster-client-dot-net (Official .NET client)**  
Language: **C#**  
Platform: **.NET, Mono, Silverlight, WindowsPhone, Xamarin.Android, Xamarin.iOS, any .NET platform**  
Level: **L4**  
Authors: [sacOO7](https://github.com/sacOO7)  
Repo: https://github.com/sacOO7/SocketclusterClientDotNet

**PureSocketCluster (.NET Core NetStandard client)**  
Language: **C#**  
Platform: **.NET Core, NetStandard**  
Level: **L4**  
Authors: [coinigy](https://github.com/coinigy)  
Repo: https://github.com/coinigy/PureSocketCluster

**socketcluster-client-C (Official C client)**  
Language: **C**  
Platform: **Any platform which has a standard C compiler**  
Level: **L4**  
Authors: [sacOO7](https://github.com/sacOO7)  
Repo: https://github.com/sacOO7/socketcluster-client-C

**scio_beast**  
Language: **C++11 or higher**  
Platform: **All**  
Level: **L4**  
Authors: [Bryan Ashby](https://github.com/NuSkooler/)  
Repo: https://github.com/cw-zift/scio-beast

**socketcluster-client-go (Official Go client)**  
Language: **Go**  
Platform: **Any platform which has a Go compiler**  
Level: **L4**  
Authors: [sacOO7](https://github.com/sacOO7)  
Repo: https://github.com/sacOO7/socketcluster-client-go

---

**SocketCluster-android-client**  
Language: **Java**  
Platform: **Android**  
Level: **L4**  
Authors: [abpopov](https://github.com/abpopov), [dark58](https://github.com/dark58)  
Repo: https://github.com/abpopov/SocketCluster-android-client
