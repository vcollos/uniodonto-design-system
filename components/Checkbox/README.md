---
id: checkbox
name: Checkbox
version: 1.0.0
radixPrimitive: Checkbox
shadcnBase: checkbox
---

# Checkbox

Caixa de seleção booleana ou múltipla.

## Regras

- 20x20px (md). Raio `sm` (6px).
- Não marcado: borda `border.default`, fundo branco.
- Marcado: fundo `vinhoEscuro`, check branco.
- Foco: ring roxo (`shadow.focus`).
- Sempre acompanhado de label clicável.

```tsx
<Checkbox id="termos" /> <label htmlFor="termos">Li e aceito os termos</label>
```
