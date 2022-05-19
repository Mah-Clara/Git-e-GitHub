# Git e GitHub

# #1 Introdução ao Git

## 1.1 O que é?
O Git é um Sistema de Controle de Versão (VCS)
Distribuído (local) que evita que alterações realizadas
em um projeto modifiquem o código-fonte.

## 1.1.1 Versionamento (VCS)
Versionamento possibilita a criação de um histórico
resgatável de um software.
```
↪ **Centralizado/Linear** ￫ o projeto monitorado é
salvo por meio de commit para o repositório central.
É necessário ter conexão ativa com o servidor
constantemente para dar um commit e ter
monitoramento do código.
```
```
↪ **Distribuído** ￫ o projeto é salvo por meio de
commit para o repositório local e compartilhado
dando um push para o repositório remoto.
```

## 1.2 Para que serve
O Git registra as mudanças que ocorrem no código-fonte
de um projeto. Logo, permite que os arquivos sejam
alterados de forma simultânea, por inúmeras pessoas,
sem a preocupação que essas alterações sejam
sobrescritas umas pelas outras.

## 1.3 Funcionalidade na prática
De forma simplificada, o Git trabalha em uma
arquitetura em Branch (ou ramificações). Cada novo
commit, ou seja, alteração do código, cria um novo
ponto na ramificação atual (uma branch).

## 1.3.1 Exemplo
Exemplificação de um fluxo de contribuição em um
projeto utilizando o Git:

```
**1 ￫** Primeiramente deve-se clonar o código-fonte
do projeto na máquina, para que os arquivos fiquem
disponíveis localmente.
```
```
**2 ￫** Criar uma Branch, ramificação totalmente
independente, que irá possibilitar a alteração dos
arquivos do projeto sem interferir as originais.
```
```
**3 ￫** A criação e alteração dos arquivos serão
divididas em commits.
**A descrição dos commits devem ser objetivas, pois
ficarão salvas no histórico das alterações.**
```
```
**4 ￫** Com a funcionalidade totalmente finalizada, a
Branch deve ser enviada, com todas as alterações,
de volta para o repositório remoto.
```
```
**5 ￫** A mesclagem das modificações da Branch com
os arquivos originais do projeto da Branch principal
ou máster, é feita pelo comando Marge. Após isso,
é necessário dar um commit e um push, para enviar
a ramificação máster mesclada ao repositório
remoto.
```