git --version                                                       [verificar a versão do git instalado na maquina]

git init                                                            [inicia um repositorio git vaziu]

git add "nome do arquivo" git add .                                 [manda os arquivos para area de stating]

git commit -m "primeiro commit"                                     [faz o primeiro commit no repositorio]

git branch -M "main"                                                [muda o nome da branch principal de master para main] 

git remote add origin https://github.com/kovalski96/ProjetoGit.git  [faz conexão entre repositório local e o repositorio do github que estou dando o nome de origin]

clear                                                               [limpa o prompt]

git commit -m "nome do commit"                                      [cria o commit com os arquivos atualizados]

git push origin main                                                [envia os commits para o github]



------"branch" é uma ramificação do projeto master/main é a branch principal

git checkout -b "novo-botao"                                        [cria a nova branch e já vai para esta nova branch]

realiza as alterações dentro desta branch que você deseja > salva > git add > git commit -m nome-do-commit (este commit é apenas dentro desta branch secundaria)


git checkout main                                                   [navega entre as branch]