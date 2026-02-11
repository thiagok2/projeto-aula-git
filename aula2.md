# Configurar github conectando ao nosso projeto local

## 1. Criar conta e novo repositório no github
Uma vez que o repositório foi criado, ele sugere os seguintes comandos:
Copie as linhas que aparecem no **seu** repositório e execute no terminal.
```sh
git remote add origin https://github.com/SEUUSUARIO/SEUPROJETO.git
git branch -M main
git push -u origin main
```

Dando tudo certo, o seu repositório na nuvem(github) vai ter seus arquivos atualizados.

## E dando errado
### Problema 1 - Repositórios com trabalhos desalinhados
Há trabalhos/arquivos/modificações no repositório remoto e não estão localmente.