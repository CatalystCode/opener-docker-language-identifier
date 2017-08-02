# opener-docker-language-identifier

[![Deploy to Azure](https://azuredeploy.net/deploybutton.svg)](https://azuredeploy.net/)
[![Docker Pulls](https://img.shields.io/docker/pulls/cwolff/opener-docker-language-identifier.svg)](https://hub.docker.com/r/cwolff/opener-docker-language-identifier/)

Dockerfile for OpeNER language identifier service.

Run and test locally:

```bash
docker run -p 8080:80 cwolff/opener-docker-language-identifier

text="I went to Rome last year. It was fantastic."
curl -d "input=$text" http://localhost:8080
```
