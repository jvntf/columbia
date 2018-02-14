# 2/4/18 #

1. Packet Loss
    * if u have inf buffers, packet loss will never happen
    * we have finite buffers, sometimes u fill them up, so some packets get dropped
    * 
2. Throughput
    * indicator of performance
    * link by link metric
    * speed of bits per time unit transfer speed
    * 
3. Protocol layers
    * more complex than a single computer because you have pieces operating at different speeds
    * cannot build systems ad hoc
        - 
    * what is the point of layering
        - id, relationship of complex systen
        - compartmentalization of tech and components
        - have parts evolve independently
        - harmful aspects of layering
            + there is a penalty
                * black boxes, information hiding, information failure
                * abstraction is counterproductive
            + 
    * layers
        - application
        - transport
        - network
        - link
        - physical
    * iso/oci refernce model
        - presentation
        - session
    * two layer model
        - content / apps services
        - internet layer in the middle
        - lower layers (infrastructure)
    * hour glass model (IP is the main long term stable interface)
    * encapsulation
        - 
    * serialization
        - how to send data without depending on comp arch or using memory references
        - go from multi dimensional space to linear space
        - ASN.1
    * 
4. 