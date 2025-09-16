# Comandos Git – Cola rápida

```bash
# 1) Configuração inicial (uma vez no computador)
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@example.com"

# 2) Iniciar repositório local
git init
git branch -M main

# 3) Ver status e preparar arquivos
git status
git add .

# 4) Primeiro commit
git commit -m "primeiro commit: estrutura do portfólio"

# 5) Conectar ao repositório remoto (substitua pela sua URL)
git remote add origin https://github.com/SEU_USUARIO/NOME_DO_REPO.git

# 6) Enviar para o GitHub
git push -u origin main

# Depois, para novos envios:
git add .
git commit -m "mensagem curta e clara"
git push
```

> Se o Git pedir **usuário/senha** no push via HTTPS:
> - Usuário: seu login do GitHub
> - Senha: **Personal Access Token (PAT)** – crie em: GitHub > Settings > Developer settings > Personal access tokens.