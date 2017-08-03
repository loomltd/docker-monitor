# Loom rsyslog relay Docker

## Run the container

```shell
docker run -e CUSTOMER_NAME=<customer name> [-e DEBUG=true] --privileged loomsystems/loom-rsyslog-relay-docker
```

## Configuration with environment variables
* `CUSTOMER_NAME` - customer's name
* `DEBUG` [true|false] - start rsyslog with debug mode on (default is false)

For more information check [Loom Doc](http://support.loomsystems.com/sources/setting-up-a-syslog-relay "Loom Doc")
