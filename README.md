# codeboost-ci-demo
codeboost ci demo

# Topics
- Docker
- Automation
- Deployment

# References
- Docker Setup tool - https://github.com/jackkweyunga/docker-setup
- My Articles - https://jackkweyunga.hashnode.dev/

# File structure

```shell
├── requirements.txt
├── Dockerfile
├── README.md
├── .dockerignore
├── .gitignore
├── .github
│   └── workflows
│       └── container.yml
└── main.py
```

# Running

1. Build docker image
```shell
# Use sudo if on linux / If not using rootless docker
docker build -t my-app .
```

2. Run a docker container
```shell
docker run -p 5000:5000 my-app
```

3. Visit http://localhost:5000
