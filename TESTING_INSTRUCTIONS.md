# Como Testar a Aplicação SynergyCare

Olá! Para testar o projeto no seu computador, siga estes passos para configurar o ambiente.

### 1. Instale as Dependências

Primeiro, abra um terminal na pasta do projeto e execute o seguinte comando. Isso irá baixar e instalar todos os pacotes que a aplicação precisa para funcionar.

```bash
npm install
```

### 2. Configure suas Credenciais do Firebase

A aplicação precisa se conectar ao Firebase para funcionar.

- No projeto, você encontrará um arquivo chamado `.env.example`. Este é um modelo.
- Crie uma cópia deste arquivo na mesma pasta e renomeie a cópia para `.env`.
- Abra o novo arquivo `.env` com um editor de texto.
- Substitua os valores de exemplo pelas suas credenciais **reais** do seu projeto no Firebase.
- **Importante:** O valor para `VITE_FIREBASE_CONFIG` deve ser o objeto de configuração JSON do seu Firebase, formatado como uma string em uma **única linha**.

### 3. Inicie o Servidor de Desenvolvimento

Após configurar as credenciais, execute o seguinte comando no seu terminal:

```bash
npm run dev
```

### 4. Veja a Aplicação no Navegador

Este último comando iniciará o servidor de desenvolvimento. O terminal exibirá um endereço, que normalmente é `http://localhost:5173`.

Copie e cole este endereço no seu navegador de internet.

A aplicação SynergyCare deve carregar e estar pronta para uso, conectada à sua conta do Firebase. Se você tiver qualquer dúvida durante o processo, pode me perguntar!
