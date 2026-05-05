## 👋 Welcome to uptimekuma 🚀

Fancy self-hosted monitoring tool

## 📋 Description

Fancy self-hosted monitoring tool

## 🚀 Services

- **app**: louislam/uptime-kuma:latest

## 📦 Installation

### Option 1: Quick Install
```bash
curl -q -LSsf "https://raw.githubusercontent.com/composemgr/uptimekuma/main/docker-compose.yaml" -o compose.yml
```

### Option 2: Git Clone
```bash
git clone "https://github.com/composemgr/uptimekuma" ~/.local/srv/docker/uptimekuma
cd ~/.local/srv/docker/uptimekuma
docker compose up -d
```

### Option 3: Using composemgr
```bash
composemgr install uptimekuma
```

## 🔧 Configuration

### Environment Variables

```shell
TZ=America/New_York
```

See `docker-compose.yaml` for complete list of configurable options.

## 🌐 Access

- **Web Interface**: http://172.17.0.1:59068

## 📂 Volumes

- `./volumes/data/uptimekuma` - Data storage

## 🔍 Logging

```shell
docker compose logs -f app
```

## 🛠️ Management

```bash
# Start services
docker compose up -d

# Stop services
docker compose down

# Update to latest images
docker compose pull && docker compose up -d

# View logs
docker compose logs -f

# Restart services
docker compose restart
```

## 📋 Requirements

- Docker Engine 20.10+
- Docker Compose V2+

## 🤝 Author

🤖 casjay: [Github](https://github.com/casjay) 🤖  
🦄 composemgr: [Github](https://github.com/composemgr) 🦄
