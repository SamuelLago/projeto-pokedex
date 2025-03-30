🪨📄✂️ JokenPo App em Flutter
Este projeto é uma aplicação mobile desenvolvida com Flutter que simula o tradicional jogo JokenPo (Pedra, Papel e Tesoura), permitindo que o usuário jogue contra o aplicativo.

📱 Objetivo
Este app foi criado como parte de um estudo para entender a estruturação de um projeto Flutter do zero, utilizando os principais widgets e boas práticas de desenvolvimento.

🚀 Funcionalidades
Estrutura básica de um app Flutter com Material Design

Definição de rotas e organização em múltiplas classes

Utilização de Scaffold, AppBar, Column, Row, Padding

Adição de imagens e layout visual centralizado

Exibição de escolhas do app e opções para o usuário

🧱 Estrutura do Projeto
main.dart: ponto de entrada do app, onde o widget raiz é definido.

jogo.dart: classe principal Jogo com layout da interface do jogo.

images/: contém as imagens usadas no jogo (como padrao.png, papel.png, tesoura.png etc).

pubspec.yaml: configurado para importar os assets de imagem corretamente.

🖼️ Preview da Interface
A tela principal contém:

Um título no topo com o nome do app

Uma imagem que representa a jogada do app

Um texto de instrução

Três imagens interativas representando Pedra, Papel e Tesoura

🛠️ Como rodar o projeto
Clone o repositório:

bash
Copiar
Editar
git clone https://github.com/seu-usuario/jokenpo-flutter.git
Navegue até o diretório:

bash
Copiar
Editar
cd jokenpo-flutter
Execute o comando para instalar as dependências:

bash
Copiar
Editar
flutter pub get
Rode o app em um emulador ou dispositivo físico:

bash
Copiar
Editar
flutter run
📂 Configuração de assets
Certifique-se de que seu pubspec.yaml está com as imagens referenciadas corretamente:

yaml
Copiar
Editar
flutter:
  assets:
    - images/padrao.png
    - images/papel.png
    - images/pedra.png
    - images/tesoura.png
📚 Aprendizado
Esse projeto aborda conceitos iniciais como:

Estruturação de widgets

Stateful vs Stateless Widgets

Navegação e organização de arquivos

Layouts responsivos e alinhamentos

Utilização de assets locais

📄 Licença
Este projeto está licenciado sob a MIT License.
