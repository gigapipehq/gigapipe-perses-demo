<a href="https://gigapipe.com" target="_blank">
  <img src='https://github.com/user-attachments/assets/fc8c7ca9-7a18-403d-b2a6-17899a534d33' style="margin-left:-10px;width:200px;" height=200 >
</a>

# <img src='https://avatars.githubusercontent.com/u/76224143?s=400&u=4e207cf756a7146392f9f04c6beb3940a417369d&v=4' style="margin-left:-10px" width=28 /> [Gigapipe: All-In-One Polyglot Observability](https://gigapipe.com)

## Gigapipe + [Perses.dev](https://perses.dev)

:rocket: Gigapipe is a _lighweight, multi-standard, polyglot **observability** stack for **Logs, Metrics**, **Traces** and **Profiling**_<br/>

:rocket: Perses is an open specification for dashboards and Grafana alternative for Prometheus, Tempo and beyond. CNCF Sandbox <br/>

<img src="https://perses.dev/assets/images/perses_overview.gif" />

This repository contains everything required to start the Perses + Gigapipe Demo

## Instructions
Use docker compose to launch the stack _(Gigapipe, ClickHouse, Perses)_

```
docker compose up -d
```

#### Services
- Perses on port 5000
- Gigapipe on port 3100
