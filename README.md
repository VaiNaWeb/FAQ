# Perguntas frequentes

Repositório criado para documentar dúvidas comuns úteis para quem está começando a aprender programação.

## Tópicos:

* [GIT](#git)
* [Javascript](#js)

## GIT
**1. Como criar uma branch?**
- git checkout -b nomedabranch

**2. Como excluir uma branch localmente?**
- git branch -D nome do branch

**3. Como trocar de branch?**
- git checkout nomedabranch

**4. Como renomear uma branch?**
- git branch -m novonome

**5. Como adicionar um remote?**
- git remote add nomeParaLembrarDeQuemÉ linkDoCloneDoRemote

**6. Como remover um remote?**
- git remote rm nomedoremote

**7. Como renomear um remote?**
- git remote rename antigonome novonome

**8. Como fazer um commit?**
- git commit -m "mensagem do commit"

**9. Como renomear um commit?**
- git commit --amend

## JAVASCRIPT
**1. Qual a diferença entre uma variável declarada em Escopo Global e em Escopo Local?**
- Uma variável declarada fora de uma função pode ser acessada por todo o código, pois foi declarada em escopo global, visivél a todos. Já uma variável declarada dentro de uma função, está invisivel para as demais funções.

**2. Quais são os tipos de dados de uma variável Javascript?**
- String: caracter declarado dentro de aspas simples ou aspas duplas;
- Numérico: números;
- Booleano: true (verdadeiro) ou false (falso);
- Array: [];
- Objeto: {};
- null;
- undefined;

**3. O que são Arrays?**
- O objeto Array do JavaScript é um objeto semelhante a listas, um tipo de estrutura de dados que armazena elementos e que podem ser identificado pelo seu índice ou uma chave.

```
var paises = [
  'brasil',
  'italia',
  'egito',
  'noruega'
]
```
[!NOTE]
Arrays iniciam em 0, então para acessar o segundo valor da lista usada no exemplo pode ser usado paises[1], que retornará "italia".