# Chū-iû Law Firm

* Implementation of [nunocoracao / blowfish](https://github.com/nunocoracao/blowfish)
* Hosting on Github Pages

## Local Development

```bash
# with docker
docker run --rm -it \
  -v $(pwd):/src \
  -p 1313:1313 \
  klakegg/hugo:0.101.0 \
  server
# with hugo 
hugo server

# visit http://localhost:1313 from browser
```

## Production Deployment

Commit or merge PR to `main` branch
