## Instale o nvm
Faça o download da versão mais recente do nvm no repositório oficial no GitHub. Você pode encontrar os arquivos de instalação na página de lançamentos: https://github.com/coreybutler/nvm-windows/releases.

Na página de lançamentos, role para baixo até encontrar a seção "Assets". Baixe o arquivo com a extensão .zip correspondente à versão mais recente do nvm.

Após o download, descompacte o arquivo .zip em um diretório de sua escolha.

Navegue até o diretório onde você descompactou o nvm.

Execute o arquivo nvm-setup.exe para iniciar o instalador do nvm.

Siga as instruções do instalador para concluir a instalação do nvm. Certifique-se de selecionar a opção para substituir a versão existente do nvm durante o processo de instalação.

## Comandos nvm
### Para listar todas as versões instaladas e disponíveis:
nvm ls

### Instalar uma versão do Node.js
nvm install xx.xx.x

### Alternar entre versões do Node.js
nvm use xx.xx.x

### Definir uma versão padrão
nvm alias default xx.xx.x

## Iniciando o npm em um projeto
Escolha a versão do nodejs

### Inicie o npm (pode dar enter na sequência que será exibida), ao finalizar será criado um package.json no seu projeto
npm init

### Instale o json-server (será usado o npm install)
npm install json-server

### Ao importar o projeto instale as depedências
npm install