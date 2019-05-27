# docker-progpilot
Dockerized version of progpilot

##About
> A static analyzer for security purposes.
> Only PHP language is currently supported.
> The main reason for this project for being an extension of progpilot is to have easy integration into continuous integration systems.
> progpilot is backed by [designsecurity] (https://github.com/designsecurity/progpilot).

## Run

### Default Rules

```bash
docker run -t -v "$(pwd)":/opt/mount/ itsdg4u/docker-progpilot:latest
```


## Contributing

Have some improvements? Send a pull request! Thank you!
