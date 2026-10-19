---
id: button
name: Button
status: stable
version: 1.0.0
category: action
radixPrimitive: null
shadcnBase: button
tokens:
  - colors.institutional.vinhoEscuro
  - colors.complementary.goiaba
  - colors.semantic.text
  - spacing.radius.md
  - spacing.shadow.sm
  - typography.scale.body-md
a11y:
  - "Deve ter contraste mínimo AA contra fundo."
  - "Estado :focus-visible obrigatório com shadow.focus (roxo)."
  - "Área mínima de clique: 44x44px."
---

# Button

Botão de ação. Expressa o tom acolhedor e alegre da Uniodonto com cantos suaves e estados claros.

## Regras

- **Primário**: Vinho-Escuro. Um por tela. Usar para ação principal (contratar, confirmar, entrar).
- **Secundário**: Outline vinho. Ações alternativas.
- **Terciário**: Ghost, sem borda. Ações de baixa ênfase (cancelar, voltar).
- **Destaque (accent)**: Goiaba. Usar apenas em contextos não-institucionais (campanhas, landing alegre).
- Nunca usar dois primários adjacentes.
- Texto em Title Case — nunca MAIÚSCULAS (viola o tom de voz).

## Variantes

| Variante   | Uso                              | Token de fundo                       |
| ---------- | -------------------------------- | ------------------------------------ |
| primary    | CTA principal                    | `colors.institutional.vinhoEscuro`   |
| secondary  | CTA alternativo                  | transparente + borda vinho           |
| tertiary   | Baixa ênfase                     | transparente                         |
| accent     | Não-institucional/campanha       | `colors.complementary.goiaba`        |
| danger     | Ações destrutivas                | `colors.semantic.feedback.danger`    |

## Tamanhos

| Size | Altura | Padding X | Fonte |
| ---- | ------ | --------- | ----- |
| sm   | 36px   | 12px      | 14px  |
| md   | 44px   | 20px      | 16px  |
| lg   | 52px   | 28px      | 18px  |

## Estados

`default` · `hover` (escurece 8%) · `active` (escurece 14%) · `focus-visible` (ring roxo) · `disabled` (40% opacity, cursor not-allowed) · `loading` (spinner substitui ícone).

## API (React + shadcn/radix)

```tsx
<Button variant="primary" size="md" loading={false} leftIcon={<Icon/>}>
  Contratar plano
</Button>
```

## Não faça

- ❌ Botão primário com cor goiaba em material institucional.
- ❌ Texto em CAIXA ALTA.
- ❌ Raio pill (`full`) em botão retangular padrão — reservado para chips.
