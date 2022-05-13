## Comandos básicos aprendidos no curso de introdução ao git/github

- git init > cria um repositório para trabalhar com o git.
- git config --global user.name "" > declara o nome do user passado entre aspas.
- git config --global user.email "" > declara o email do user passado entre aspas.
- git add arq/pasta/* > coloca arq/pasta/tudo do dir pronto para ser comitado (staged).
- git commit -m "" > comita dir e passa nele a mensagem que foi introduzida entre aspas.
- git remote add origin master/main https://... > adiciona o endereço do servidor remoto para qual será feito upload do repositório.
- git push origin master/main > faz upload do repositório para o servidor informado no comando anterior.
- git pull origin master/main > faz download do repositório informado no endereço.
- git clone https://... > clona repositório do servidor informado para o ambiente de desenvolvimento/tua máquina.

- git status > mostra se há alguma arq/pasta que demande alguma ação para continuar o versionamento.
- git config --list > mostra dados do repositório, como user.name/email.
- git remote -v - mostra o servidor ao qual o repositório está ligado.
- git rm arq/pasta > remove/deleta.


### Extra:

[Link para o guia do markdown](https://www.markdownguide.org/basic-syntax/)
