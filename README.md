[![Build Status](https://travis-ci.org/ncalibey/multi-docker.svg?branch=master)](https://travis-ci.org/ncalibey/multi-docker)
# multi-docker
A multi-container docker deployment for a Fibonacci program that uses a Nodejs application server and React for the client side. The user enters a number which is then routed to a worker (built in JavaScript) and used as the starting index of a fibonacci calculation whose results are stored in a PostgreSQL database. Redis is used for caching to speed up already used indexes, and the app is served on an Nginx web server.

The setup is purposefully cumbersome as the main point of this repository was to practice using a multi-container deployment in Docker. Part of Stephen Grider's [Docker and Kubernetes: The Complete Guide](https://www.udemy.com/docker-and-kubernetes-the-complete-guide/learn/v4/overview) Udemy course (excellent and highly recommended).
