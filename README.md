World cup social Network

Intro:

developed a social network platform designed to provide real-time updates and reports for an ongoing football tournament. This platform allows users to subscribe to specific game channels, enabling them to send and receive live reports and updates about the matches they are following.

Technical Implementation:

•	Server Implementation:
  - STOMP Server Services: The server uses the Simple (or Streaming) Text Oriented Messaging Protocol (STOMP) to handle messaging between clients and the server.
  - Thread-Per-Client Model: This design pattern assigns a dedicated thread to each client, ensuring reliable and straightforward handling of client requests and responses       up to a limited number of clients.
  - Reactor Design Pattern: This pattern allows the server to handle multiple client requests efficiently by demultiplexing incoming requests and dispatching them to the         appropriate handlers. It helps in managing numerous clients with minimal overhead, ensuring scalability.

•	Scalability and Efficiency: The Server supports both the Thread-Per-Client and Reactor design patterns, ensuring the system can scale according to the number of clients. This flexibility is crucial for maintaining high performance, low latency, and efficient resource utilization under varying loads.

Technologies  used:

C++, Java, OOP, multi-threading techniques. 
