<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=26&duration=3000&pause=1000&color=FFB86C&center=true&vCenter=true&width=620&height=45&lines=Backend+engineer%2C+full-stack+when+needed.;I+build+systems+that+survive+traffic.;Java+%C2%B7+Spring+Boot+%C2%B7+Kafka+%C2%B7+Kubernetes">
  <source media="(prefers-color-scheme: light)" srcset="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=26&duration=3000&pause=1000&color=B45309&center=true&vCenter=true&width=620&height=45&lines=Backend+engineer%2C+full-stack+when+needed.;I+build+systems+that+survive+traffic.;Java+%C2%B7+Spring+Boot+%C2%B7+Kafka+%C2%B7+Kubernetes">
  <img alt="Backend engineer, full-stack when needed" src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=26&duration=3000&pause=1000&color=B45309&center=true&vCenter=true&width=620&height=45&lines=Backend+engineer%2C+full-stack+when+needed.;I+build+systems+that+survive+traffic.;Java+%C2%B7+Spring+Boot+%C2%B7+Kafka+%C2%B7+Kubernetes">
</picture>

# Likhith Raju P

**Software Development Engineer** at Webknot Technologies · Bengaluru, India

[![LinkedIn](https://img.shields.io/badge/LinkedIn-B45309?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/likhith-raju-p-775564179)
[![LeetCode](https://img.shields.io/badge/LeetCode-B45309?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/likhithraju1)
[![Email](https://img.shields.io/badge/Email-B45309?style=for-the-badge&logo=maildotru&logoColor=white)](mailto:YOUR_EMAIL@example.com)

</div>

---

## About

I work on the parts of a product that users never see and always feel — service boundaries, message queues, data models, and the instrumentation that tells you what broke at 2am. Java and Spring Boot are home; I pick up the frontend when a project needs one rather than because I want to live there.

Right now I'm most interested in **event-driven architecture** and **observability**: how systems behave under load, and how you find out when they stop behaving.

> [!NOTE]
> **Open to backend and platform engineering roles.** Best reached on [LinkedIn](https://linkedin.com/in/likhith-raju-p-775564179).

**A few facts**

| | |
|---|---|
| 🔭 **Building** | TraceFlow — a distributed tracing pipeline on OpenTelemetry + Kafka |
| 🌱 **Learning** | Kubernetes, cloud-native patterns, event-driven design |
| 🧩 **Practice** | 400+ LeetCode problems, top 8% — system design starts with data structures |
| 💬 **Ask me about** | Spring Boot internals, Kafka, concurrency, anything observability |

---

## Stack

<table>
  <tr>
    <td><b>Backend</b></td>
    <td>
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=java,spring,nodejs,kafka,redis&theme=dark">
        <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=java,spring,nodejs,kafka,redis&theme=light">
        <img height="44" alt="Java, Spring Boot, Node.js, Kafka, Redis" src="https://skillicons.dev/icons?i=java,spring,nodejs,kafka,redis">
      </picture>
    </td>
  </tr>
  <tr>
    <td><b>Data &amp; Infra</b></td>
    <td>
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=postgres,mysql,docker,kubernetes,aws,jenkins&theme=dark">
        <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=postgres,mysql,docker,kubernetes,aws,jenkins&theme=light">
        <img height="44" alt="Postgres, MySQL, Docker, Kubernetes, AWS, Jenkins" src="https://skillicons.dev/icons?i=postgres,mysql,docker,kubernetes,aws,jenkins">
      </picture>
    </td>
  </tr>
  <tr>
    <td><b>Frontend</b></td>
    <td>
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=react,nextjs,ts,tailwind&theme=dark">
        <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=react,nextjs,ts,tailwind&theme=light">
        <img height="44" alt="React, Next.js, TypeScript, Tailwind" src="https://skillicons.dev/icons?i=react,nextjs,ts,tailwind">
      </picture>
    </td>
  </tr>
</table>

---

## Featured work

### ShowTime — entertainment booking platform

Movies, live events and sports in a single booking flow, in the shape of BookMyShow.

**The hard part.** Seat inventory under concurrent demand. When a thousand people want the same three seats, correctness lives in how you handle holds, expiry and release — so that's where the design effort went, rather than in the CRUD around it.

`Java` `Spring Boot` `Microservices` `React` `Next.js` `Docker`

```
booking-service/     seat holds, reservations, payments
api-gateway/         routing, auth, rate limiting
client/              React + Next.js frontend
docker-compose.yml   one command to run the whole thing
```

[**→ Read the code**](https://github.com/likhithrajuuu/ShowTime)

<br/>

### TraceFlow — observability platform

Tracing and understanding distributed systems while they're running, not after the incident review.

**The hard part.** Ingesting high-volume spans without dropping them. Kafka absorbs the burst, the ingestor writes in batches instead of per-span, and a trace stays queryable end to end across service hops.

`OpenTelemetry` `Kafka` `Distributed Tracing`

```
otel-collector/      instrumentation + span collection
ingestor/            batched writes into storage
pipeline/            Kafka-backed, real-time
tracer/              end-to-end distributed tracing
```

[**→ Read the code**](https://github.com/likhithrajuuu/TraceFlow)

---

## Activity

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=likhithrajuuu&show_icons=true&hide_border=true&bg_color=0D1117&title_color=FFB86C&icon_color=FFB86C&text_color=C9D1D9&ring_color=FFB86C">
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api?username=likhithrajuuu&show_icons=true&hide_border=true&bg_color=FFFFFF&title_color=B45309&icon_color=B45309&text_color=24292F&ring_color=B45309">
  <img height="160" alt="GitHub statistics" src="https://github-readme-stats.vercel.app/api?username=likhithrajuuu&show_icons=true&hide_border=true">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=likhithrajuuu&hide_border=true&background=0D1117&ring=FFB86C&fire=FFB86C&currStreakLabel=FFB86C&sideLabels=C9D1D9&dates=8B949E&sideNums=C9D1D9&currStreakNum=C9D1D9">
  <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com?user=likhithrajuuu&hide_border=true&background=FFFFFF&ring=B45309&fire=B45309&currStreakLabel=B45309&sideLabels=24292F&dates=57606A&sideNums=24292F&currStreakNum=24292F">
  <img height="160" alt="Contribution streak" src="https://streak-stats.demolab.com?user=likhithrajuuu&hide_border=true">
</picture>

<br/><br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=likhithrajuuu&hide_border=true&bg_color=0D1117&color=FFB86C&line=FFB86C&point=C9D1D9&area=true&area_color=FFB86C">
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=likhithrajuuu&hide_border=true&bg_color=FFFFFF&color=B45309&line=B45309&point=24292F&area=true&area_color=B45309">
  <img alt="Contribution activity over the past year" src="https://github-readme-activity-graph.vercel.app/graph?username=likhithrajuuu&hide_border=true">
</picture>

</div>

---

<div align="center">
<sub>Always learning. Always building. Always curious.</sub>
</div>
