# Criando um repositório

#### Vamos colocar em prática os seus conhecimentos sobre o Git. Para isso, crie um novo diretório em seu computador e realize algumas modificações nele. Observe:

- Crie uma pasta em seu computador;
- Acesse a pasta que você acabou de criar;
- Inicie o versionamento por meio do comando ```git init```;
- Abra a pasta no ```VS Code``` por meio do comando code .;
- Crie um arquivo chamado ```README.md```;
- Adicione o arquivo novo em staging e realize um commit, como em ``` git add . e git commit -m "Descreva a alteração realizada"```;
- Crie uma nova branch por meio do comando ```git checkout -b, como em git checkout -b adiciona-readme```;
- Faça uma alteração em ```README.md``` e, depois, realize um novo commit, como em ```git add . e git commit -m "Alterando o README"```;
- Retorne para a branch main e, em seguida, realize o merge das alterações por meio do comando ```git merge nome-da-branch```, como em ```git merge adiciona-readme```.