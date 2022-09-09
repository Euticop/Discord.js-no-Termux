# Discord.js-no-Termux
Faça um simples bot na versão atualizada do nodejs e do discord.js, pelo seu celular e pelo o termux!
Deixei os créditos ao autor da index no final do arquivo.
Caso precise de ajuda, me contate no pv do Discord. Silva.#0002

1- Primeiramente, baixe o termux no site oficial (termux.com) ou diretamente pela play store.

2- Após baixar o termux, utilize o comando **pkg update && pkg upgrade**.

3- Após os packages estarem atualizados, introduza o seguinte comando em seu terminal;

```
1- termux-setup-storage
2- pkg install nodejs
```

# Após concluir todos os passoa abaixo, utilizaremos:

```
1- cd /mnt/sdcard
2- mkdir (Nome de uma pasta onde instalará o seu bot.)
3- cd (Nome da pasta do seu bot) 

ex: cd Eduardo.
```

# Criando o arquivo principal

Após ter concluido tudo, iremos iniciar o arquivo inicial (index.js) de seu bot, e para isso, antes, deveremos utilizar **npm init**, para instalar os arquivos do Discord

Apenas tecle enter em tudo, e no final digite **Yes**.

Depois de utilizar npm init, partiremos para a index.js, o arquivo principal de todo o bot qur utiliza Discord.js.

__Digite esse comando em seu Terminal, e cole esta index.__

```
1- nano index.js (Para abrir um editor de texto do termux.)
2- copie e cole na index.js

Index: https://sourceb.in/RgZmAd6yVN
```

Após ter colado este código na index, acione o botão Ctrl e Aperte C no teclado de seu smartphone, após isso, digite Y, aguarde e aperte enter. Pronto! seu arquivo está salvo, agora iremos partir para a config.json.

# Criando o arquivo Config.json

Depois da index.js, o config é o responsável por armazenar alguns arquivos importantes do bot, como o token, prefixo, e entre outros!

Siga os passos a passos abaixo;

```
1- nano config.json
2- Copie e cole este link em seu arquivo .json: https://sourceb.in/uSVnpFciha
3- Pegue seu token no site de developers do discord
4- Insira entre os "" na parte escrita "token"
3- Salve seu arquivo.
```

# Utilizando npm i discord.js

Para instalar as dependências do discord.js V14, utilize **npm i discord.js** em seu terminal do termux.
Aguarde terminar a instalação, e iremos partir para a handler.

# Handler

Para a criação da handler, teremos que criar uma nova pasta chamada **handler** para armazenar a nossa handler.
Siga a ordem abaixo.

```
1- mkdir handler
2- cd handler
3- Crie um arquivo chamado **index.js**
4- Copie e Cole em sua index.js da pasta **handler** o código deste link: https://sourceb.in/2Xi9P7x7M8
5- Salve seu arquivo.
```

# Pasta de Comandos

Bom, já finalizando, temos que criar uma pasta para armazenar os nossos comandos, por isso ensinarei como criá-las e como utilizá-las.

```
1- mkdir Comandos
2- cd Comandos
3- mkdir Utilitários
4- mkdir Moderação
5- mkdir Diversão
6- Após ter criado todas essas SubPastas, elas irão servir para adicionarmos SlashCommands.
```

# Criação de Comandos

Após ter feito a criação de **SubPastas**, temos que adicionar um comando de Ping, então, teremos que criar um arquivo chamado "ping.js", em qualquer SubPasta da sua escolha, após isso;

```
1- Pegue o código deste link: https://sourceb.in/Wh6jiu4a39
2- Cole em seu arquivo de **ping.js** que criamos anteriormente
3- Salve seu arquivo.
```

Após isso, o seu bot já pode ser ligado.

# Ligando o Bot

Após ter criado arquivos e pastas, chegou a hora tão sonhada de ligar o seu bot! E para isso usaremos um simples comando que fará a magia de ligar o nosso bot;

```
node .
```

Após efetuar este comando em seu terminal, aguarde até que seu bot ligue, caso dê algum erro, contate Silva.#0002 no privado!

Depois de seu bot está ligado, temos que testar o comando de ping. E para isso utilizaremos **/** antes do comando, para executar os **SlashCommands**, caso dê tudo certo, seu bot está totalmente preparado para a adicionação de comandos ou para a sua utilização

# Agradecimentos e Créditos

o Ferinha:

Discord: ! ferinha#2995

YouTube: https://youtube.com/c/OFerinha

Servidor do Discord: discord.gg/ferinha
