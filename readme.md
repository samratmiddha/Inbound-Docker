# Inbound

Recruitment manager for IMG

## Deployment

To deploy this project run

```bash
  git clone https://github.com/samratmiddha/Inbound-Docker.git
```

```bash
  cd Inbound-Docker
```

```bash
  git clone https://github.com/samratmiddha/Inbound-backend.git
```

```bash
  git clone https://github.com/samratmiddha/Inbound-Frontend.git
```

add .env files in Inbound-backend directory

set the variables in ./Docker/init.sql

set Postgres variables in docker-compose.yml

```bash
  Docker compose build
```

```bash
  Docker compose up
```
