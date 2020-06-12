# NETCore3.1-Udemy-ProducerConsumerRabbitMQ

# follow the steps od tutotial below to install RabbitMQ on Linux Mint distribution
https://www.fosslinux.com/6339/how-to-install-rabbitmq-server-on-ubuntu-18-04-lts.htm


# some commands:
## to clean all
### stop rabbitmq
$ sudo rabbitmqctl stop_app
### reset rabbitmq
$ sudo rabbitmqctl reset
### start rabbitmq
$ sudo rabbitmqctl start_app


## to add user
### add user and password
$ sudo rabbitmqctl add_user test test
### set tag [administrator]
$ sudo rabbitmqctl set_user_tags test administrator
### set permmissions read and write
$ sudo rabbitmqctl set_permissions -p / test ".*" ".*"
