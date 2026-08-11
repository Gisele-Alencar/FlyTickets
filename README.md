# 🎟️ FlyTickets — Plataforma de Venda de Ingressos

> **Status:** Em desenvolvimento (Fly College)

O **FlyTickets** é uma plataforma de venda de ingressos projetada para suportar altíssima concorrência. O foco central da arquitetura é garantir disponibilidade e consistência durante picos extremos de tráfego, evitando vendas duplicadas e mitigando a ação de bots.

## 🎯 Requisitos de Arquitetura (NFRs Principais)
- **Escalabilidade:** Suportar até 10 milhões de usuários ativos (Pico: 50 mil requisições/minuto).
- **Consistência:** Garantia de concorrência real (0 vendas duplicadas do mesmo assento).
- **Disponibilidade e Resiliência:** Sistema operante mesmo sob ataque de bots ou falha parcial de serviços.
- **Desempenho:** Pesquisas de eventos com latência < 500ms.

