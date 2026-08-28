<h1 align="center">Hi 👋, I'm Udaykishore Resu</h1>
<h3 align="center">Principal Software Engineer | Control planes & data planes in Go Kubernetes • AWS/GCP • Spec-driven systems • LLMs in production pipelines</h3>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=20&pause=1000&color=2E9EF7&center=true&vCenter=true&width=600&lines=Building+cloud-native+systems+in+Go;12%2B+years+across+AWS+%26+GCP;Kubernetes+%7C+Terraform+%7C+GitOps;Observability-first+engineering" alt="Typing SVG" />
</p>

---

### 🧭 About Me

I build control-plane and data-plane systems on AWS and GCP — Go, Scala and Java distributed services that process 50M+ transactions daily at sub-millisecond latency, alongside the control planes that provision,authorize, govern and observe them across 50+ tenants.

The thing I've spent this year on is **Intent = Execution**: what a system actually does should be continuously provable against what was specified. That means spec-driven development with BPMN process models and invariant conformance contracts, a CI/CD gate that blocks any deployment diverging from the approved spec, and a conformance engine that scores every runtime execution against its contract and records the evidence.

Twelve years, starting in C++ on retail terminals and mobile hardware.I care most about systems that stay fast, secure, and boring in production — the kind of infrastructure people trust without thinking about it. These days I also use LLMs as engineering infrastructure rather than a demo: Claude in a C++-to-Go translation and test-harness pipeline, GPT-4 extraction in production data paths.
---

### 🚀 What I Do

- ☁️ **Cloud Infrastructure** — Multi-account, multi-cloud (AWS/GCP) environments codified with Terraform, AWS CDK, CloudFormation & GCP Deployment Manager
- ⚓ **Kubernetes at Scale** — EKS/GKE cluster administration, Helm-driven multi-environment deployments, mTLS service mesh security
- 🔁 **CI/CD & GitOps** — Automated pipelines (Jenkins, GitHub Actions) with deployment gates, health checks & rollback logic
- 📊 **Observability** — Full-stack instrumentation with OpenTelemetry, Prometheus, Grafana, Datadog & Splunk
- 🔐 **Security & IAM** — Zero-trust architectures: mTLS, OAuth2/OIDC, SSO, workload identity, KMS/HSM encryption, PCI-DSS & NIST compliance
- 🏗️ **Distributed Systems** — Event-driven microservices, BFF patterns, gRPC/REST/GraphQL/MQTT APIs at massive scale

---

### 🛠️ Tech Stack

