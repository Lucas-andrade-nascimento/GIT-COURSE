# Notas uteis para o curso

git clone 'link' - clona o repositorio pro seu pc 

git init - inicia um repositorio git na pasta local

git status - mostra algumas infos sobre o repositorio 

git diff - mostra no terminal o que foi altereado, retirado ou colocado. Depois de comitado 

git diff --staged - mostra essas mudanças nos arquivos ja staged

git add - manda os arquivo pro stage 

git commit -m "mensage" - comita o que vou para stage

git log - mostra o historico de commits com os nomes dos autores e os hashcodes

q - sai do gitbash no cli

git restore 'nome do arquivo' - recupera uma modificação feita, remove as alterações

git restore --staged 'nome do arquivo' - faz o mesmo, com um arquivo em stage

git remote - mostra as branch do repo remoto

git push -u origin 'nome da branch' - sobe o commit para o repositorio remoto 

git pull - puxa o estado atual do repo remoto e faz um merge com o seu local, caso vc nao faça nada 

git fetch  - puxa o estado atual do repo remoto mas nao faz o merge permitindo que use o:

git diff orgin/'branch' - mostra a diferença entre o estado do repo remoto pro seu. Dando para analisar se voce quer fazer o pull

git branch 'name' - cria uma branch no repositorio local 

git log --oneline --decorate - mostra a branch que nos estamos

git checkout 'name' - leva para a branch q queremos ir

git merge 'name brach' - une as branches trazendo a branch que vc quer para a branch que voce esta