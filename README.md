# Aula prática com Git e Github

## Configurando o Git 

 git config --global user.name "Vitória537"
 git config --global user.email "vivellozo78@gmail.com"

 ## Validando as configurações 

 git config --list

 ## Inicializando repositório

 git init

 ## Verificar arquivos 

 git status

 ## Commit

 git add . ou <nomeDoArquivo>
 git commit -m "Primeiro commit"
 
## Definir a ramificação

git branch -M main

## Conectar ao repositório do Github (somente na 1ª vez)

git remote add origin {cole o link do repositório}

## Enviar para o Github

git push -u origin main (apenas no 1º envio)
git push (para os demais envios )

## Atualizar do Github

git pull  