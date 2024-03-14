- - -
### Exercício Final. 
#### Crie um novo repositório denominado "first-git-go-[nome-sobrenome]". 

##### Navegue até o diretório onde deseja criar o novo repositório
```bash
cd /home/usuario/
```
##### Crie o diretório com o nome especificado
```bash
mkdir first-git-go-Kaike-Vitorino
```
##### Navegue até o novo diretório
```bash
cd first-git-go-Kaike-Vitorino
```
##### Inicialize um novo repositório Git
```bash
git init
```
##### Crie um arquivo README.md
```bash
touch README.md
```

#### Nesse repositório você deve disponibilizar um código em Go de um programa que fornece explicações de comandos Git. Ao rodar, seu programa solicita ao usuário um comando GIT, e apresenta a ele a explicação do comando. Caso o usuário digite um comando inválido seu programa deve tratar o erro. Você tem liberdade para implementar o programa como preferir, porém deve estar atento às 4 (quatro) restrições abaixo:
1. IF's só podem ser utilizados para tratamento de erro. ELSE e SWITCH-CASE são proibidos.
2. Ao menos uma struct deve ser criada.
3. Ao menos um map (HashMap) deve ser implementado.
4. Todas as funções que forem implementadas DEVEM estar associadas a algum
conceito, classe do programa.
#### Bônus (opcional). Implemente o map sem utilizar tipos primitivos da linguagem. Ou seja, nem a chave nem o valor serão strings, inteiros, floats, booleans, etc.
