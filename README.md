<p align="center">
<img src="./media/ascii-bat-light.svg#gh-light-mode-only" width="80%" alt="ascii bat" >
</p>
<p align="center">
<img src="./media/ascii-bat-dark.svg#gh-dark-mode-only" width="80%" alt="ascii bat">
</p>

&nbsp;

# Backend Engineering • Concurrency • Distributed Systems • Scalability

**Languages & Runtime**
<p align="left">
<img src="https://raw.githubusercontent.com/lightningbat/DevIcons/refs/heads/main/badges/badges_golang.png" width="50px" title="Golang">
<img src="https://raw.githubusercontent.com/lightningbat/DevIcons/refs/heads/add-missing-icons/badges/badges_nodejs.png" width="50px" title="Node.js">
<img src="https://raw.githubusercontent.com/lightningbat/DevIcons/refs/heads/add-missing-icons/badges/badges_typescript.png" width="50px" title="TypeScript">
<img src="https://raw.githubusercontent.com/lightningbat/DevIcons/refs/heads/add-missing-icons/badges/badges_javascript.png" width="50px" title="JavaScript">
<img src="https://raw.githubusercontent.com/lightningbat/DevIcons/refs/heads/add-missing-icons/badges/badges_python.png" width="50px" title="Python">
<img src="https://raw.githubusercontent.com/lightningbat/DevIcons/refs/heads/add-missing-icons/badges/badges_bash.png" width="50px" title="Bash">
</p>

**Protocols & API Architecture**
<p align="left">
<img src="https://raw.githubusercontent.com/lightningbat/DevIcons/refs/heads/add-missing-icons/badges/badges_grpc.png" width="50px" title="gRPC">
<img src="https://raw.githubusercontent.com/lightningbat/DevIcons/refs/heads/add-missing-icons/badges/badges_rest.png" width="50px" title="REST">
<img src="https://raw.githubusercontent.com/lightningbat/DevIcons/refs/heads/add-missing-icons/badges/badges_graphql.png" width="50px" title="GraphQL">
<img src="https://raw.githubusercontent.com/lightningbat/DevIcons/refs/heads/add-missing-icons/badges/badges_websocket.png" width="50px" title="WebSocket">
</p>

**Testing & Observability**
<p align="left">
<img src="https://raw.githubusercontent.com/lightningbat/DevIcons/refs/heads/add-missing-icons/badges/badges_k6.png" width="50px" title="K6">
<img src="https://raw.githubusercontent.com/lightningbat/DevIcons/refs/heads/add-missing-icons/badges/badges_cloudwatch.png" width="50px" title="CloudWatch">
<img src="https://raw.githubusercontent.com/lightningbat/DevIcons/refs/heads/add-missing-icons/badges/badges_grafana.png" width="50px" title="Grafana">
<img src="https://raw.githubusercontent.com/lightningbat/DevIcons/refs/heads/add-missing-icons/badges/badges_prometheus.png" width="50px" title="Prometheus">
</p>

**Storage**
<p align="left">
<img src="https://raw.githubusercontent.com/lightningbat/DevIcons/refs/heads/add-missing-icons/badges/badges_postgresql.png" width="50px" title="PostgreSQL">
<img src="https://raw.githubusercontent.com/lightningbat/DevIcons/refs/heads/add-missing-icons/badges/badges_redis.png" width="50px" title="Redis">
<img src="https://raw.githubusercontent.com/lightningbat/DevIcons/refs/heads/add-missing-icons/badges/badges_dynamodb.png" width="50px" title="DynamoDB">
<img src="https://raw.githubusercontent.com/lightningbat/DevIcons/refs/heads/add-missing-icons/badges/badges_mongodb.png" width="50px" title="MongoDB">
<img src="https://raw.githubusercontent.com/lightningbat/DevIcons/refs/heads/add-missing-icons/badges/badges_s3.png" width="50px" title="S3">
<img src="https://raw.githubusercontent.com/lightningbat/DevIcons/refs/heads/add-missing-icons/badges/badges_sqlite.png" width="50px" title="SQLite">
</p>

**Environment**
<p align="left">
<img src="https://raw.githubusercontent.com/lightningbat/DevIcons/refs/heads/add-missing-icons/badges/badges_docker.png" width="50px" title="Docker">
<img src="https://raw.githubusercontent.com/lightningbat/DevIcons/refs/heads/add-missing-icons/badges/badges_git.png" width="50px" title="Git">
<img src="https://raw.githubusercontent.com/lightningbat/DevIcons/refs/heads/add-missing-icons/badges/badges_linux.png" width="50px" title="Linux">
<img src="https://raw.githubusercontent.com/lightningbat/DevIcons/refs/heads/add-missing-icons/badges/badges_aws.png" width="50px" title="AWS">
</p>

---

## Featured Work

### [Distributed URL Shortener](https://github.com/lightningbat/distributed-url-shortener)
A horizontally scalable URL shortener designed for low-latency redirection.

**Key Highlights**
- Sustained peak throughput of 11,600 RPS on a single AWS t3.micro instance with zero socket errors
- Decoupled ID generation into an independent service that asynchronously pre-populates Redis.
- Dual-layer L1 (in-memory) + L2 (Redis) caching architecture

**Stack**
Go · Redis · k6

### [Resilient Rate Limiter](https://github.com/lightningbat/resilient-rate-limiter)

A Redis-backed Express rate-limiting middleware written in TypeScript with automatic degraded-mode fallback handling for high-availability environments.

**Key Highlights**
- Synchronizes rate limits across distributed instances using atomic Redis operations
- Handles Redis timeouts or disconnects via customizable fallbacks (local memory tracking or fail-open bypass)

**Stack**
TypeScript · Node.js · Redis

---

## Currently deep diving Into
- Distributed systems architecture  
- Horizontal scaling patterns  
- High-throughput API infrastructure


---

### Connect 
[LinkedIn](https://www.linkedin.com/in/r-raj--/) • [Email](mailto:raj@krynix.xyz)
