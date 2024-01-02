![logo](https://raw.githubusercontent.com/iunn-sh/blowfish/main/content/feature-logo-card.png)

![Hugo](https://img.shields.io/badge/Hugo-0.121.1-FF4088?style=for-the-badge&logo=hugo&logoColor=white) ![GitHub deployments](https://img.shields.io/github/deployments/iunn-sh/blowfish/github-pages?logo=github&style=for-the-badge) ![Website](https://img.shields.io/website?logo=googledomains&logoColor=white&style=for-the-badge&url=https%3A%2F%2Fwww.chu-iu.pro)

# Chū-iû Law Firm

Official website https://www.chu-iu.pro/

* Implementation of [nunocoracao/blowfish](https://github.com/nunocoracao/blowfish)
* Hosting on Github Pages

## Local Development

### Run Server

```bash
# with docker
docker run --rm -it \
  -v $(pwd):/src \
  -p 1313:1313 \
  klakegg/hugo:0.111.3 \
  server
# with hugo 
hugo server

# visit http://localhost:1313 from browser
```

### Update

```bash
git submodule update --remote --merge
```

## Production Deployment

Commit or merge PR to `main` branch
