
<img src="https://secure.webtoolhub.com/static/resources/icons/set2/acc5b045385d5.png" width="150px">

<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black">

# LINUX
_**Comandos do LINUX, aprendidos na aula GSO II com Professor Wellington**_

## COMANDOS DE DIRETÓRIOS/ARQUIVOS
- ```pwd``` : Mostra o diretório atual
- ```ls``` : Lista arquivos/pastas do diretório atual.
  - -a: mostra arquivos e pastas ocultas.
  - -l: mostra detalhes (formato longo) dos arquivos e pastas.
  - -la: combina as duas opções anteriores.
  - -s: exibe tamanho dos arquivos.
- ```cd``` : Entra em um diretório.
  - ```cd ..``` : Volta para diretório anterior.
  - ```cd ~``` : Vai para o diretório ```home```.
  -  ```cd /``` : Vai para o diretório *raiz* do Linux.
  -  ```cd -``` : Para voltar para o último diretório visitado.
- ```cp``` : Copia arquivo.
- ```mv``` : Move arquivos e diretórios, também renomeia arquivos.
- ```rmdir ou rm``` : Remove arquivo e diretórios.
- ```mkdir``` : Cria diretórios.
- ```cat``` : Concatena (junta/mostra) arquivos [**exemplo os .txt**]
- ```touch``` : Cria arquivos vazios
- ```nano``` : Editor de texto no proprio terminal

## COMANDOS DE ADMINISTRAÇÃO DE USUÁRIOS
- ```adduser``` : Adiciona um usuário ou grupo no sistema. Por padrão quando um novo usuário é adicionado, é criado um grupo com o mesmo nome do usuário.
- ```userdel``` : Remove usuários.
  - ```userdel -r donald``` : Remove o usuário, inclusive seus arquivos e diretórios.
- ```groupadd``` : Adiciona um grupo ao sistema.
- ```addgroup``` : Adiciona um usuário a um grupo.
- ```whoami``` : Ver usuário atual.
- ```login``` : Entra com outro usuário.
- ```logout``` : Sai do usuário.

## COMANDOS DE INSTALAÇÃO DE PROGRAMAS
- ```apt-get update``` : Baixa a lista dos pacotes disponíveis.
- ```apt-get upgrade``` :  Atualiza todos os pacotes do sistema.
- ```apt-get install``` : Instala um programa.
- ```apt-get remove``` : Desinstala um programa.
