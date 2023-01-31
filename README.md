# MessageBrokerRabbitMq
Message Broker RabbitMq exploration

RabbitMq message broker.
why it is required ? 
Nowdays every application is moving from Monolithic application to micro-services and in micro-services everything is modular and hence the messaging will be every crucial part of architecture. so rabbitMq is being used.

Advantages.
1. Light-weight
2. HighlyScalable
3. supports varity of protocols
4. Interoperability
5. Enterprise and cloud ready
6. Decouple producers and consumers of messages, allowing for more flexible and scalable systems.
7. Provide reliable delivery of messages, with features such as guaranteed delivery and retry mechanisms.
8. Support asynchronous communication, enabling different parts of a system to run independently.
9. Implement complex routing and processing patterns, like publish-subscribe, fanout, and dead-letter exchanges.
10. Balance workloads and distribute messages evenly across consumers, improving system performance and resilience.


More on AMQP(Advanced message queueing protocol)
IT is the set of rule so that application should adhere to in-oder to send messages. It provides a way for applications to exchange messages reliably and asynchronously, regardless of the underlying hardware and software. It enables interoperability between different systems that implement the protocol. AMQP is commonly used in applications that need to handle high volumes of messages, support complex routing and processing, and ensure delivery of messages even in the presence of failures.

Routing and Processing: AMQP supports complex routing and processing patterns, such as publish-subscribe, fanout, and dead-letter exchanges, making it possible to build scalable and flexible systems.

Broker-based Architecture: AMQP uses a broker-based architecture, where messages are sent to a central message broker, which is responsible for routing and delivering the messages to their intended recipients. This architecture provides several benefits, such as scalability, reliability, and security.

Language Agnostic: AMQP is language agnostic, meaning that it can be used with a wide variety of programming languages, including Java, Python, Ruby, and more. This makes it easier to integrate with existing systems and develop new applications.



