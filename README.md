🎬 Filme App

Um aplicativo móvel desenvolvido como projeto de estudo utilizando React Native e Expo. O objetivo principal desta aplicação é praticar os conceitos fundamentais do desenvolvimento mobile, gerenciamento de estado e construção de interfaces de usuário.

🚀 Tecnologias Utilizadas

Este projeto foi construído com as seguintes tecnologias:

React Native - Framework para construção de aplicativos nativos.

Expo (SDK 58) - Plataforma e framework para aplicações React universais.

React Native Paper - Biblioteca de componentes UI (Material Design).

📋 Pré-requisitos

Antes de começar, você precisará ter as seguintes ferramentas instaladas em sua máquina:

Node.js (Recomendado versão LTS)

Aplicativo Expo Go instalado no seu dispositivo iOS ou Android.

🔧 Como executar o projeto localmente

Siga os passos abaixo para rodar a aplicação na sua máquina:

Clone o repositório (ou acesse a pasta do projeto):

cd app-mobile-expogo


Instale as dependências:

npm install


Inicie o servidor de desenvolvimento do Expo:

npx expo start


Abra no seu celular:

iOS: Abra o aplicativo de Câmera nativo e escaneie o QR Code exibido no terminal.

Android: Abra o aplicativo Expo Go e escaneie o QR Code diretamente por ele.

💡 Resolução de Problemas Comuns (Troubleshooting)

Erro de Autenticação no Expo Go (iOS):
Se o terminal exibir um erro informando que as contas do celular e do CLI não coincidem (You need to be signed in to Expo Go and Expo CLI...), autentique o seu terminal usando um Token de Acesso:

Gere um token em expo.dev/settings/access-tokens.

No seu terminal (PowerShell), defina a variável:

$env:EXPO_TOKEN="seu-token-aqui"


Reinicie o servidor limpando o cache: npx expo start -c.

Aviso de "overflow: hidden" em Surfaces:
No iOS, usar overflow: 'hidden' diretamente em um componente <Surface> (do React Native Paper) corta a exibição da sombra (elevation). Para corrigir, envolva o conteúdo interno do <Surface> em uma <View> e aplique o overflow: hidden nesta View interna, mantendo a sombra no <Surface> pai.

📝 Licença

Este projeto é apenas para fins de estudo e está sob a licença MIT.
