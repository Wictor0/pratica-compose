# Ambiente DevOps

Ambiente reproduzível com Nginx, MySQL e phpMyAdmin orquestrados pelo Docker Compose.

## Pré-requisitos
- Ubuntu com Docker e Docker Compose (plugin v2) instalados
- Git

## Inicializar
```bash
docker compose up -d
```

## Verificar
```bash
docker compose ps
```
- Nginx: http://localhost:8080
- phpMyAdmin: http://localhost:8081 (servidor: `mysql`, usuário: `root`, senha: `123456`)

## Encerrar
```bash
docker compose down
```

> As senhas explícitas são apenas didáticas. Em ambientes reais, credenciais não devem ser versionadas em texto puro.
