# 🚀 Como Resolver o Erro 404 no GitHub Pages

## ✅ Passo a Passo Completo

### 1. **Criar Repositório no GitHub**
- Vá para [github.com](https://github.com)
- Clique em "New repository"
- Nome: `iof-timeline` (ou qualquer nome)
- ✅ Marque "Public"
- ✅ Marque "Add a README file"
- Clique "Create repository"

### 2. **Upload dos Arquivos**
- No repositório criado, clique "uploading an existing file"
- Arraste o arquivo `index-github.html`
- **IMPORTANTE:** Renomeie para `index.html` (sem o "-github")
- Adicione mensagem: "Add IOF timeline website"
- Clique "Commit changes"

### 3. **Ativar GitHub Pages**
- Vá em **Settings** (aba do repositório)
- Role até **Pages** (menu lateral esquerdo)
- Em **Source**, selecione "Deploy from a branch"
- Em **Branch**, selecione "main"
- Em **Folder**, deixe "/ (root)"
- Clique **Save**

### 4. **Aguardar Deploy**
- ⏱️ Aguarde 2-5 minutos
- Aparecerá uma mensagem verde com o link
- Link será: `https://seu-usuario.github.io/nome-repositorio/`

## 🔧 Possíveis Problemas e Soluções

### ❌ Erro 404 - Possíveis Causas:

1. **Nome do arquivo errado**
   - ✅ DEVE ser `index.html` (não `index-github.html`)

2. **GitHub Pages não ativado**
   - ✅ Verificar Settings > Pages

3. **Branch errada**
   - ✅ Deve ser "main" (não "master")

4. **Demora para propagar**
   - ✅ Aguardar até 10 minutos

5. **Repositório privado**
   - ✅ Deve ser público

### 🔄 Se ainda não funcionar:

1. **Verificar Actions**
   - Vá em "Actions" (aba do repositório)
   - Veja se há erros no deploy

2. **Forçar novo deploy**
   - Edite qualquer arquivo
   - Faça commit
   - Aguarde novo deploy

3. **Verificar URL**
   - Formato correto: `https://usuario.github.io/repositorio/`
   - Não: `https://github.com/usuario/repositorio/`

## 📋 Checklist Final

- [ ] Repositório é público
- [ ] Arquivo se chama exatamente `index.html`
- [ ] GitHub Pages ativado em Settings > Pages
- [ ] Branch "main" selecionada
- [ ] Aguardou pelo menos 5 minutos
- [ ] URL está no formato correto

## 🆘 Se Continuar com Erro 404

Me envie:
1. Link do seu repositório GitHub
2. Link que está tentando acessar
3. Screenshot da página Settings > Pages

Vou te ajudar a resolver!

