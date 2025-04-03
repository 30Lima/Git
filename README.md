# Guia de Comandos Git

Este repositório contém um resumo dos comandos mais utilizados no Git para facilitar o versionamento de código.

# 📌 Inicialização do Repositório
````
git init                   # Inicializa um repositório Git vazio
git clone <url>            # Clona um repositório remoto
````
# 🟢 Configuração Inicial
````
git config --global user.name "Seu Nome"        # Define o nome de usuário
git config --global user.email "seu@email.com"  # Define o e-mail de usuário
````
# 📂 Controle de Versão
````
git status                 # Exibe o estado atual do repositório
git add <arquivo>          # Adiciona um arquivo ao staging
git commit -m "Mensagem"   # Realiza um commit
git log                    # Exibe o histórico de commits
````
# 🌐 Trabalho com Branches
````
git branch                 # Lista as branches
git branch <nome-branch>   # Cria uma nova branch
git switch <branch>        # Troca de branch
git merge <branch>         # Mescla uma branch
````
# 🚀 Envio e Atualização Remota
````
git push origin <branch>  # Envia commits para o repositório remoto
git pull origin <branch>  # Baixa alterações do repositório remoto
````
# 🛠️ Resolução de Problemas
````
git reset --hard HEAD     # Desfaz alterações locais
````
# ✍️ Conventional Commits

O padrão Conventional Commits define um formato para mensagens de commit que facilita a leitura e o entendimento das mudanças.

Exemplo de Commit:
````
feat: adiciona nova funcionalidade de login
fix: corrige erro na função de autenticação
chore: atualiza dependências
refactor: melhora a estrutura do código
````
- feat: Adição de nova funcionalidade

- fix: Correção de bug

- chore: Tarefas de manutenção

- refactor: Alterações sem impacto externo

Documentação do Conventional Commits: https://www.conventionalcommits.org/en/v1.0.0/


# 📝 Dicas Úteis

Use git commit -am "Mensagem" para adicionar e commitar em um único comando.

Evite commits grandes e prefira commits pequenos e frequentes.
