# Git e GitHub

# #1 Introdução ao Git

## 1.1 O que é?
O Git é um Sistema de Controle de Versão (VCS) Distribuído (local) que evita que alterações realizadas em um projeto modifiquem o código-fonte.

## 1.1.1 Versionamento (VCS)
Versionamento possibilita a criação de um histórico resgatável de um software.

↪ Centralizado/Linear ￫ o projeto monitorado é salvo por meio de commit para o repositório central. É necessário ter conexão ativa com o servidor constantemente para dar um commit e ter monitoramento do código.

↪ Distribuído ￫ o projeto é salvo por meio de commit para o repositório local e compartilhado dando um push para o repositório remoto.

## 1.2 Para que serve
O Git registra as mudanças que ocorrem no código-fonte de um projeto. Logo, permite que os arquivos sejam alterados de forma simultânea, por inúmeras pessoas, sem a preocupação que essas alterações sejam sobrescritas umas pelas outras.

## 1.3 Funcionalidade na prática
De forma simplificada, o Git trabalha em uma arquitetura em Branch (ou ramificações). Cada novo commit, ou seja, alteração do código, cria um novo ponto na ramificação atual (uma branch).

## 1.3.1 Exemplo
Exemplificação de um fluxo de contribuição em um projeto utilizando o Git:

1 ￫ Primeiramente deve-se clonar o código-fonte do projeto na máquina, para que os arquivos fiquem disponíveis localmente.

2 ￫ Criar uma Branch, ramificação totalmente independente, que irá possibilitar a alteração dos arquivos do projeto sem interferir as originais.

3 ￫ A criação e alteração dos arquivos serão divididas em commits.
**A descrição dos commits devem ser objetivas, pois ficarão salvas no histórico das alterações.**

4 ￫ Com a funcionalidade totalmente finalizada, a Branch deve ser enviada, com todas as alterações, de volta para o repositório remoto.

5 ￫ A mesclagem das modificações da Branch com os arquivos originais do projeto da Branch principal ou máster, é feita pelo comando Marge. Após isso, é necessário dar um commit e um push, para enviar a ramificação máster mesclada ao repositório remoto.

# #2 Introdução ao GitHub

## 2.1 O que é?
GitHub é uma plataforma de hospedagem de código-fonte e arquivos com controle de versão usando o Git. É como uma plataforma social colaborativa, onde programadores e empresas colocam seus projetos para o desenvolvimento do código.

## 2.2 Para que serve
Por meio dele, é possível acompanhar qualquer alteração e quem a efetuou, além de permitir a restauração do código removido ou modifica

# #3 A evolução do GitHub

## 3.1 Um pouco de história

### ● (1985) Concurrent Version System (CVS)
Um dos softwares de controle de versão mais famosos antigamente.
↪ Centralizado
↪ Open Source
↪ Mais popular
↪ Alguns problemas
● (2000) Apache Subversion (SVN)
É um sistema de controle de versão desenhado especificamente para ser um substituto moderno do CVS.
↪ Centralizado
↪ Open Source
↪ Ativo até hoje
↪ CVS-like
● (2000) BitKeeper
É uma ferramenta de software para controle de revisão distribuída de código-fonte de computador.
↪ Distribuído
↪ Era proprietário
↪ Versão comunidade (maior “cliente” era o Linux)
↪ CVS-free
● (2004) BitKeeper - Problema
↪ SoucePuller ￫ cliente de código aberto para acessar o sistema de controle de versão BitKeeper.
↪ Engenharia reversa
↪ Recursos destravados
● (2005) – BitKeeper
↪ Nova licença
↪ Acesso a metadados
↪ Só na versão comercial
● (2005) Git
↪ Distribuído
↪ Open Source
↪ Feito em 10 dias
↪ Performace

## 3.2 O que quer dizer “Git” segundo Linus Torvalds
↪ Três letras do alfabeto;
↪ Gíria ￫ teimoso, cabeça-dura, pensa que sempre está certo (referindo a si mesmo);
↪ Global information tracker;
↪ Goddamn idiotic truckload of shit.

## 3.3 E o GitHub?
### ● (2008)
↪ Proprietário;
↪ Hospedagem de código;
↪ Baseado em Git;
↪ 2009 ￫ 46k repositórios;
↪ 2010 ￫ 100k users / 1M repositórios;
↪ 2011 ￫ Ultrapassou SourceForge;
↪ 2013 ￫ 3M users / 5M repositórios;
↪ 2016 ￫ 14°ligar na lista da **Forbes**;
↪ 2018 ￫ **Maior ataque de DDoS** da história.
### ● (2018)
↪ **Adquirido pela Microsoft**;
↪ US$7.5 bilhões;
↪ Operação independente;
↪ 2020 ￫ **GitHub compra a npm**.

## 3.4 OctoCat <3
Mascote do GitHub – gato com rosto humanizado e com tentáculos :D