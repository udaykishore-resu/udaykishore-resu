<h1 align="center">Hi 👋, I'm Udaykishore Resu</h1>
<h3 align="center">Principal Software Engineer | Golang & Cloud Platform Engineering | Kubernetes • Terraform • Multi-Cloud</h3>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=20&pause=1000&color=2E9EF7&center=true&vCenter=true&width=600&lines=Building+cloud-native+systems+in+Go;12%2B+years+across+AWS+%26+GCP;Kubernetes+%7C+Terraform+%7C+GitOps;Observability-first+engineering" alt="Typing SVG" />
</p>

---

### 🧭 About Me

I'm a **Principal Software Engineer** with **12+ years** of experience building and operating production infrastructure at scale — from Fortune 500 fintech platforms to embedded IoT systems. My core focus is **Golang backend engineering** and **cloud platform engineering**, with deep, hands-on expertise in **Kubernetes (EKS/GKE)**, **Infrastructure as Code**, **zero-trust security**, and **observability-driven operations**.

Currently at **Capital One**, I'm building **multi-tenant SaaS onboarding platforms** and **sub-millisecond decision engines** that process 50M+ transactions daily. I care most about systems that stay fast, secure, and boring in production — the kind of infrastructure people trust without thinking about it.

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
- **Situation:** Manual per-tenant provisioning couldn't keep up as onboarding needed to be fast, secure, and isolated for every new tenant. 
- **Task:** Build a self-service onboarding platform that scales horizontally while keeping each tenant fully isolated. 
- **Action:** Built the platform in Golang on AWS CDK, with SQS/Lambda event-driven pipelines (DLQ-isolated per stage) and CloudFormation managed stacks; gave each tenant a VPC-isolated environment with Route 53 private hosted zones, locked down with AWS KMS, IAM permission boundaries, and Secrets Manager; added CloudWatch Alarms and Synthetics canaries plus OpenTelemetry tracing into Splunk, with usage streamed to Snowflake for analytics. 
- **Result:** A horizontally auto-scaling, tenant-isolated onboarding platform with continuous validation and a full audit trail.

#### ⚡ Decision Orchestration Engine
- **Situation:** Consumer-facing apps needed decisions at massive scale without being tightly coupled to the decisioning system's internal topology.
- **Task:** Build the core decisioning services and a safe, simple way for client apps to consume them.
- **Action:** Built Decision Orchestration and Decisioning Core in Golang over gRPC, fronted by a BFF layer that aggregates results into REST for consumers, documented with UML diagrams; secured service-to-service traffic with mTLS, OPA-based authorization, and short-lived JWTs; instrumented with OpenTelemetry into Splunk Observability Cloud and CloudWatch SLO-based alerting.
- **Result:** 50M+ decisions per day at sub-millisecond latency, fully encrypted traffic, and automated on-call paging when SLOs slip.

#### 🔄 C++ → Golang Migration (NCR Voyix)
- **Situation:** A legacy C++ self-checkout SDK was slowing down processing and capping how fast new stores could be onboarded.
- **Task:** Lead the migration to a cloud-native stack without disrupting live store operations.
- **Action:** Rebuilt the SDK as Golang microservices deployed on GKE via Helm; added MQTT pub/sub and Redis caching for device state; built a BFF (internal gRPC, external REST via a posless adapter) with Cloud DNS and VPC peering; wired up OpenTelemetry tracing into Splunk, automated test harnesses, and mTLS with least-privilege IAM. Led an 8-engineer team through the cutover.
- **Result:** 30% latency reduction, checkout adoption up from 35% to 65%, 95% automated test coverage, and milestones delivered 15% ahead of schedule.

#### 🗄️ IBM DB2 → AWS Aurora Migration
- **Situation:** A DB2-to-Aurora migration had to happen without gaps in data integrity, security, or availability.
- **Task:** Architect a two-phase migration covering both the bulk historical load and ongoing change data.
- **Action:** Phase 1 used an HPC unload pipeline with SAFENET HSM encryption, S3 staging, and Lambda-driven bulk inserts protected by IAM and a KMS customer-managed key; Phase 2 layered on Qlik Replicate for CDC, an on-prem Kafka Data Encryptor, AWS MSK, a Scala-based Data Replicator, and a Schema Replicator to guarantee exactly-once delivery; the whole pipeline was secured with IAM, KMS, Direct Connect, and Splunk alerting.
- **Result:** An HSM-encrypted, event-driven, exactly-once migration pipeline that's fully auditable end to end.

#### 📈 Graphite Workflow Engine
- **Situation:** Decisioning pipelines needed a unified way to run graph-based execution and long-running workflows with clear contracts between teams.
- **Task:** Build an orchestration platform covering both graph execution and durable state machines.
- **Action:** Built the engine in Java/Spring Boot on AWS CDK with API contracts defined via SpecKit; graph execution runs in containerized tasks on Fargate backed by DynamoDB, while long-running workflows run as Step Functions state machines with DynamoDB-backed persistence for auditability and replay; a Lambda API layer fronts both paths as a single entry point.
- **Result:** A unified orchestration platform that scales elastically with no EC2 to manage, keeps a full replay/audit history, and gives consuming teams one decoupled entry point.

---

### 📫 Let's Connect

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/udaykishore-resu)
[![Email](https://img.shields.io/badge/-Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:iamudaykishore@outlook.com)
[![Medium](https://img.shields.io/badge/-Medium-000000?style=flat-square&logo=medium&logoColor=white)](https://medium.com/@udaykishoreresu)
[![Instagram](https://img.shields.io/badge/-Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://instagram.com/mr.resu_)

<p align="center"><i>Open to collaborations on cloud-native architecture, platform engineering, and distributed systems.</i></p>
