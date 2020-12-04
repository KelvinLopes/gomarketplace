#GoMarketplace
Um app desenvolvido em Reat Native que usa uma api fake em server json para listar os produtos. Com isso já é possível se ter uma ideia do app e como ele pode se comportar com uma api real.

###como usar?
Depois de clonar o repositório, acesse o diretório do projeto e rode o comando: ```yarn``` para instalar todas as dependências. Após isso rode o comando ```yarn start``` se estiver usando **Yarn**, isso já deixa o bundle iniciado, depois rode: ```yarn android```, caso esteja no Android senão pode rodar ```yarn ios```, aguardar o app ser instalado.

###Json Server
Rode o comando: ```yarn json-server server.json -p 3333```, isso habilita os dados dos produtos dentro do app.

Se estiver no Android, talvez terá que mudar o endereço na api, substituindo o localhost pelo ip de sua máquina, e excutar esse comando dessa forma: ```yarn json-server --host xxx.xxx.xx.xxx server.json -p 3333```, onde x devem ser substituidos pelo ip de seu local de desenvolvimento.

Essa configuração também serve no **Crostini no Chrome OS**.