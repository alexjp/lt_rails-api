unicorn -E production -c config/unicorn.rb

~/A/a/p/s/a/controllers git:master ❯❯❯ loadtest -n 10000 -c 10 http://localhost:8080/users.json                                                     ✱ ◼
[Mon Mar 30 2015 08:59:20 GMT+0100 (WEST)] INFO Requests: 0 (0%), requests per second: 0, mean latency: 0 ms
[Mon Mar 30 2015 08:59:24 GMT+0100 (WEST)] INFO 
[Mon Mar 30 2015 08:59:24 GMT+0100 (WEST)] INFO Target URL:          http://localhost:8080/users.json
[Mon Mar 30 2015 08:59:24 GMT+0100 (WEST)] INFO Max requests:        10000
[Mon Mar 30 2015 08:59:24 GMT+0100 (WEST)] INFO Concurrency level:   10
[Mon Mar 30 2015 08:59:24 GMT+0100 (WEST)] INFO Agent:               none
[Mon Mar 30 2015 08:59:24 GMT+0100 (WEST)] INFO 
[Mon Mar 30 2015 08:59:24 GMT+0100 (WEST)] INFO Completed requests:  10000
[Mon Mar 30 2015 08:59:24 GMT+0100 (WEST)] INFO Total errors:        0
[Mon Mar 30 2015 08:59:24 GMT+0100 (WEST)] INFO Total time:          3.764137657 s
[Mon Mar 30 2015 08:59:24 GMT+0100 (WEST)] INFO Requests per second: 2657
[Mon Mar 30 2015 08:59:24 GMT+0100 (WEST)] INFO Total time:          3.764137657 s
[Mon Mar 30 2015 08:59:24 GMT+0100 (WEST)] INFO 
[Mon Mar 30 2015 08:59:24 GMT+0100 (WEST)] INFO Percentage of the requests served within a certain time
[Mon Mar 30 2015 08:59:24 GMT+0100 (WEST)] INFO   50%      3 ms
[Mon Mar 30 2015 08:59:24 GMT+0100 (WEST)] INFO   90%      4 ms
[Mon Mar 30 2015 08:59:24 GMT+0100 (WEST)] INFO   95%      4 ms
[Mon Mar 30 2015 08:59:24 GMT+0100 (WEST)] INFO   99%      10 ms
[Mon Mar 30 2015 08:59:24 GMT+0100 (WEST)] INFO  100%      37 ms (longest request)

