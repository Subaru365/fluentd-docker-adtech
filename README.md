# fluentd-docker-adtech
High availability fluentd docker image for adtech

## Usage

```
docker run \
    --sysctl net.core.somaxconn=10240 \
    -v ${td-agent.conf} /etc/td-agent/td-agent.conf
```

## References

- [Fluentd High Availability Configuration (td-agent3)](https://docs.fluentd.org/v1.0/articles/high-availability)

