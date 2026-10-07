Trocar para a main:

git switch main // troca pra main branch
git pull // puxa as att mais recentes 

Para criar a cópia da branch e já entre nela :
git switch -c nome-da-branch

Para começar a adicionar o arquivos na branch, usamos:
git add . 

Salva tudo, não esquece de dar nome:
git commit -m "Aquela descrição chata do commit"

Envia para nuvem:

git push origin nome-da-branch 

Aí o Pull Request e o Merge são feito normalmente no GitHub mesmo.