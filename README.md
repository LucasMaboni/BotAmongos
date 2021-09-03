# BotAmongos (AmongUs)
Bot para silenciar canal de voz no discord, utilizado em servidores privados/pequenos.

Criei um bot para uso privado no seu servidor.
Q: O que ele faz?
R: Muta todos os usuários do canal de voz com comando no chat.

Q: Como que adiciona ele no meu servidor?
R: Você precisa ter um BOT no seu servidor e adicionar o token dele no código. Depois disso só ligar o bot.

Q: Como adiciono esse bot no meu servidor para utilizar?

1º Configure um bot para seu discord, nome, foto e gere um token de bot.
Convide o bot para seu servidor com as devidas permissões:
| View Audit Log
| Mention @everyone, @here, and All Roles
| View Channel
| Connect
| Speak
| Mute Members
Você pode usar esse site para gerar as permissões do seu bot quando for convidá-lo para seu servidor: https://discordapi.com/permissions.html
Caso não saiba como faz isso, procure como criar um bot no discord do zero.

2º Na pasta do bot, abra |index.js| e adicione o Token do seu bot lá no discord dev, na variável token = ''. Ex: token = '23j2ojioiajfoiawokok11okpokpoaksjeoij2qoij'
salve e feche.

3º Execute o LigarBot.bat e não feche a janela, se não o bot desliga.
Se o bot ficou ON, deu certo até aqui.

4º O USUÁRIO que irá utilizar o bot precisa da permissão VER REGISTRO DE AUDITORIA do servidor.
Então crie um cargo que tenha essa permissão ou adicione em algum ja existente.

5º O bot por padrão não tem as permissões
| Read Messages (Ler mensagens)
| Send Messages (Enviar mensagens)
| Read Message History (ver histórico de mensangens)
Basta criar um canal para comandar o bot e colocar o cargo do bot com essas permissões.
Ou você pode ir em algum canal já existente e dar essas permissões para o cargo do bot, assim ele conseguirá ler e receber o comando.

Se o bot consegue:
Ler, Enviar e ler o histórico de mensagens do canal então digite:
/ajuda
Para ver os comandos.
