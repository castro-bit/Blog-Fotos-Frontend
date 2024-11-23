IMPORTANTE: Antes de começar, é necessário ter o Node.js instalado em sua máquina. A versão recomendada é a v20.x.x.

Passo 1: Baixe o código do projeto
Opção 1 - Clonando o repositório para o seu GitHub
Para usar essa opção, você precisará do Git instalado. Caso não tenha, ou se preferir, use a opção 2 para baixar o arquivo .zip.

Faça um fork do repositório clicando no botão Fork no canto superior direito da página;
Realize o clone do repositório para sua máquina:
Clique em <> Code e copie o link remoto do repositório;
Abra o terminal e navegue até o diretório onde deseja baixar o projeto, em seguida execute o comando git clone <endereço remoto>;
Você também pode abrir a pasta diretamente no Visual Studio Code clicando em File > Open Folder e selecionando a pasta do projeto.
Opção 2 - Baixando o arquivo .zip
Clique em <> Code e depois em Download ZIP;
O arquivo compactado será baixado na pasta padrão de downloads do seu navegador;
Extraia o conteúdo da pasta ZIP e mova para o diretório de sua escolha.
Passo 2: Instale as dependências do projeto
Opção 1 - Usando o terminal do Visual Studio Code
Abra o Visual Studio Code e carregue o projeto indo até File > Open Folder e selecionando a pasta onde o projeto foi baixado;
Vá até Terminal > New Terminal no menu do VS Code. O terminal será aberto automaticamente na pasta correta;
Execute o comando npm install e aguarde até que a instalação seja concluída.
Opção 2 - Usando outro terminal
Abra o terminal de sua preferência e navegue até o diretório onde o projeto foi baixado com o comando cd <pasta>;
Na raiz da pasta, execute o comando npm install e aguarde a instalação das dependências.
Passo 3: Execute o projeto
Após a instalação, execute o comando npm run dev no terminal (no VS Code ou outro terminal de sua escolha). Você verá uma mensagem indicando que o servidor local foi iniciado:

arduino
Copiar código
> dev
> npx parcel --port 8000 index.html

Server running at http://localhost:8000
✨ Built in xxxms
Agora o projeto estará disponível em http://localhost:8000 e pode ser acessado pelo navegador de sua preferência.
