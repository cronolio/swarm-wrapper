reimplementation for software like https://github.com/vitalets/docker-stack-wait-deploy

it works in foreground, waiting until docker services is actually up.

```
docker swarm wrapper

stack [command] [options] stack_name

command:
    up            - see 'docker stack deploy'
        options:  -c <path to compose file>
    status        - see 'docker stack ps'
    down          - see 'docker stack rm'
    help          - show this help
```

it is unfinished project. use on your own risk. features will be expanded.
