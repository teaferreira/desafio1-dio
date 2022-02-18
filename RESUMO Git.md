# RESUMO

### Desafio de Projeto GIT/GITHUB - Resuminho

Basic Syntax Mark Down: https://www.markdownguide.org/basic-syntax/

### Lembretes:

- Comandos básicos GIT: 

  WINDOWS    **/**     LINUX

cd = change directory - navega entre as pastas     **/**          =

dir = directory - lista o que há dentro do diretório (uma pasta determinada)       **/**         ls
*quando usada a flag "-a" lista também os arquivos ocultos*

mk dir = make directory - cria pastas          **/**          =

del = delete - deleta apenas arquivos dentro de uma pasta             **/**            rm

rmdir = remove directory - deleta pastas

cd .. = volta ao diretório anterior             **/**            =

cls = limpa a tela              **/**              Clear (Ctrl + L)

- ​
  GIT INIT - inicia um repositório dentro de um diretório (pasta)

  GIT CLONE - faz "download" de um repositório remoto para a máquina local

  GIT STATUS -  mostra o status da branch em que você está trabalhando

  GIT ADD - Move arquivos antes "em edição" para status "staged" 

  GIT COMMIT - Comita mudanças e permite que as mesmas sejam acrescentadas ao repositório remoto através do comando "GIT PUSH"

  GIT PULL -  Puxa alterações do repositório remoto (usado também no caso de conflitos)

  ​

- É importante lembrar a sequência de upload ou download de um repositório DE ou PARA GitHub (repositório remoto), assim como o procedimento para atualizar os respectivos repositórios (local/remoto) após modificações. 
  Para download do repositório remoto para a máquina local utiliza-se o comando "git clone" e logo após se insere o link (HTTPS ou SSH - se já tiver configurado a chave SSH) . 
  ​Após feitas modificações, para "enviar estas modificações de volta ao repositório remoto", primeiro as mesmas precisam ser comitadas através dos comandos "git add" e "git commit". Finalmente, através do comando "git push" (git push origin main/master), enviamos as alterações para o repositóio remoto.