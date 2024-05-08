# Polynote

## Commands

```bash
docker run --rm -p 8192:8192 -p 4040-4050:4040-4050 -v ./config.yml:/opt/config/config.yml --name polynote polynote/polynote:0.5.2-2.12 --config /opt/config/config.yml
```

## Snippets

```scala
println("Hello, World!")
```

## References

- https://github.com/polynote/polynote
- https://hub.docker.com/r/polynote/polynote
- https://github.com/polynote/polynote/tree/0.5.2/docker
- https://polynote.org/latest/docs/server-configuration/
- https://github.com/polynote/polynote/blob/0.5.2/config-template.yml
- https://docs.scala-lang.org/tour/basics.html
