# docker-examples

- A collection of Dockerfile examples for various configurations.

## notes
### About `docker-compose.yml`
- All Dockerfile are assumed to be referenced from the root of the repository.
- You need to specify the build context and the Dockerfile location in the `docker-compose.yml` file under the `build` section.

Example configuration:

```yml
    build:
      context: .
      dockerfile: docker/*
```
