---
id: card
name: Card
status: stable
version: 1.0.0
category: container
shadcnBase: card
tokens:
  - colors.semantic.surface.default
  - colors.semantic.surface.subtle
  - spacing.radius.lg
  - spacing.shadow.sm
---

# Card

Contêiner de conteúdo agrupado. Três variantes cobrem 90% dos usos na Uniodonto.

## Variantes

### `plano` — Card de plano odontológico
Fundo branco, borda sutil, accent superior em cor complementar (roxo padrão). Título do plano em `heading-3`, preço em `display-md`, lista de benefícios.

### `cooperado` — Card de dentista cooperado
Foto recortada em círculo, nome em `heading-3`, especialidades em `caption`, CTA "Agendar".

### `beneficio` — Card de benefício/feature
Ícone grande em círculo colorido (paleta complementar), título `heading-3`, descrição `body-md`.

## Regras

- Raio `lg` (16px) padrão. `xl` apenas em cards hero.
- Shadow `sm` em estado default; `md` em hover quando clicável.
- Padding interno mínimo: 24px (`spacing.6`).
- Em fundos escuros, usar `surface.brand` com texto `onBrand`.

## API

```tsx
<Card variant="plano" tone="roxo">
  <Card.Header>...</Card.Header>
  <Card.Body>...</Card.Body>
  <Card.Footer>...</Card.Footer>
</Card>
```
