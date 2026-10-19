---
id: badge
name: Badge
status: stable
version: 1.0.0
category: display
tokens:
  - colors.complementary
  - spacing.radius.full
  - typography.scale.caption
---

# Badge

Rótulo curto para status, categorias ou destaque de dados.

## Variantes

| Tom        | Fundo                    | Texto     | Uso                          |
| ---------- | ------------------------ | --------- | ---------------------------- |
| neutral    | `surface.muted`          | vinho     | Categoria, tag genérica      |
| brand      | `vinhoEscuro`            | branco    | Institucional                |
| success    | `feedback.success` 12%   | success   | Plano ativo, pagamento ok    |
| warning    | `feedback.warning` 12%   | warning   | Pendência                    |
| roxo       | `roxo` 30%               | vinhoUltra| Singulares                   |
| goiaba     | `goiaba` 30%             | vinhoUltra| Novidade, campanha           |
| lima       | `lima` 40%               | vinhoUltra| Prevenção, saúde             |
| ciano      | `ciano` 35%              | vinhoUltra| Conteúdo, informativo        |

## Regras

- Raio `full` (pill). Altura 24px (sm) ou 28px (md).
- Texto em `caption` com Title Case — nunca CAIXA ALTA.
- Ícone opcional à esquerda, 14px.

## API

```tsx
<Badge tone="roxo" size="sm">Singular</Badge>
```
