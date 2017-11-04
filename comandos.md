# Lista de Comandos #

- **X** define um número específico.
- Argumentos entre **( )** são opcionais.

## Coordenadores

| Comando | Argumento | Descrição |
|:-------:|:---------:|:-----------:|
| !botname | — | exibe o nome do bot. |
| !clearchat | — | limpa o chat no navegador do bot. |
| !clearlocalstorage | — | limpa os dados do bot do navegador. |
| !cycle | — | muda o ciclo de DJs. |
| !cycletimer | X | Defina o tempo máximo de ciclo de DJ para quando o cicloguard está habilitado. |
| !language | (nome do idioma em inglês) | especifica o idioma que você gostaria que o bot usasse. |
| !locktimer | X | define o tempo máximo em que a lista de espera pode ser bloqueada se o bloqueio estiver ativado. |
| !logout | — | desloga o bot da conta no plug.dj. |
| !maxlength | X | especifica o comprimento máximo que uma música pode ter quando o tempo está ativado. |
| !refresh | — | reinicia a página do bot. |
| !skippos | X | define a posição para pular e mover o dj. |
| !usercommands | — | modifica os comandos dos usuários. |
| !voteskip | (X) | quando nenhum argumento é especificado, retorna o limite atual do limite de votos, quando X é especificado, o limite do limite de votos é atualizado para o novo limite especificado. |
| !mensagens | — | exibe uma mensagem aleatória do bot. |
| !maxlength / !tempo / !duracao | (X) | exibe o tempo limite da sala, ou modifica o limite para X minutos. |

## Coordenadores+

| Comando | Argumento | Descrição |
|:-------:|:---------:|:-----------:|
| !add | @user | adiciona o `usuário` à lista de espera. |
| !lock | — | tranca a lista de espera. |
| !unlock | — | desbloqueia a lista de espera. |
| !lockdown | — | bloqueia a sala: apenas os administradores podem conversar. |
| !move | @user (X) | move o usuário para a posição X na lista de espera, se não for informado, o padrão é 1. |
| !remove | @user | remove o usuário da lista de espera. |
| !songstats | — | ativa ou desativa as estatísticas das músicas tocadas. |
| !swap | @user1 @user2 | troca a posição de dois usuários na lista de espera. |
| !welcome | — | modifica a mensagem de boas vindas. |

## Seguranças

| Comando | Argumento | Descrição |
|:-------:|:---------:|:-----------:|
| !active | (X) | mostra quais usuários conversaram nos últimos X minutos. Se X não for especificado, será usado 60 por padrão. |
| !autodisable | — | modifica o autodisable. |
| !ban | @user | exclui o usuário da sala por 1 dia. |
| !blacklist / !bl | blacklistname | adiciona a música especificada á lista de músicas proíbidas. |
| !blinfo | — | mostra as informações necessárias para listar uma música como proibida (blacklist). |
| !cycleguard | — | modifica o cycleguard. |
| !dclookup / !dc | (@user) | retorna o usuário para sua última posição na lista de espera. |
| !english | @user | pede para o usuário falar em inglês (pede na lingua do usuário). |
| !portugues / !pt / !br | @user | pede para o usuário falar em português (pede na lingua do usuário). |
| !forceskip / !fs | — | força a música atual a ser pulada. |
| !historyskip | — | modifica a opção de pular músicas no histórico. |
| !jointime | @user | mostra quanto tempo o usuário esteve na sala. |
| !kick | (X) | tira o usuário por X minutos, o padrão é de 0,25 minutos (15 segundos). |
| !kill | — | desliga o bot. |
| !lockguard | — | modifica o lockguard. |
| !lockskip | (razão) | pula a música, bloqueia a lista de espera e move o dj de volta (a posição pode ser configurada com `!skippos`). |
| !mute | @user/(X) | mude o usuário, por X minutos se X for especificado, caso contrário por um período indefinido. |
| !reload | — | reinicia o bot. |
| !sessionstats | — | mostra as estatísticas da sessão atual. |
| !skip / !smartskip | (razão) | Pula a música e move o dj para a posição 1 (a posição pode ser definida com lockskippos !)
(motivo) as razões  estão definidas abaixo, utilizar a primeira palavra em negrito após o comando (ex.: `!skip som`).
**history** ”Sua música estava no histórico da sala.”
**som** "A música tocada tinha qualidade de som ruim ou não tinha som."
**genero** "Sua música não estava de acordo com os gêneros permitidos pela sala."
**nudes** "A música continha conteúdo impróprio NSFW :underage:"
**ind** "A música não estava disponível para alguns usuários." |
| !status | — | mostra as configurações básicas do bot. |
| !timeguard | — | modifica o timeguard. |
| !togglebl | — | modifica a blacklist. |
| !togglevoteskip | — | modifica o voteskip. |
| !unban | @user | tira o usuário do banimento. |
| !unmute | @user/all | tira o usuário do mudo. |
| !uptime | — | mostra a quanto tempo o bot está online |
| !voteratio | @user | mostra as estatisticas de voto de um usuário. |
| !whois | @user | mostra informações sobre o usuário especificado. |

## DJs Residentes

| Comando | Argumento | Descrição |
|:-------:|:---------:|:-----------:|
| !link | — | mostra o link do youtube para a música atual. |

## Usuários

| Comando | Argumento | Descrição |
|:-------:|:---------:|:-----------:|
| !ask | (pergunta) | o usuário faz uma pergunta ao bot e ele responde aleatóriamente com sim, não ou talvez. |
| !autowoot | — | exibe o link para o site do PlugCubed. |
| !commands / !comandos | — | mostra a página de comandos do bot. |
| !dclookup / !dc | — | move a si próprio para a posição onde estava na lista de espera. |
| !emoji / !emote / !emojis | — | mostra o link para a lista de emojis do plug.dj. |
| !eta | — | mostra o tempo que falta para tocar. |
| !fb / !face / !facebook | — | mostra o link para o grupo da sala. |
| !gif / !giphy | (palavra) | retorna gif (do giphy) relacionado à tag fornecida. Retorna um gif aleatório se nenhuma tag for fornecida. |
| !help / !ajuda | — | mostra o link para o projeto do SadBotTr00. |
| !rules / !regras | — | mostra o link para as regras da sala. |
| !source | — | mostra o repositório do basicBot no Github. |
| !theme / !tema | — | mostras os gêneros permitidos na sala. |
| !website / !grupo | — | o mesmo que `!fb`. |
