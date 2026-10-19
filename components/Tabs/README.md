---
id: tabs
name: Tabs
version: 1.0.0
radixPrimitive: Tabs
shadcnBase: tabs
---

# Tabs

Navegação entre painéis relacionados.

## Regras

- Trigger ativo: sublinhado vinho 2px + texto `vinhoEscuro`.
- Trigger inativo: texto `text.muted`.
- Hover: texto `vinhoEscuro` sem sublinhado.
- Espaçamento entre triggers: 32px (`spacing.8`).

```tsx
<Tabs defaultValue="visao">
  <Tabs.List>
    <Tabs.Trigger value="visao">Visão geral</Tabs.Trigger>
    <Tabs.Trigger value="cobertura">Cobertura</Tabs.Trigger>
  </Tabs.List>
  <Tabs.Content value="visao">...</Tabs.Content>
</Tabs>
```
