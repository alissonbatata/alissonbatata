- 👋 Opa prazer! Alisson Xavier.
Obrigado por testar meu bot :)

### Projeto Batata
Uma bot em português feita para PC, originalmente para o WhatsApp, possui mais de 500 comandos e continua em crescimento e melhorias frequentes.

### Usar apenas no Telefone
No celular é dificílimo que você consiga usar, portanto, use o site [Goorm](https://ide.goorm.io) para criar sua BOT pelo telefone, mas saiba que ele irá te desconectar frequentemente, se você possui PC, é muito melhor usa-lo do que usar o Goorm.

### Pedido Pessoal
Por favor NÃO REMOVA os créditos, levei muito tempo e precisei ter muita dedicação pra se criar uma BOT Brasileira assim, agradeço pela cooperação.
```bash
> wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
> sudo apt install ./google-chrome-stable_current_amd64.deb
```

### Para os donos
Você pode rodar comandos de Windows como "ipconfig", comandos de linux como "apt", ou comandos de programações como python -c tudo pelo WhatsApp, ninguém além de você pode usar isso, se você deseja que usem, remova a linha if (!isOnwer) [aqui](https://github.com/KillovSky/iris/blob/main/config.js#L3144), mas saiba que removê-la pode ser perigoso a você.

### Funções (+200)

| Função |Contém|
| ------------- | ------------- |
| Administrar Grupos |✅|
| Anti Porno/Link de Chat |✅|
| Ataques SMS/CALL/EMAIL |✅|
| Bem Vindo/Adeus/Anti-Fake/Blacklist |✅|
| Bloquear/Desbloquear pessoas |✅|
| Buscar Anime/Letra de Música/Twitter/Instagram |✅|
| Mandar mensagens a outros grupos |✅|
| Conversar por texto/voz Sim-Simi/Local (ilimitado) |✅|
| Deletar Mensagens do BOT |✅|
| Downloads (Redes-Sociais e YouTube) |✅|
| Falar 51 idiomas/Tradutor |✅|
| Geração de Textos/Diário |✅|
| Google/Google Play/Pinterest |✅|
| Informações de Grupo/Perfil |✅|
| Marcar todos/Remover Todos |✅|
| Memes/Fazer Memes |✅|
| Nasa, Brainly, Wikipédia |✅|
| Pausar/Sair de Tudo/Transmissão/Apagar Tudo |✅|
| Pesquisa Fotos/Dados/Covid |✅|
| Printar Tela/Sites |✅||
| Sticker de GIF/Sem-Fundo/Link/Palavras |✅|
| Uploads de Fotos |✅|
| Usar CMD/Terminal pelo WhatsApp |✅|
| XP/Ranking/Level/Votações |✅|
| Outras |✅|

### Requisitos

- [NodeJS](https://nodejs.org) - Recomendo a LTS.
- [Git](https://git-scm.com) - Opcional (Se não usar Git Clone).
- [Ffmpeg](https://ffmpeg.org) - Para o comando de GIF.
Se desejar, pode tentar instalar o ffmpeg usando o npm, siga o código abaixo:

```bash
> npm i fluent-ffmpeg -g
```

Para a instalação do git, node e ffmpeg em Linux, use o comando abaixo:

```bash
> sudo apt install nodejs git ffmpeg -y
```

Caso você obtenha erros com a versão do node no repositório de seu Linux, use o [Node Source](https://github.com/nodesource/distributions), lembre-se de usar a LTS (14).

### Instalação
Você precisa ter esse repositório, é simples, rode os comandos abaixo, em caso de erros, rode como sudo/administrador.

```bash
> git clone https://github.com/botbatata/batata.git
> cd iris
> npm i
```

### Iniciar
Para iniciar digite o comando abaixo e espere, após isso, escaneie o QR Code.

```bash
> npm start
```

### Ver todos os comandos
Digite no seu chat a mensagem:

```bash
> /menu
```

### Crie seus comandos
Há uma base simples para suas criações por [aqui](https://github.com/KillovSky/iris/blob/main/config.js#L3661), basta que você remova a "/\*" e a "\*/" para utilizá-la, se precisar de outros tipos, você pode ver sobre eles por [aqui](https://docs.openwa.dev/classes/client.html), se obtiver dificuldades, chame-me por [aqui](https://chat.whatsapp.com/H53MdwhtnRf7TGX1VJ2Jje) ou [aqui](https://wa.me/+5518998044132).

### Mudanças
Edite as API's encontradas em: (Se estiver incorreta avise ou procure)

- [API 1 & 2 - ImgBB](https://github.com/KillovSky/iris/blob/main/lib/config/config.json#5)
- [API 2 - AlphaCoders](https://github.com/KillovSky/iris/blob/main/lib/config/config.json#6)
- [API 3 - API-Flash](https://github.com/KillovSky/iris/blob/main/lib/config/config.json#7)
- [API 4 - RemoveBG](https://github.com/KillovSky/iris/blob/main/lib/config/config.json#8)
- [API 5 - WallHaven](https://github.com/KillovSky/iris/blob/main/lib/config/config.json#12)
- [Limite de Membros](https://github.com/KillovSky/iris/blob/main/lib/config/config.json#10)
- [Limite de Grupos](https://github.com/KillovSky/iris/blob/main/lib/config/config.json#9)
- [Prefix](https://github.com/KillovSky/iris/blob/main/lib/config/config.json#4)
- [Número 1 & 2](https://github.com/KillovSky/iris/blob/main/lib/config/config.json#2)
- [DDI](https://github.com/KillovSky/iris/blob/main/lib/config/config.json#3)
- [Bomber](https://github.com/KillovSky/iris/blob/main/config.js#L3131)
- [Akinator](https://github.com/KillovSky/iris/blob/main/lib/config/config.json#11)
- Elas são referentes aos sites [RemoveBG](https://www.remove.bg/pt-br), [ImgBB](https://api.imgbb.com/), [AlphaCoders](https://wall.alphacoders.com/api.php) e [WallHaven](https://wallhaven.cc/settings/account).
- A DDI e Akinator são obrigatórios apenas caso você for de fora do Brasil, o Bomb apenas se você usar Linux.

### Brainly Português
Depois de terminar a instalação siga esses passos para deixar seu brainly em português:

```
Abra a brainly.js na pasta iris\node_modules\brainly-scraper\src
Mude a graphql/id para graphql/pt
```

### Bem-vindo/Adeus em Português
Após a instalação dos módulos siga esses passos para deixar seu bem-vindo(Welcome) e adeus(Goodbye) em português:

```
Abra a pasta iris\node_modules\discord-canvas\src\greetings
Abra a Welcome e localize a linha "this.textTitle" e "this.textMessage"
Mude o "Welcome" e "Welcome in" para o que quiser e repita o mesmo processo na Goodbye
```

### Computer-Freaker/Axios
Para fixar o funcionamento da API da Computer-Freaker, que é responsável por diversos comandos (hug, hentai, dva, baguette...), siga os passos desse [Mini-Tutorial](https://github.com/KillovSky/iris/discussions/10).

### Alertas no WhatsApp
Para receber também as mensagem de erros do botbatata pelo WhatsApp, remova a "//" da linha [Catch](https://github.com/KillovSky/iris/blob/main/config.js#L3675).