**Languages**
![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Scala](https://img.shields.io/badge/-Scala-DC322F?style=flat-square&logo=scala&logoColor=white)
![Java](https://img.shields.io/badge/-Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)

**Cloud & Infrastructure**
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![GCP](https://img.shields.io/badge/-GCP-4285F4?style=flat-square&logo=google-cloud&logoColor=white)
![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/-Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Helm](https://img.shields.io/badge/-Helm-0F1689?style=flat-square&logo=helm&logoColor=white)

**CI/CD & Automation**
![Jenkins](https://img.shields.io/badge/-Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)

**Data & Messaging**
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![DynamoDB](https://img.shields.io/badge/-DynamoDB-4053D6?style=flat-square&logo=amazon-dynamodb&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Kafka](https://img.shields.io/badge/-Kafka-231F20?style=flat-square&logo=apache-kafka&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/-Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)

**Observability**
![Grafana](https://img.shields.io/badge/-Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/-Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Datadog](https://img.shields.io/badge/-Datadog-632CA6?style=flat-square&logo=datadog&logoColor=white)
![Splunk](https://img.shields.io/badge/-Splunk-000000?style=flat-square&logo=splunk&logoColor=white)

**APIs**
![REST](https://img.shields.io/badge/-REST-02569B?style=flat-square&logo=fastapi&logoColor=white)
![gRPC](https://img.shields.io/badge/-gRPC-2E7D8C?style=flat-square&logo=google&logoColor=white)
![GraphQL](https://img.shields.io/badge/-GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white)
![MQTT](https://img.shields.io/badge/-MQTT-660066?style=flat-square&logo=mqtt&logoColor=white)

---

### 🏆 Certifications

- ☁️ Google Cloud Professional Cloud Architect
- ☁️ AWS Certified Solutions Architect – Associate
- 🧑‍💻 Programming in Golang Specialization (Coursera)
- 🤖 Generative AI Fundamentals (Databricks)

---

### 📌 Highlight Projects

#### 🏦 Multi-Tenant SaaS Onboarding Platform

Self-service tenant onboarding platform built in Golang on AWS CDK, with SQS/Lambda event-driven pipelines and a fully VPC-isolated environment per tenant. Locked down with AWS KMS, IAM permission boundaries, and Secrets Manager, with CloudWatch and OpenTelemetry for full observability. Scales horizontally with a complete audit trail.

#### ⚡ Decision Orchestration Engine

gRPC-based decisioning services in Golang, fronted by a BFF layer exposing REST to consumer apps and secured with mTLS and OPA-based authorization. Processes 50M+ decisions/day at sub-millisecond latency, with OpenTelemetry tracing and automated SLO-based alerting.

#### 🔄 C++ → Golang Migration (NCR Voyix)

Led an 8-engineer team migrating a legacy C++ self-checkout SDK to Golang microservices on GKE, adding MQTT/Redis for device state and full OpenTelemetry observability. Cut latency 30%, grew adoption from 35% to 65%, and reached 95% automated test coverage.

#### 🗄️ IBM DB2 → AWS Aurora Migration

Two-phase, HSM-encrypted migration pipeline: a bulk historical load via Lambda and S3, followed by CDC via Qlik Replicate, Kafka, and AWS MSK for exactly-once delivery. Fully auditable and secured end to end with IAM and KMS.

#### 📈 Graphite Workflow Engine

Orchestration platform in Java/Spring Boot on AWS CDK, combining Fargate-based graph execution with Step Functions state machines for durable workflows, all behind a single Lambda API. Scales elastically with no EC2 to manage and a full replay/audit history.

---

### 🔗 Public Code
**Start here — three repos, in order:**

1. **[payments-platform](../../../payments-platform)** — a multi-tenant payment
   gateway in Go. Nine deployables, hexagonal, no framework. A twelve-step
   durable saga onboards merchants; a scored-routing orchestrator executes.
   *Read this one if you want to see how I structure a system.*

2. **[db-migration-platform](../../../db-migration-platform)** — zero-downtime,
   self-verifying database migration. LSN-fenced writes, watermark-based
   snapshot/CDC, hierarchical digest reconciliation, and a cutover gate that
   is a proof rather than a checklist.
   *Read this one if you want to see how I think about correctness.*

3. **[request-journey](../../../request-journey)** — one web request across
   browser, DNS, TLS, AWS, Kubernetes, data stores and observability, plus
   16 failure modes, all runnable.
   *Read this one if you want to see how I explain things.*

**Also public:**
- `agentgate` — provider-agnostic control plane for enterprise AI agents ·
- `vertex-sco-platform` — event-driven self-checkout edge platform ·
- `zero-trust-api-gateway` — identity-aware reverse proxy, sub-2ms p50 ·
- `specforge` — governed spec-driven engineering, hash-chained audit trail ·
- `infoblox-ipam-operator` — CRD-based IPAM allocation with drift detection .
---

### 📫 Let's Connect

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/udaykishore-resu)
[![Email](https://img.shields.io/badge/-Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:iamudaykishore@outlook.com)
[![Medium](https://img.shields.io/badge/-Medium-000000?style=flat-square&logo=medium&logoColor=white)](https://medium.com/@udaykishoreresu)
[![Instagram](https://img.shields.io/badge/-Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://instagram.com/mr.resu_)

<p align="center"><i>Open to collaborations on cloud-native architecture, platform engineering, and distributed systems.</i></p>
