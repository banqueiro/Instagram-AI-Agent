## Riona-AI-Agent 🌸

Riona-AI-Agent é uma ferramenta de automação alimentada por IA, projetada para interagir com várias plataformas de mídia social, como Instagram, Twitter e GitHub. Ela utiliza modelos avançados de IA para gerar conteúdo envolvente, automatizar interações e gerenciar contas de mídia social de forma eficiente.

Antes de usar as funcionalidades de automação, você pode treinar o agente com conteúdo personalizado. Você pode fazer o upload do seu conteúdo por meio de um dos seguintes:

- **URL de vídeo do YouTube** 🎥
- **Arquivo de áudio** 🎙️
- **Portfólio ou link do site** 🌐
- **Formatos de arquivo suportados: PDF, DOC, DOCX, TXT** 📄

## Funcionalidades

- **Automação no Instagram:** Fazer login automaticamente, curtir postagens e deixar comentários reflexivos.
- **Automação no Twitter:** (Em breve) Tuitar, retuitar e curtir tweets automaticamente.
- **Automação no GitHub:** (Em breve) Gerenciar repositórios, issues e pull requests automaticamente.
- **Geração de conteúdo com IA:** Usar o Google Generative AI para gerar comentários e postagens envolventes.
- **Suporte a proxies:** Usar proxies para gerenciar várias contas e evitar limites de taxa.
- **Gerenciamento de cookies:** Salvar e carregar cookies para manter sessões entre reinicializações.

## Instalação

1. **Clone o repositório**:
    ```sh
    git clone https://github.com/david-patrick-chuks/Riona-AI-Agent.git
    cd Riona-AI-Agent
    ```

2. **Instale as dependências**:
    ```sh
    npm install
    ```

3. **Configuração das variáveis de ambiente**:
    Renomeie o arquivo [.env.example](http://_vscodecontentref_/1) para o arquivo [.env](http://_vscodecontentref_/1)  no diretório raiz e adicione suas credenciais e chaves de API (opcional). Consulte o arquivo [.env.example](http://_vscodecontentref_/2) para as variáveis necessárias.
    ```dotenv
    # Instagram credentials
    IGusername=your_instagram_username
    IGpassword=your_instagram_password

    # Twitter credentials
    Xusername=your_twitter_username
    Xpassword=your_twitter_password

    ```

## Uso

1. **Execute o agente**:
    ```sh
    npm start
    ```

<!-- 2. **Execute o agente do Twitter** (Em breve):
    ```sh
    npm run start:twitter
    ```

3. **Execute o agente do GitHub** (Em breve):
    ```sh
    npm run start:github
    ``` -->

## Estrutura do Projeto

- **src/client**: Contém a lógica principal para interagir com plataformas de mídia social.
- **src/config**: Arquivos de configuração, incluindo a configuração do logger.
- **src/utils**: Funções utilitárias para lidar com erros, cookies, etc.
- **src/schema**: Definições de esquemas para conteúdo gerado pela IA.

## Logs

O projeto utiliza um logger personalizado para registrar informações, avisos e erros. Os logs são salvos no diretório [logs](http://_vscodecontentref_/3).

## Tratamento de Erros

Manipuladores de erro a nível de processo são configurados para capturar rejeições de promessas não tratadas, exceções não capturadas e avisos de processo. Os erros são registrados usando o logger personalizado.

## Contribuições

Contribuições são bem-vindas! Por favor, faça um fork do repositório e envie um pull request com suas mudanças.

## Licença

Este projeto é licenciado sob a Licença MIT. Consulte o arquivo LICENSE para mais detalhes.

## Agradecimentos

- [Google Generative AI](https://ai.google/tools/) por fornecer modelos de AI.
- [Puppeteer](https://github.com/puppeteer/puppeteer) para automação do navegador.
- [puppeteer-extra](https://github.com/berstend/puppeteer-extra) para plugins adicionais e melhorias


---
