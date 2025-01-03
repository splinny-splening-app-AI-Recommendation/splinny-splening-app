# Splinny-splening-app Starter

Bem-vindo ao guia de inicialização do Splinny-splening-app! Este documento contém instruções detalhadas para configurar e iniciar o projeto, incluindo o aplicativo mobile e a API.

## Passo a Passo para Iniciar o Projeto

### 1. Instalando as Dependências

Para começar, precisamos instalar todas as dependências necessárias para o projeto funcionar corretamente.

1. **Na pasta raiz do projeto:**
   - Abra o terminal e navegue até a pasta raiz do projeto.
   - Execute o seguinte comando para instalar as dependências principais:
     ```
     npm install
     ```
   - Instale o `expo-cli` globalmente, se ainda não tiver:
     ```
     npm install -g expo-cli
     ```
   - Depois disso, inicie o emulador Android com o seguinte comando:
     ```
     npx expo start
     ```

2. **Na pasta da API:**
   - Navegue até a pasta `api`:
     ```
     cd api
     ```
   - Execute o comando novamente para instalar as dependências específicas da API:
     ```
     npm install
     ```
   - Depois disso, inicie a API utilizando o comando:
     ```
     npm run start
     ```

### 2. Lidando com Possíveis Erros no `tailwind.config.js`

Se durante a configuração do projeto você encontrar um erro relacionado ao arquivo `tailwind.config.js`, siga estas etapas para corrigi-lo:

1. Abra o arquivo `tailwind.config.js` no editor de código.
2. Localize a linha que está causando o erro.
3. Apague a linha com erro e digite-a novamente exatamente como estava.
4. Salve o arquivo e tente novamente.

### 3. Ou se preferir, inicie o projeto com emulador Android e API ao mesmo tempo

Depois de instalar as dependências, você pode iniciar o aplicativo mobile e a API juntos:

1. Certifique-se de estar na pasta raiz do projeto.
2. Execute o comando abaixo para iniciar o Expo e a API simultaneamente:
