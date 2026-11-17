# Instruções para Publicar no GitHub Pages

Seu portfólio profissional está pronto! Siga estes passos para publicar no GitHub Pages:

## Opção 1: Upload Manual (Sem Git)

### 1. Criar Repositório no GitHub
1. Acesse: https://github.com/new
2. Nome do repositório: `seu-usuario.github.io` (substitua "seu-usuario" pelo seu username do GitHub)
3. Torne público (Public)
4. **NÃO** marque "Initialize this repository with a README"
5. Clique em "Create repository"

### 2. Fazer Upload dos Arquivos
1. No repositório criado, clique em "uploading an existing file"
2. Arraste todos os arquivos da pasta `Port` para o GitHub:
   - index.html
   - Retrato profissional em camisa preta.png
   - 01 - CAPA.png
   - 02 - CONSOLIDADO.png
   - 06 - TME.png
   - 2 - VISA~O ME^S.png
   - RESUMO.png
   - Pa�gina 3.png
   - CV LUCAS.pdf
3. Clique em "Commit changes"

### 3. Ativar GitHub Pages
1. No GitHub, vá no seu repositório
2. Clique em Settings (Configurações)
3. No menu lateral, clique em Pages
4. Em "Build and deployment", em "Source", selecione "Deploy from a branch"
5. Em "Branch", selecione "main" e pasta "/ (root)"
6. Clique em "Save"

### 4. Aguardar Publicação
- Aguarde 1-2 minutos
- Seu portfólio estará disponível em: `https://SEU-USUARIO.github.io`

---

## Opção 2: Usando Git (Recomendado)

### 1. Instalar Git (se não tiver)
- Baixe em: https://git-scm.com/download/win
- Instale com as opções padrão

### 2. Criar Repositório no GitHub
1. Acesse: https://github.com/new
2. Nome do repositório: `seu-usuario.github.io`
3. Torne público (Public)
4. Clique em "Create repository"

### 3. Preparar os Arquivos
Abra o PowerShell ou Git Bash na pasta `C:\Users\Lucas Franco\OneDrive\Documentos\Port` e execute:

```bash
git init
git add .
git commit -m "Portfólio profissional - Lucas Silva"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/seu-usuario.github.io.git
git push -u origin main
```

**Substitua SEU-USUARIO pelo seu username do GitHub**

### 4. Ativar GitHub Pages
1. No GitHub, vá no seu repositório
2. Clique em Settings (Configurações)
3. No menu lateral, clique em Pages
4. Em "Build and deployment", em "Source", selecione "Deploy from a branch"
5. Em "Branch", selecione "main" e pasta "/ (root)"
6. Clique em "Save"

---

## Seus Arquivos

✅ index.html - Página principal do portfólio
✅ Foto de perfil profissional
✅ 6 Dashboards/Imagens
✅ Currículo em PDF

O portfólio inclui:
- Design profissional com tema escuro (fundo preto, letras brancas)
- Acento em ciano (#00d4ff) para elementos destacados
- Layout responsivo para desktop e mobile
- Link para LinkedIn
- Botão para download do currículo
- Galeria de dashboards organizada
- Totalmente em português
