# Overview
Inspired by [Laravel Sail](https://github.com/laravel/sail), Raft provides a simple command-line interface to containerize and manage Docker-based node applications. 

# Instructions
Create a new appliction using the following command.
```
bash <(curl -s https://raw.githubusercontent.com/nikhilkutinha/raft/master/stubs/docker/bootstrap) <app_name>
```
An alias can be assigned to allow you to conveniently start the container using `raft up`.
```
alias raft='[ -f raft ] && bash raft || bash docker/raft'
```
