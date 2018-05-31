### Summary
Reducing network latency in mobile applications is an effective
way of improving the mobile user experience and has tangible
economic benefits. This paper presents PALOMA, a novel client-centric
technique for reducing the network latency by prefetching
HTTP requests in Android apps. Our work leverages string analysis
and callback control-flow analysis to automatically instrument
apps using PALOMA’s rigorous formulation of scenarios that address
“what” and “when” to prefetch. PALOMA has been shown
to incur significant runtime savings (several hundred milliseconds
per prefetchable HTTP request), both when applied on a reusable
evaluation benchmark we have developed and on real applications.

### Publications
Yixue Zhao, Marcelo Schmitt Laser, Yingjun Lyu, and Nenad Medvidovic. **“Leveraging Program Analysis to Reduce
User-Perceived Latency in Mobile Applications.”** Accepted for the 40th International Conference on Software Engineering **(ICSE 2018)**.
[Paper Link](https://softarch.usc.edu/~yixue/mypapers/ICSE2018_PALOMA.pdf) 
[Poster](https://softarch.usc.edu/~yixue/file/ICSE2018Poster.pdf)

### Repositories
* [PALOMA Analysis](https://github.com/felicitia/PALOMA-Analysis) 
* [PALOMA Proxy](https://github.com/felicitia/XposedProxy)
* [MBM Server](https://github.com/felicitia/PALOMA-MBM-Server)
* [MBM Test Cases](https://github.com/felicitia/PALOMA-MBM)

### Contact
Yixue Zhao [[website]](https://softarch.usc.edu/~yixue/) [email: yixue.zhao [AT] usc.edu]
