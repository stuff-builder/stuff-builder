<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:0F172A,100:1E3A8A&height=150&text=stuff-builder&fontSize=48&fontColor=FFFFFF&fontAlignY=42&desc=Senior%20Full-Stack%20Engineer%20%C2%B7%20Startup%20to%20Enterprise&descSize=16&descAlignY=70&descColor=CBD5E1" alt="stuff-builder" width="100%" />
</p>

<p align="center">
  I design and build secure, scalable software for regulated industries —<br/>
  taking products from first MVP to enterprise-grade platforms.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/raymond-thomas-jr/"><img src="https://img.shields.io/badge/LinkedIn-0F172A?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <img src="https://img.shields.io/badge/Available_for-Contract_%26_Consulting-0F172A?style=flat-square" alt="Availability" />
</p>

---

### Focus

| Industries | What I deliver |
|:--|:--|
| **Fintech** · **Insurance** · **Healthcare** · **Legal Tech** · **SaaS** | Customer platforms, internal tools, public APIs, data pipelines, legacy modernization, cloud migration |

---

### Tech Stack

| | |
|:--|:--|
| **Languages** | <img src="https://skillicons.dev/icons?i=cs,py,ts,js,bash" height="36" /> |
| **.NET** | <img src="https://skillicons.dev/icons?i=dotnet" height="36" /> &nbsp; `ASP.NET Core` `Web API` `EF Core` `Blazor` `SignalR` `CQRS / MediatR` |
| **Python** | <img src="https://skillicons.dev/icons?i=django,fastapi,flask" height="36" /> &nbsp; `DRF` `Celery` `Pydantic` `SQLAlchemy` `Pandas` |
| **JavaScript** | <img src="https://skillicons.dev/icons?i=react,nextjs,nodejs,nestjs,express,tailwind" height="36" /> &nbsp; `Redux` `React Query` `Prisma` |
| **Cloud** | <img src="https://skillicons.dev/icons?i=azure,aws,gcp" height="36" /> &nbsp; `Azure Functions` `AWS Lambda` `Cloud Run` `API Gateway` `Service Bus` `SQS` |
| **DevOps** | <img src="https://skillicons.dev/icons?i=docker,kubernetes,terraform,githubactions" height="36" /> &nbsp; `Helm` `Azure DevOps` `Bicep` `OpenTelemetry` `Grafana` |
| **Data** | <img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis,kafka,rabbitmq,elasticsearch" height="36" /> &nbsp; `SQL Server` `Cosmos DB` `DynamoDB` `BigQuery` |
| **Security** | `OAuth 2.0 / OIDC` `Entra ID` `Auth0` `Key Vault / Secrets Manager` `HIPAA` `PCI DSS` `SOC 2` |
| **Testing** | `xUnit` `Pytest` `Jest` `Playwright` `Contract testing` |

---

### How I Work

```mermaid
flowchart LR
    A[Discover<br/><sub>goals · users · constraints</sub>] --> B[Design<br/><sub>architecture · data · risks</sub>]
    B --> C[Build<br/><sub>small slices · tested</sub>]
    C --> D[Ship<br/><sub>CI/CD · safe rollouts</sub>]
    D --> E[Measure<br/><sub>metrics · feedback</sub>]
    E -. iterate .-> A

    classDef step fill:#0F172A,stroke:#334155,color:#F8FAFC
    class A,B,C,D,E step
```

### How I Make Decisions

```mermaid
flowchart TD
    P([Business problem]) --> Q1{Can an existing<br/>service solve it?}
    Q1 -- Yes --> R1[Integrate, don't rebuild]
    Q1 -- No --> Q2{Sensitive or<br/>regulated data?}
    Q2 -- Yes --> R2[Security & compliance<br/>designed in from day one]
    Q2 -- No --> R3[Simplest design<br/>with room to scale]
    R1 --> M[Ship the smallest valuable slice<br/>→ measure → improve]
    R2 --> M
    R3 --> M

    classDef node fill:#0F172A,stroke:#334155,color:#F8FAFC
    classDef decision fill:#1E3A8A,stroke:#334155,color:#F8FAFC
    class P,R1,R2,R3,M node
    class Q1,Q2 decision
```

---

### Typical Architecture

```mermaid
flowchart LR
    U[Users] --> FE[Next.js / React]
    FE --> GW[API Gateway]
    ID[Identity<br/>OAuth2 / OIDC] -.- GW
    GW --> SVC

    subgraph SVC[Services · Kubernetes / Serverless]
      direction TB
      S1[.NET]
      S2[Python]
      S3[Node.js]
    end

    SVC --> DB[(SQL / NoSQL)]
    SVC --> CA[(Cache)]
    SVC --> MQ[[Event Bus]] --> FN[Background<br/>Functions]
    OBS[Observability · CI/CD · IaC] -.-> SVC

    classDef node fill:#0F172A,stroke:#334155,color:#F8FAFC
    class U,FE,GW,ID,S1,S2,S3,DB,CA,MQ,FN,OBS node
    style SVC fill:#1E3A8A,stroke:#334155,color:#F8FAFC
```

---

### Engineering Principles

| Principle | In practice |
|:--|:--|
| **Outcomes over output** | Every feature ties back to a user or business result |
| **Simple first, scalable next** | Clear boundaries so growth is a refactor, not a rewrite |
| **Secure by default** | Least privilege, encryption, secrets management, audit trails |
| **Observable systems** | Logs, metrics and traces ship with every feature |
| **No surprises** | Written designs, honest estimates, early risk flags |

---

### GitHub Activity

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=stuff-builder&show_icons=true&count_private=true&include_all_commits=true&hide_border=true&bg_color=0F172A&title_color=F8FAFC&text_color=CBD5E1&icon_color=60A5FA" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=stuff-builder&layout=compact&hide_border=true&bg_color=0F172A&title_color=F8FAFC&text_color=CBD5E1&langs_count=6" alt="Top languages" />
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/stuff-builder/stuff-builder/output/github-contribution-grid-snake-dark.svg" />
    <img alt="Contribution snake" src="https://raw.githubusercontent.com/stuff-builder/stuff-builder/output/github-contribution-grid-snake.svg" />
  </picture>
</p>

---

<p align="center">
  <sub>Have a product to launch, a platform to scale, or a system to modernize? &nbsp;·&nbsp; <a href="https://www.linkedin.com/in/raymond-thomas-jr/">Let's talk</a></sub>
</p>
