# Aggregation in GNNs 

This is the pre-reading used for investigating aggregation in GNNs.

## Principal Neighbourhood Aggregation
**[Principal Neighbourhood Aggregation for Graph Nets (2020, Corso et al.)](https://arxiv.org/pdf/2004.05718.pdf)**

This paper challenges the use of single aggregators (usually mean or max) in MPNN. In the image below you can see that no single aggregators can discriminate all the neghbourhoods
<img width="548" alt="image" src="https://user-images.githubusercontent.com/64110421/195933265-2363bc73-1af1-411f-88b5-24af571d9ddb.png">

This paper shows that for $n$ neighbours you need $n$ different aggregators to guarantee discrimination.

<img width="521" alt="image" src="https://user-images.githubusercontent.com/64110421/195933928-c2b330e8-e91c-46a1-bbf4-f87e667562d7.png">

Listed are more resources related to this paper: 
- [A lecture by Petar Velickovic](#)
- [A lecture by Dominique Beaini](https://www.youtube.com/watch?v=psN9SEStMHc&ab_channel=ValenceDiscovery)
- [A paper breakdown by Andrei Margeloiu](https://www.youtube.com/watch?v=i7pFDKrlb3I&ab_channel=AndreiMargeloiu-MachineLearning)

