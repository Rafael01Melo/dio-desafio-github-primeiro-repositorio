# Informações de alguns comandos do Git/GitHub da Dio.me
Repositório criado para o Desafio de projeto

##Git 
### Estados
 - Modificado (modifed);
 - Preparado (staged/index);
 - Consolidado (comitted);

### Geral
git help

## Configurações
Setar usuário -> git config --global user.name "Rafael Soares"

Setar email -> git config --global user.email rafa_psa@hotmail.com

## Repositório Local

**bold text** Criar novo repositório
- git init
**bold text** Verificar estado dos arquivos/ diretorio
- git status
**bold text** Adicionar arquivo/diretório (staged area)
Adicionando arquivo específico -> git add meu_arquivo.txt
Adicionando todos os arquivos -> git add .

## Comitar arquivos/Diretórios

Comitar um arquivo -> git commit -m "comentário sobre o commit"

## Enviar arquivos/diretórios para o repositório remoto
O primeiro push de um repositório deve conter o nome do repositório remoto blanch.
- git push -u origin master

Os demais pushes não precisam dessa informação
git push

Atualizar os arquivos no branch atual
git pull

### Clonar um repositório remoto já existente

git clone colar o endereço da HTTPS ou SSH exemplo https://github.com/Rafael01Melo/dio-desafio-github-primeiro-repositorio.git


## Links úteis
[Sintaxe.Basica.Makdow](https://www.markdownguide.org/cheat-sheet/)
