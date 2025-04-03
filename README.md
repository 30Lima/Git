Guia de Comandos Git

Este repositório contém um resumo dos comandos mais utilizados no Git para facilitar o versionamento de código.

📌 Inicialização do Repositório

git init            # Inicializa um repositório Git vazio
git clone <url>     # Clona um repositório remoto

🟢 Configuração Inicial

git config --global user.name "Seu Nome"       # Define o nome de usuário
git config --global user.email "seu@email.com" # Define o e-mail de usuário

📂 Controle de Versão

git status         # Exibe o estado atual do repositório
git add <arquivo>  # Adiciona um arquivo ao staging
git commit -m "Mensagem" # Realiza um commit
git log            # Exibe o histórico de commits

🌐 Trabalho com Branches

git branch                # Lista as branches
git branch <nome-branch>  # Cria uma nova branch
git checkout <branch>     # Troca de branch
git merge <branch>        # Mescla uma branch

🚀 Envio e Atualização Remota

git push origin <branch>  # Envia commits para o repositório remoto
git pull origin <branch>  # Baixa alterações do repositório remoto

🛠️ Resolução de Problemas

git reset --hard HEAD     # Desfaz alterações locais

📝 Dicas Úteis

Use git commit -am "Mensagem" para adicionar e commitar em um único comando.

Evite commits grandes e prefira commits pequenos e frequentes.
