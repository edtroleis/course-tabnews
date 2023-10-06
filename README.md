# course-tabnews

- [Node Version](./docs/NODE_VERSION.md)
- [Modules](./docs/MODULES.md)
- [Protocols](./docs/PROTOCOLS.md)
- [Git](./docs/GIT.md)
- [Tests](./docs/TESTS.md)

# Check README.md links

```
docker run -v ${PWD}:/tmp:ro --rm -i ghcr.io/tcort/markdown-link-check:stable /./tmp/README.md
```

# Versionamento de apis

## URI path versioning

```
https://www.tabnews.com.br/api/v1/contents
https://www.tabnews.com.br/api/v2/contents
```

## Header versioning

```
Accepts-Version: 1.5
Accepts-Version: 2023-09-21
```

# Run web server

```
npm run dev
```

# Métodos HTTP

- GET
- POST
- DELETE
- PUT
- PATCH
