unicorn -E production -c config/unicorn.rb

loadtest -n 10000 -c 10 http://localhost:8080/users.json


check results.txt for results

