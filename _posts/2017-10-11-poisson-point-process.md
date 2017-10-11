## Motivation

Poisson point process is best suited to model the arrivals of packets due to fact that this math tool
involves a "memoryless" waiting time until the arrival of the next packet. The interarrival times provided
by Poisson process are therefore probabilistically independent, and this makes the Poisson process the most
convenient choice to model the packet arrivals.

## Definitions

The number of arrivals \\( N(t) \\) in a finite interval of length \\( t \\) obeys the Poisson \\( (\mu t) \\) distribution:

\\( \mathbb{P} ( N_{t} = k ) = \cfrac{(\mu t)^{k}}{k !} \cdot e^{-\mu t} \\)

Considering an interval \\( [a,b] \\) instead of \\( t \\), the previous equation becomes:

\\( \mathbb{P} ( N_{[a,b]} = k ) = \cfrac{\left [ \mu (b-a) \right  ]^{k}}{k !} \cdot e^{-\mu (b-a)} \\)

The inter-arrival times \\( (I) \\) are independent and obey the exponential  \\( (Exp(\mu)) \\)  distribution:

\\( \mathbb{P} ( \text{inter-arrival time} > t ) = e^{-\mu t} \\)


## References

E. Modiano, "Introduction to Queueing Theory." *Lecture Notes*, Massachusetts Institute of Technology.

