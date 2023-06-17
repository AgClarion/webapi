# WhatsPainel Saas</br>
Baileys 4 </br> Devido ao fim do suporte para Baileys 4 e 5 por parte do WhatsApp, a biblioteca baileys tem que ser atualizada para o 6.1, mesmo que alguns techos do codigo tenham chamdas legadas daq versão 4, está atualização não impacta o funcionamento do sistema.

Edite a linha do package.json dentro do diretório backend substituindo:

"@adiwajshing/baileys": "^4.0.0", por  "@adiwajshing/baileys": "github:WhiskeySockets/Baileys",

Execute npm update seguido de pm2 restart all (sobre o caminho backend)

Em breve remnoremos todas as chamadas legadas do código.

Com Integração Facebook/Instagram - Em Homologação

Com Cadastro Ativado</br>
Bugs em Revisão: Retorno GerenciaNet</br>
Meta: Mensagem de resposta inválida
