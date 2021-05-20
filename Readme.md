# Projeto para entender como as branches funcionam 
 
## Branch master ou main 
 
É a branch principal do repositório, é a partir dela que nosso sistema será entregue aos clientes.
 
O "git" usa o nome da branch como master, o "github" como main
 
Para converter use "gir branch -M main" depois que fizer o primeiro commit a partir do repositório criado com o "git init"
 
# manipulação de branches
para listar use
```
$ git branch --list
```
 
para excluir uma branch
```
$ git branch -d nome_da_branch
```
 
Para alterar o nome_da_branch
``` 
$ git branch -m nome_da_branch
```