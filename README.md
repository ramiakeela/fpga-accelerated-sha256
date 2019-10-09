# FPGA-accelerated SHA256 Hash Algorithm

A Hardware/Software partitioned implementation of the SHA-256 hash algorithm used in mining cryptocurrencies like Bitcoin and Zcash. 

# Motivation for FPGA Adoption

Mining has often been associated with consuming too much power.

ASICs are over-consuming. They also become obsolete in a few months since they can't adapt to changes with algorithms.
GPUs are not computationally powerful, when compared to ASICS, and they are power hungry.

FPGAs solve all these issues and consume less power. They are also re-programmable, so algorithm changes are accommodated. 

Benefits:  
- Reconfigurability
- Low-power 
- High-throughput 
- Low-latency

![alt text](https://i.udemycdn.com/course/750x422/1149408_34fc_4.jpg "Logo Title Text 1")

# Methodology

Hardware/Software Partitioning algorithm to achieve acceleration. 

![partitioning_flowchart](https://user-images.githubusercontent.com/55208009/66450302-d96fca00-ea0c-11e9-8734-a62d48dde04d.jpg)

![Capture2](https://user-images.githubusercontent.com/55208009/66450692-45066700-ea0e-11e9-9a78-95650919e3cc.JPG)

![hls_flow](https://user-images.githubusercontent.com/55208009/66450700-49328480-ea0e-11e9-8dda-6c4ddb88323f.JPG)


# Demo

Pragmas/Directives Strategically Placed for Optimization.

![pragma](https://user-images.githubusercontent.com/55208009/66450497-9b26da80-ea0d-11e9-8441-960f160a2863.JPG)

Event Tracing Used to Avoid Dependencies.

![event_tracing](https://user-images.githubusercontent.com/55208009/66450559-daedc200-ea0d-11e9-9d00-43abc8e6e411.JPG)

![tracing](https://user-images.githubusercontent.com/55208009/66450652-2902c580-ea0e-11e9-9e82-4f670ab80232.JPG)

# Results

![results_sha256](https://user-images.githubusercontent.com/55208009/66450616-0e305100-ea0e-11e9-8366-70783bf75079.JPG)

* 3x faster than a CPU implementation



