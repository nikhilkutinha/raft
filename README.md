# Overview
Inspired by [Laravel Sail](https://github.com/laravel/sail), Raft provides a simple command-line interface to containerize and manage Docker-based node applications. 

# Instructions
Copy over the files from the `./stubs` folder into the root of your node application and run the following command.

```
bash ./docker/bootstrap
```
An alias can be assigned to allow you to conveniently start the container using `raft up`.
```
alias raft='[ -f raft ] && bash raft || bash docker/raft'
```