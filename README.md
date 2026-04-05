## This project provides observability for a Redis-based recommendation system.

It monitors:
- Redis performance (memory, ops/sec, clients)
- User interaction patterns
- Interest evolution
- Engagement distribution

Stack:
- Redis (external)
- Redis Exporter
- Prometheus
- Grafana


1. Copy .env.example → .env
2. Fill Redis credentials
3. Run:

docker compose up -d
