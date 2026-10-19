---
id: input
name: Input
status: stable
version: 1.0.0
category: form
radixPrimitive: null
shadcnBase: input
tokens:
  - colors.institutional.vinhoEscuro
  - colors.semantic.border.default
  - colors.semantic.feedback.danger
  - spacing.radius.md
a11y:
  - "Sempre usar <label> associado via htmlFor."
  - "Mensagens de erro usam aria-describedby."
  - "Estado inválido usa aria-invalid=true."
---

# Input

Campo de entrada de texto. Foco em clareza e simplicidade — o beneficiário deve preencher sem fricção.

## Anatomia

`[label]` → `[campo com placeholder]` → `[helper ou erro]`

## Regras

- Label sempre visível (nunca só placeholder).
- Placeholder em tom `text.muted`, frase orientando formato ("Ex.: 000.000.000-00").
- Borda padrão 1px `border.default`; no foco, borda vinho + shadow.focus roxo.
- Erro: borda `feedback.danger` + ícone + mensagem abaixo.

## Tamanhos

| Size | Altura | Fonte |
| ---- | ------ | ----- |
| sm   | 36px   | 14px  |
| md   | 44px   | 16px  |
| lg   | 52px   | 18px  |

## Estados

`default` · `hover` · `focus` · `filled` · `invalid` · `disabled` · `readonly`.

## API

```tsx
<Field label="CPF" error={errors.cpf} hint="Apenas números">
  <Input name="cpf" placeholder="000.000.000-00" />
</Field>
```

## Não faça

- ❌ Usar só placeholder como rótulo.
- ❌ Mensagem de erro genérica ("Campo inválido") — seja específico.
