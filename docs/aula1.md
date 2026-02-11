# Introdução

## O que é git?

O Git é um sistema de controle de versão distribuído, gratuito e de código aberto, utilizado para monitorar alterações no código-fonte durante o desenvolvimento de software. Ele permite gerenciar o histórico de arquivos, reverter mudanças, trabalhar em equipe simultaneamente sem sobrescrever o trabalho alheio e criar ramificações (branches) para desenvolver funcionalidades com segurança.

## Criando um projeto
1. Criar pasta e abrir ela no VSCode. 
Comando para iniciar um projeto no git:

```sh
git init --initial-branch=main
```

1. O que é o --initial-branch=main?
É um parâmetro opcional que informa o git a utilizar a branch inicial sendo a main e não mais a master. O nome master é um nome em desuso. 

2. E o que é branch?
São ramos de trabalhos. Linhas, versões para serem implementadas/desenvolvidas.

## Trabalhando com novos arquivos

1. Crie arquivos, por exemplo:
  a. criar arquivo index.js
  b. criar pasta docs e dentro da pasta criar um arquivo aula1.md, aula2.md

2. Dado que os arquivos foram apenas criados mas ainda não foram rastreados pelo git. Logo, são identificados como não rastreáveis(untracked).
Vamos adicionar eles ao rastreio com o comando.

```sh
git add *
```

3. Uma vez que foram adicionado, estão aptos a serem incluídos em um commit.

*Definição de commit*
Um git commit é um instantâneo (snapshot) das alterações preparadas (na staging area) do seu projeto, funcionando como um registro histórico seguro e permanente. Ele salva o estado atual dos arquivos, com metadados como autor, data e mensagem, permitindo rastrear, reverter ou compartilhar modificações no repositório.

Comando para commitar:
```sh
git commit -m 'mensagem do commmit'
```

