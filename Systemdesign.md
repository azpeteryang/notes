Section 1: Networks and Protocols      
Section 2: Storage, Latency and Throughput      
Section 3: Availability      
Section 4: Caching      
Section 5: Proxies      
Section 6: Load Balance      
Section 7: Consistent Hashing      
Section 8: Databases      
Section 9: Leader Election      
Section 10: Polling, Streaming, Sockets      
Section 11: Endpoint Protection      
Section 12: Messages and Pub-Sub       
Section 13: Smaller Essentials       

# Networks and Protocols       
* IP - Internet Protocol
* TCP - Transmission Control Protocol      
* HTTP - Hyper Text Transfer Protocol      

# Storage, Latency and Throughput      
* Storage: "Disk storage" is persistent storage, "Memory storage" is temporary storage;      
* Latency: Reading from memory is much faster than reading form disk.      
* Throughput: The amount of data that can be pass in a unit of time, the way to increase the throughput is to increase the bottleneck of the system.           

# System Availability            
* Quantifying Availability: the percentage of time that the system's primary functionality and operations are available in a period of time.     
* SLAs: Service Level Agreements/ Assurances      
* Designing HA: Design a high availability (HA) system by designing 'redundancy' into the system.      

# Proxy
中间的服务器.     
There are two types of proxies: a forward proxy and a reverse proxy; A forward proxy act as a proxy to act as a client in the interaction between client and server;
A reverse proxy acts on behalf of a server;      
A reverse proxy is very useful for the reason that it can be delegated a lot of tasks that you don't want your main server to handle.      

# Load Balancing
Server Selection Strategy: Round Robin and Weighted Round Robin; Load-based server selection; IP Hashing based selection (select based on geography); Path or service based selection; Mixed Bag (Load balancers for load balancers, different levels of services and functions.)

# Data Base
* Retional Database: Highly structured
* Non-retional Database: More flexible, key-value pairs      
* Database indexing: find data more effeciently      
* Replication
* sharding      

# Leader Election
Choose a primary server to do some jobs      

# Polling, Streaming, Sockets      
* Polling is simply having your client "check" send a network request to your server and asking for updated data.      

