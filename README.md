# system-design

### Interesting reads:
1. [Scalable System Design Patterns](http://horicky.blogspot.com/2010/10/scalable-system-design-patterns.html)
2. [Google Pregeg graph processing model](http://horicky.blogspot.com/2010/07/google-pregel-graph-processing.html)
3. [Paxos algorithm](https://www.linkedin.com/pulse/building-consensus-distributed-systems-power-paxos-raft-salik-tariq#:~:text=Paxos%20is%20a%20family%20of,systems%20that%20require%20high%20availability.)
4. Popular consesus Algorithm


### Other Important links:
1. http://horicky.blogspot.com
           

### Engineering blog links

1. [Netlix](https://netflixtechblog.com/)
2. [Pinterest](https://medium.com/@Pinterest_Engineering)
3. [Databricks](https://databricks.com/blog/category/engineering) 
4. [Uber](https://eng.uber.com/)
5. [Quora](https://quoraengineering.quora.com/)
6. [Lyft](https://eng.lyft.com/)

### How to calculate System availability
The most widely held mechanism for measuring the availability of a web application is calculating the percent of time it’s accessible for use by customers. We can describe this by using the following formula for a given period:


> Site availability percentage = total_seconds_in_period − seconds_system_is_down / total_seconds_in_period

Let’s consider an example. Suppose that over the month of April, your website was down twice; the first time it was down for 37 minutes, and the second time it was down for 15 minutes. What is the availability of your website?

- Total number of seconds down = (37 + 15) × 60 = 3,120 s
- Total number of seconds in month = 30 days × 86,400 s/day = 2,592,000 s
- Site availability percentage = total_seconds_in_period − seconds_system_is_down / total_seconds_in_period
- Site availability percentage = 2,592,000 s − 3,120 s / 2,592,000 s Site availability percentage = 99.8795
- Your site availability is 99.8795%.

### The nines :

| Nines   | Percentage | Monthly outage |
| ------- | ---------- | -------------- |
| 2 nines | 99%        | 432 minutes    |
| 3 nines | 99.9%      | 43 minutes     |
| 4 nines | 99.99%     | 4 minutes      |
| 5 nines | 99.999%    | 26 seconds     |
| 6 nines | 99.9999%   | 2.6 seconds    |
     
