Testando o git através do terminal.

Lista de comandos importantes:

    Básicos

- git init: inicia um repositório dentro do caminho especificado
- git add file: adiciona um arquivo para ser monitorado (tracked)
- git commit -m "mensagem": cria um commit (um ponto na linha do tempo)
- git status: mostra o status atual, se há arquivos modificados ou untracked (não monitorado)
- git log: mostra um log com todos os commits realizados
- git show: mostra o último commit
- git show "código_do_commit": mostra um commit específico

    Branches

- git branch: mostra a lista de branches
- git branch "nome_da_branch": cria uma nova branch (nova ramificação do projeto, sem alterar o master)
- git checkout master: vai pra branch master
- git checkout "nome_da_branch": vai para a branch especificada
- git merge "nome_da_branch": incorpora a branch no master
- git branch -D "nome_da_branch": deleta a branch especificada

    Repositórios remotos:

-