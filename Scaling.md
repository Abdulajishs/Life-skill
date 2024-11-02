# Load Balancer and Scaling

# Load Balancer

### Function
* Load balancer takes the request and distributes it to different servers based on the workload handled by the server.
* It prevents no single server is overburdened.
  
### Benefits
* **Reliability:** If one server fails, another server handles the traffic by redistributing requests.
* **Scalability:** If the requests are higher, add more servers as needed by Auto-Scaling.

### Examples
* **Round Robin:** This method distributes, each request to the server in line in a circular sequence.
* **Smart Load Balancing:** This method distributes requests based on server load. If a server is too busy, the load balancer distributes the request to the least busy server. 
  

# Scaling

### Definition
* Scaling refers to adding resources to improve the system performance and handle more requests.

### Types

**Vertical Scaling**
* Vertical Scaling or Scaling-Up is adding more resources(CPU, RAM) to the single server to handle more requests.
* It is limited by the maximum capacity of one server.
* It is cheaper for the short term.
* Implementation is easier.

**Horizontal Scaling**
* Horizontal Scaling or Scaling-Out is adding more servers to share the load.
* It is flexible for handling more requests.
* It is cost-effective in the long term.
* Implementation is a bit complex.



### Reference
* https://www.youtube.com/watch?v=sCR3SAVdyCc
* https://www.youtube.com/watch?v=dvRFHG2-uYs
* https://www.youtube.com/watch?v=xUumgxZ04SM


