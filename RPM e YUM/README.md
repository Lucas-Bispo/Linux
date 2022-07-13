# Linux

# Gerenciamento de Pacotes


Comando rpm
O gerenciador de pacotes rpm(man rpm) opera apenas sobre pacotes com extensão .rpm. Caso necessite de bibliotecas e dependências, estes deverão ser instalados manualmente.

Principais opções:

-h, –hash: Exibe um indicador de progresso para a instalação do pacote.
-v: Modo detalhado.
-i, –install: Instala um pacote .rpm.
-U, –update: Instala ou atualiza um pacote .rpm.
-q, –query: Lista informações sobre um pacote.
Opções que acompanham a opção -q:
-a, –all: Lista todos os pacotes instalados no sistema.
-i, –info: Exibe informações sobre um pacote instalado.
-d, –docfiles: Exibe documentos e páginas de manuais de um pacote instalado.
-f, –file: Determina qual pacote instalou o arquivo.
-l, –list: Lista os arquivos instalados por determinado pacote.
-R, –requires: Exibe as dependências do pacote.
–whatrequires: Exibe quais são os programas dependentes do pacote.
-p: Realiza consultas diretamente no arquivo .rpm.
-e, –erase: Remove o pacote.
Acompanhe alguns exemplos a seguir:

<img alt="Discover" src="https://user-images.githubusercontent.com/60610011/178755606-eae0677c-b11c-47c8-8960-4199dd995696.png">

<img alt="Discover" src="hhttps://user-images.githubusercontent.com/60610011/178756085-9c586d33-49a9-4771-b381-587556fceb71.png">
