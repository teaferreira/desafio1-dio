# Repositório do desafio1-dio
### Desafio de Projeto GIT/GITHUB - Resuminho

Basic Syntax Mark Down: https://www.markdownguide.org/basic-syntax/

### Lembretes:

- Comandos básicos GIT: 

cd = change directory - navega entre as pastas

dir = directory - lista o que há dentro do diretório (uma pasta determinada)
quando usada a flag *"-a"* lista também os arquivos ocultos

mk dir = make directory - cria pastas

del = delete - deleta apenas arquivos dentro de uma pasta

rmdir = remove directory - deleta pastas

cd .. = volta ao diretório anterior

clear = limpa a tela (Ctrl + L)

GIT INIT - inicia um repositório dentro de um diretório (pasta)

- É importante lembrar a sequência de upload ou download de um repositório DE ou PARA GitHub (repositório remoto), assim como o procedimento para atualizar os respectivos repositórios (local/remoto) após modificações. 
  Para download do repositório remoto para a máquina local utiliza-se o comando "git clone" e logo após se insere o link (HTTPS ou SSH - se já tiver configurado a chave SSH) . 
  Após feitas modificações, para "enviar estas modificações de volta ao repositório remoto", primeiro as mesmas precisam ser comitadas através dos comandos "git add" e "git commit". Finalmente, através do comando "git push"​ (git push origin main/master), enviamos as alterações para o repositóio remoto.