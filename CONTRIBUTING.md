# Guia de Contribuição

Obrigado por querer contribuir com este projeto! 🙌

## Como contribuir

### 1. Fork e clone

```bash
# Faça um fork pelo GitHub e clone o seu fork
git clone https://github.com/seu-usuario/data-portfolio-template.git
cd data-portfolio-template
```

### 2. Crie uma branch para sua alteração

```bash
git checkout -b feat/nome-da-feature
# ou
git checkout -b fix/descricao-do-bug
```

Use a convenção:
- `feat/` — nova funcionalidade
- `fix/` — correção de bug
- `docs/` — alteração somente em documentação
- `style/` — ajuste visual sem mudar lógica
- `refactor/` — refatoração de código

### 3. Faça as alterações

- Mantenha o projeto como **single-file HTML** (tudo em `index.html`)
- Teste em **desktop e mobile** antes de abrir o PR
- Garanta que os slides de desktop e mobile estejam **sincronizados** em conteúdo

### 4. Commit e push

```bash
git add .
git commit -m "feat: adiciona suporte a tema escuro nativo"
git push origin feat/nome-da-feature
```

### 5. Abra um Pull Request

- Descreva o que foi feito e por quê
- Adicione prints ou GIFs se a mudança for visual
- Referencie issues relacionadas com `Closes #N`

---

## Convenções de código

- **CSS**: use variáveis CSS (`var(--nome)`) para qualquer cor reutilizável
- **JS**: sem frameworks — apenas vanilla JS
- **HTML**: mantenha os comentários de seção (`<!-- CAPA -->`, `<!-- MOBILE -->`, etc.)
- **Sem build step**: o projeto deve funcionar abrindo diretamente o `index.html`

---

## Reportando bugs

Abra uma [issue](../../issues/new) com:
1. Descrição do problema
2. Browser e versão
3. Desktop ou mobile
4. Print ou vídeo (se possível)

---

## Sugestões de melhorias

Ideias que adoraríamos ver implementadas:

- [ ] Tema escuro nativo via `prefers-color-scheme`
- [ ] Slide template para projetos de Machine Learning
- [ ] Animações de entrada com Intersection Observer
- [ ] Gerador de PDF do portfólio via `window.print()`
- [ ] Suporte a múltiplos idiomas (i18n)
- [ ] Modo de edição inline (clique para editar texto)

---

## Código de Conduta

Seja respeitoso, construtivo e inclusivo. Contribuições de todos os níveis de experiência são bem-vindas.
