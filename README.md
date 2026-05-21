# HomeLab
This is a personal home lab that would showcase DevOps at its best.
```
homelab/
├── app/
│   ├── index.html
│   └── Dockerfile
├── .github/
│   └── workflows/
├── terraform/
├── ansible/
└── README.md

```
# Architecture
```
Developer
    │
    ▼
GitHub Repo
    │
    ▼
GitHub Actions Pipeline
    │
    ├── Build Docker Image
    ├── Test
    ├── Push Artifact
    └── Deploy
    │
    ▼
AWS EC2 Server
    │
    ├── Docker Runtime
    ├── App Container
    ├── NGINX Reverse Proxy
    └── Monitoring Later
