# 🤝 Guia de Contribuição

Obrigado por considerar contribuir para **SQL: Do Zero ao Avançado**! Este documento fornece diretrizes e instruções para contribuir com o projeto.

---

## 📋 Código de Conduta

Todos os contribuidores devem seguir princípios éticos e respeitosos. Qualquer comportamento discriminatório, abusivo ou prejudicial resultará em exclusão imediata do projeto.

---

## 🎯 Como Contribuir

### 1. **Reportar Bugs**

Encontrou um problema? Abra uma **Issue** com:
- **Título claro:** Descreva o problema em uma frase
- **Descrição detalhada:** O que aconteceu, quando, em qual navegador/device
- **Steps to reproduce:** Passos exatos para reproduzir o bug
- **Expected vs Actual:** O que deveria acontecer vs o que realmente acontece
- **Screenshots/GIFs:** Se relevante, adicione capturas visuais

### 2. **Sugerir Melhorias**

Tem uma ideia? Abra uma **Issue** com:
- **Label:** `enhancement` ou `feature-request`
- **Descrição:** O que você gostaria de adicionar e por quê
- **Contexto:** Como isso beneficia os usuários
- **Exemplos:** Links, screenshots ou mockups

### 3. **Pull Requests**

Pronto para contribuir código? Siga este fluxo:

#### Passo 1: Fork e Clone
```bash
# Fork o repositório no GitHub
# Clone seu fork
git clone https://github.com/seu-usuario/sql-course-website.git
cd sql-course-website

# Adicione o upstream original
git remote add upstream https://github.com/Thiagoflima2503-fonte/sql-course-website.git
```

#### Passo 2: Crie uma Branch
```bash
# Sempre trabalhe em uma branch separada
git checkout -b feature/sua-feature
# ou
git checkout -b fix/seu-bug
# ou
git checkout -b docs/sua-documentacao
```

#### Passo 3: Faça suas Mudanças
- Edite os arquivos necessários
- Mantenha o código limpo e bem comentado
- Siga o estilo de código existente
- Teste em múltiplos navegadores e devices

#### Passo 4: Commit com Mensagem Clara
```bash
# Mensagens descritivas ajudam a entender o histórico
git commit -m "feat: adiciona validação de formulário

- Valida campos obrigatórios
- Mostra mensagens de erro amigáveis
- Melhora UX em mobile"
```

**Guia de prefixos:**
- `feat:` – Nova funcionalidade
- `fix:` – Correção de bug
- `docs:` – Mudanças na documentação
- `style:` – Formatação, sem mudanças lógicas
- `refactor:` – Reorganização do código
- `perf:` – Melhorias de performance
- `test:` – Adição de testes

#### Passo 5: Push e Pull Request
```bash
# Push para seu fork
git push origin feature/sua-feature

# Abra um Pull Request no GitHub
# Descreva suas mudanças, por quê fez, e qualquer contexto importante
```

#### Passo 6: Code Review
- Responda aos comentários do reviewer
- Faça os ajustes solicitados
- Após aprovação, sua contribuição será merged!

---

## 🎨 Padrões de Código

### HTML
- Use tags semânticas (`<section>`, `<article>`, `<nav>`, etc.)
- Sempre inclua `alt` em imagens
- Use IDs com prefixo para evitar conflitos (ex: `sql-hero`, `sql-faq`)

### CSS
- Use variáveis CSS definidas no `:root`
- Prefira classe sobre ID (exceto para âncoras)
- Mobile-first: comece com mobile, depois expanda
- Use flexbox/grid ao invés de float

### JavaScript
- Código limpo e comentado
- Use `const` por padrão, `let` quando necessário
- Evite `var`
- Nomes descritivos para variáveis e funções

---

## 🧪 Teste suas Mudanças

Antes de fazer um Pull Request:

1. **Teste em navegadores:**
   - Chrome (última versão)
   - Firefox (última versão)
   - Safari (se possível)
   - Edge

2. **Teste em devices:**
   - Desktop (1920x1080)
   - Tablet (768x1024)
   - Mobile (375x667)

3. **Performance:**
   - Lighthouse Score deve estar acima de 90
   - Verificar Core Web Vitals
   - Sem console errors/warnings

---

## 📝 Documentação

Se sua mudança afeta a funcionalidade:
- Atualize o `README.md`
- Adicione comentários no código se complexo
- Se é uma nova feature, documente em `ROADMAP.md`

---

## ❓ Dúvidas?

Abra uma **Issue** com a label `question` ou entre em contato com o autor.

---

## 🙏 Agradecimentos

Valorizamos todas as contribuições, por menores que sejam. Obrigado por tornar este projeto melhor!

---

**Made with ❤️ by the SQL Course Community**
