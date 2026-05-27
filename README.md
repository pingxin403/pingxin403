<!-- 
  GitHub Profile README for pingxin403
  Displayed at https://github.com/pingxin403
-->

### Hi, I'm pingxin403 👋

Backend engineer focused on **microservices governance**, **platform engineering**, and **AI agent systems**. ~6 years Java + 2 years Go. CKA-certified. Based in Shenzhen, China.

后端工程师，专注**微服务治理 / 平台工程 / AI Agent 系统**。约 6 年 Java + 2 年 Go 实战，持有 CKA 认证，深圳。

---

#### What I work on / 在做什么

- **Service governance at scale** — service decomposition, API contract management, observability standards, SLO + error-budget-driven release gates
- **Platform engineering** — CI/CD pipelines, GitOps with ArgoCD/Flagger, internal developer platforms, golden-path templates
- **AI / Agent systems** — LangGraph orchestration, multi-tenant RAG, hybrid retrieval (dense + BM25), production-grade LLM pipelines

#### Architecture showcases / 公开作品

| Project | Stack | What it shows |
|---|---|---|
| **[cuckoo-echo-showcase](https://github.com/pingxin403/cuckoo-echo-showcase)** | FastAPI · LangGraph · Milvus · PostgreSQL RLS | Multi-tenant AI customer-service SaaS — architecture docs, 9 ADRs, 3 production runbooks. Source repo private; access by invitation. |
| **[cuckoo](https://github.com/pingxin403/cuckoo)** | Go · gRPC · Protobuf · K8s | Polyglot microservices monorepo — IM chat, URL shortener, unified auth. Envoy gateway, Kafka, etcd, full observability stack. |
| **[cuckoo-microservices](https://github.com/pingxin403/cuckoo-microservices)** | Spring Boot 3 · Spring Cloud Alibaba · Nacos · Seata | Java microservices learning project — service registry, distributed transactions, Sentinel circuit breaking, OpenTelemetry tracing. |
| **[platform-console](https://github.com/pingxin403/platform-console)** | Backstage · TypeScript · ArgoCD | Internal Developer Platform reference impl — service catalog, golden-path templates, observability integration. |
| **[genai-examples](https://github.com/pingxin403/genai-examples)** | Python · LangChain · RAG | Hands-on samples for retrieval-augmented generation and agent workflows. |

#### Areas of practice / 实战范围

```
Languages       Java · Go · Python · TypeScript
Frameworks      Spring Boot/Cloud · FastAPI · Gin · LangGraph · LangChain
Storage         MySQL · MongoDB · PostgreSQL · Redis · Elasticsearch · Milvus
Messaging       Kafka · RocketMQ · Pulsar · Eventbus
Cloud-native    Kubernetes (CKA) · Istio · Helm · Terraform · ArgoCD · Flagger
Observability   OpenTelemetry · Prometheus · Grafana · Jaeger · ELK · Langfuse
Patterns        Multi-tenancy (RLS / PartitionKey) · Distributed locks ·
                Idempotency · CDC · Saga · Hybrid retrieval · HITL workflows
```

#### Selected experience / 经验片段

- **Microservices governance** — service decomposition for high-change/high-traffic modules; OpenAPI/gRPC unified contract; circuit-breaker + cache fallback baselines as a platform capability
- **Heterogeneous DB migration** — MySQL → MongoDB via dual-write + Canal binlog sync; MySQL → AWS Aurora with read-replica middleware
- **Sharded MongoDB** — `(app_id, user_id:hashed)` compound shard key; 3-shard × 3-replica cluster behind Mongos
- **CI/CD platform** — GitHub Actions custom actions; CI build time 18 min → 6 min; Flagger canary tied to SLO + error budget; one-click rollback
- **Observability platform** — OTel-based unified pipeline; tail-sampling for storage cost reduction; layered alerting + standardized dashboards as a platform default

#### Contact / 联系方式

- 📫 Email — `pingxin0521 [at] 163.com`
- 💼 GitHub — you're here
- 🌏 Open to opportunities — backend / platform engineering / AI infra. Based in Shenzhen 🇨🇳; comfortable with remote and freelance, EN/中文 working language.

<!-- TODO: add LinkedIn / personal site / Medium when ready -->
<!-- TODO: consider adding GitHub stats card / language badges if a clean style is found -->
<!-- TODO: revisit pricing/availability disclosure for freelance once positioning is final -->
<!-- TODO: add open-source contribution highlights once any non-trivial PR lands upstream -->
<!-- TODO: pin layout review — re-order pinned repos as portfolio evolves -->
<!-- TODO: review every 3 months for drift between resume and showcases -->

---

<sub>This is a curated showcase. Some work is in private repos and shared on request — see [`cuckoo-echo-showcase`](https://github.com/pingxin403/cuckoo-echo-showcase) for an example of how I share private work for evaluation. 部分项目源码在私有仓库，按需开放只读权限做技术评估。</sub>
