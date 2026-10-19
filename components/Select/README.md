---
id: select
name: Select
status: stable
version: 1.0.0
category: form
radixPrimitive: Select
shadcnBase: select
---

# Select

Dropdown de seleção. Usa Radix UI Select por acessibilidade.

## Regras

- Trigger idêntico ao Input (mesma altura, raio, borda).
- Chevron 16px à direita em `text.muted`.
- Conteúdo do popover: raio `md`, shadow `md`, padding 4px.
- Item selecionado: check à esquerda + fundo `brandSoft`.
- Item em hover: fundo `surface.muted`.

## API

```tsx
<Select value={v} onValueChange={setV}>
  <Select.Trigger><Select.Value placeholder="Escolha" /></Select.Trigger>
  <Select.Content>
    <Select.Item value="basico">Plano Básico</Select.Item>
    <Select.Item value="premium">Plano Premium</Select.Item>
  </Select.Content>
</Select>
```
