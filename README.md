<h1 align="center">Hi, I'm Lucas Martins 👋</h1>
<p align="center"><b>Backend Software Engineer · Java · Quarkus · Event-driven systems</b><br/>São Paulo, Brazil · Card issuing & personalization @ F1RST (Santander group)</p>

<p align="center">
  <a href="https://www.linkedin.com/in/lucashmartins/"><img src="https://img.shields.io/badge/LinkedIn-lucashmartins-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
</p>

---

### About me
I build backend systems for **card issuance and personalization** in banking: REST microservices and event-driven integrations that have to stay correct and reliable under load.

- 🏦 Software Engineer at **[F1RST Digital Services](https://www.f1rst.com.br/)** (Santander group) since 2022
- ⚙️ Day to day: Java + Quarkus services, Kafka/RabbitMQ, PostgreSQL, OAuth2, outbox & idempotency
- ☁️ Running on AWS and Kubernetes, observed with OpenTelemetry, Dynatrace and Grafana
- 🏃 Off the keyboard: running and hiking

### Tech stack
<p>
  <img src="https://skillicons.dev/icons?i=java,quarkus,kafka,rabbitmq,postgres,aws,kubernetes,grafana&perline=8" alt="Java, Quarkus, Kafka, RabbitMQ, PostgreSQL, AWS, Kubernetes, Grafana"/>
</p>

| Area | Tools |
| --- | --- |
| Language & framework | Java, Quarkus |
| APIs & patterns | REST, microservices, OAuth2, transactional outbox, idempotency, batch & concurrency |
| Messaging | Kafka, RabbitMQ |
| Data | PostgreSQL / SQL |
| Cloud | AWS (S3, IAM, Secrets Manager, API Gateway, CloudWatch), Kubernetes |
| Observability | OpenTelemetry, Dynatrace, Grafana |

### Highlights
- 📈 Reworked a card-processing app that failed at **~500 cards** into a batch pipeline handling **~30k cards** (concurrency, clearer boundaries, resource usage).
- 🔌 Designed a partner integration (REST + Kafka + OAuth2 + outbox/idempotency) that moved card requests from a **daily window to continuous processing**.
- 🧭 Implemented **leader election** with Kubernetes leases across **8 apps** to coordinate replica work.
- 🚨 Led a **~12h production cutover** / war-room migration.

### Projects
- [finance-starter](https://github.com/Lucash16/finance-starter): Self-hosted personal finance stack: Next.js dashboard + Supabase/Postgres + Pluggy Open Finance sync.

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)

<!-- Enable once a few repos are public (cards only count public repos):
<p>
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Lucash16&show_icons=true&hide_border=true&theme=transparent" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Lucash16&layout=compact&hide_border=true&theme=transparent" />
</p>
-->
