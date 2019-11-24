# awsx

Strategic script for easy access to AWS instances.

## authorize-security-group-ingress

```
$ ./scrtips/authorize-security-group-ingress [security group name] [tcp|udp] [port] [x.x.x.x/x]
```

## describe-security-group

To show the details of specific security group, you need to specify the name of related EC2 instance:

```
$ ./scripts/describe-security-group [key words]
```

## list-security-groups

List security groups, showing corresponding EC2 name

```
$ ./scripts/list-security-groups
```
