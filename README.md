# 🐳 Docker Compose Collections

A curated collection of Docker Compose configurations for various self-hosted services, development tools, and infrastructure components.  
Each subfolder contains a ready-to-use `docker-compose.yml` tailored for a specific purpose or stack.

> Designed for developers, sysadmins, and DevOps professionals who want to deploy services quickly, reproducibly, and efficiently.

## 🔧 Usage

### Clone this repository

```bash
git clone https://github.com/your-username/docker-compose-collections.git
cd docker-compose-collections
```

### Navigate to the desired service

```bash
cd service-name
```

### Run the stack

```bash
docker-compose up -d
```

### Optional: Customize .env or mounted configs

## 📦 Included Stacks (Examples)

| Service      | Description                          |
| ------------ | ------------------------------------ |
| `squid`      | High-performance caching proxy       |
| `nginx`      | Lightweight HTTP reverse proxy       |
| `portainer`  | Docker management UI                 |
| `redis`      | In-memory key-value store            |
| `postgres`   | SQL database                         |
| `grafana`    | Metrics dashboard and visualizations |
| `prometheus` | Monitoring and alerting toolkit      |

> More services coming soon...

## 🛠️ Requirements

Docker (20.x or later)

Docker Compose v2+

Basic knowledge of shell / terminal usage

## 📘 Best Practices

Each compose file uses relative volume mounts and a .env file for environment-specific customization.

Designed to be portable, version-controlled, and self-documenting.

Services avoid hardcoded credentials; you can use environment variables or .env files safely.

## 🤝 Contributing

Feel free to fork, improve or submit pull requests!
If you want to add a new service, please follow the folder structure and naming conventions.

## 📄 License

MIT License — feel free to use, modify, and share.
