# RRBR — rrbr-frontend

> **Frontend**: Real-time risk dashboards and AI chat interface in Portuguese.

[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](LICENSE)

## Overview

Next.js 15 frontend for the RRBR system. Real-time risk dashboards powered by WebSocket/SSE, with an integrated AI chat interface in Portuguese for natural language risk queries.

## Stack

- **Next.js 15** + **React** + **TypeScript**
- **Tailwind CSS** — styling
- **Recharts** — risk metric visualizations
- **TanStack Query** — server state management
- **WebSocket / SSE** — real-time dashboard updates
- **Zod** — runtime validation of all risk data from API

## Key Features

- Real-time portfolio risk dashboard (DV01, Greeks, FRTB capital)
- Yield curve visualization (Selic, DI, IPCA implicit)
- AI chat: "Explique o impacto FRTB da movimentação na curva DI"
- Human-in-the-loop approval interface for agent actions
- Multilingual: PT-BR first, EN supported

## License

Apache 2.0
