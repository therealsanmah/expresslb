# expresslb
Sample implementation of a loadbalancer from https://www.lunchbadger.com/build-load-balancer-express/

Created a sample express server that handles all GET and POST requests at server.js, listening on two ports, mimicking two http servers.

Created a loadbalancer in lb.js that loadbalances between the two servers created above. 

Added https support and loadbalances over http on 8080 and https on 8443. 
