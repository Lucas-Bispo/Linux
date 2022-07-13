# Linux

<div align="center">
    <img alt="Tudo sobre permissões avançadas e ACL no Linux" src="">
  </div>
  
  <br>
  
  <div align="center">
    <img alt="Discover" src="">
    <div>
      <h1>Tudo sobre permissões avançadas e ACL no Linux</h1>
      <span>🚀 Sistema Operacional 🚀</span>
    </div>
  </div>
  
  ## 📚 Sobre
  
  Vamos realizar o estudo de permissões para máquina Linux 
  
  ### 🕹️ Possui as seguintes funcionalidades:
  
  Linux Permissães 
  
  - L - Ler aquivos .
  - W - Write.
  - X - eXecutar.

  Quem tem permissões

  - Usuários.
  - Grupo.
  - Outros.
    
    <img alt="Discover" src="https://user-images.githubusercontent.com/60610011/177796932-7c609928-4b63-4659-a877-ebb1282bc1cd.png">

  - chmod - Altera os níveis de permissoes.
  - Sintaxe - chmod [opções] [permissões] [diretorio/arquivo]
  - Opções -> -v mostra todos os arquivos que estão sendo processados
           -> -f Não mostra a maior parte das mensagens de erro
           -> -c Exibe somente os arquivos que tiveram as permissões alteradas. 


    <img alt="Discover" src="https://user-images.githubusercontent.com/60610011/178329803-4eded389-e914-4b2a-af08-f99f66941bca.jpeg">
  
  ### 📝 Gerenciamento de pacotes
  
  O GERENCIADOR DE PACOTES DPKG

  O dpkg foi criado para instalar pacotes (.deb) na distribuição Debian. O dpkg é o mais popular, sendo utilizado por outras distribuições, como Ubuntu, KNOPPIX, etc., para instalar pacotes.
  <img alt="Discover" src="https://user-images.githubusercontent.com/60610011/178741056-e03809b1-a037-4ca9-bc67-a29e60a30352.png">
  


  Exemplos:

  1. Instala o pacote:

  # dpkg -i pacote.deb

  Desinstala o pacote, mas mantêm os seus arquivos de configuração:

  # dpkg -r pacote

  Desinstala o pacote, inclusive os seus arquivos de configuração:

  # dpkg -P pacote

  Exibe informações do pacote não instalado:

  # dpkg -I pacote.deb

  DPKG-RECONFIGURE
  Reconfigura pacotes ".deb" após terem sido instalados utilizando o debconf (sistema de configuração de pacotes ".deb"). Esse comando fará perguntas para reconfigurar o pacote.

  Sintaxe: dpkg-reconfigure opções nome_pacote
  Opções:
  -a ou --all :: reconfigura todos os pacotes
  -h ou --help :: exibe ajuda

  Exemplo:

  Reconfigura o pacote ssh:

  # dpkg-reconfigure ssh

  ALIEN
  Converte entre formatos de pacotes ".rpm", ".deb", ".tgz" (só Slackware) e ".slp".

  Este comando deve ser utilizado com muito cuidado, pois nem todos os pacotes podem ser convertidos do seu formato original para outro.

  Sintaxe: alien opções nome_pacote
  Opções:
  --to-tgz ou -t :: converte o pacote para o formato ".tgz".
  --to-rpm ou -r :: converte o pacote para o formato".rpm".
  --to-deb ou -d :: converte o pacote para o formato".deb".

  Exemplo:

  Converte um pacote RPM para DEB:

  # alien -d nome_pacote.rpm

  ### 🏗️ Desenvolvimento
  
  
  
  ## 🔎 Demonstração
  
  <img alt="Application demo GIF" src=".github/Coffe.gif">
  
  ## 💻 Como acessar
  
 ## A aplicação está hospedada na  e pode ser acessada [aqui](https://rocket-coffee-gray.vercel.app).##
  
  ## 🛠️ Tecnologias utilizadas
  
  <h3 align="center">🖥️ Front-End</h3>
  
  <table align="center">
    <tbody>  
    </tbody>
  </table>
  
  
  
  
  ## 🚀 Desenvolvido em
  
  27 de Jun. de 2022
  
  <p align="center">✨ Feito com muito foco por <a href="https://github.com/Lucas-Bispo"><strong>Lucas Bispo</strong></a> ✨</p>
