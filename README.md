![logo](https://repository-images.githubusercontent.com/632368150/928f4d3d-5363-48cf-975e-014eeb488f50)

![Hugo](https://img.shields.io/badge/Hugo-blowfish-FF4088?style=for-the-badge&logo=hugo&logoColor=white) ![GitHub deployments](https://img.shields.io/github/deployments/iunn-sh/blowfish/github-pages?logo=github&style=for-the-badge) ![Website](https://img.shields.io/website?logo=googledomains&logoColor=white&style=for-the-badge&url=https%3A%2F%2Fwww.chu-iu.pro)

# Chū-iû Law Firm

Official website https://www.chu-iu.pro/

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
