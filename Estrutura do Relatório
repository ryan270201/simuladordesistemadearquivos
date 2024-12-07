Metodologia

Vamos desenvolver um simulador em Java. Ele vai receber comandos com os parâmetros necessários e oferecer as funcionalidades que precisamos para cada um deles. À medida que o programa executa essas tarefas, ele também mostrará os resultados na tela.

Parte 1: Introdução ao Sistema de Arquivos com Journaling
O que é um sistema de arquivos?

Um sistema de arquivos é como a organizadora de um grande arquivo de escritório. Ele é responsável por arrumar, armazenar, recuperar e gerenciar dados em dispositivos de armazenamento, oferecendo uma maneira fácil e segura de guardar e acessar arquivos.

O que é Journaling?

Journaling é uma técnica que ajuda a manter nossos dados seguros. Essa abordagem cria um registro (ou "jornal") de todas as operações que realizamos, o que permite recuperar informações caso algo dê errado. Existem diferentes métodos de journaling, como o write-ahead logging e o log-structured, cada um com suas características específicas.

Parte 2: Arquitetura do Simulador
Estrutura de Dados:

No nosso simulador, usaremos classes em Java para representar arquivos, diretórios e o próprio sistema de arquivos. Aqui estão as principais classes que vamos criar:

File: Representa um arquivo.

Directory: É como uma pasta que contém arquivos e outros diretórios.

Journal: Fica responsável por gerenciar o registro das operações que são feitas no sistema de arquivos.

Journaling:

Vamos implementar o journaling através da classe Journal, que vai manter um registro de todas as operações que fazemos (como criar, remover ou renomear arquivos e diretórios). Isso nos ajudará a garantir que nossos dados estejam sempre seguros e que possamos recuperá-los em caso de alguma falha.

Parte 3: Implementação em Java
Classe FileSystemSimulator:

Essa classe vai ser o coração do nosso simulador do sistema de arquivos. Ela contará com métodos para cada operação e receberá comandos do usuário, realizando as ações correspondentes e registrando tudo no journal.

Classes File e Directory:

Essas classes vão representar, respectivamente, os arquivos e diretórios. Elas incluirão métodos para manipulação, como adicionar, remover e renomear arquivos e diretórios.

Classe Journal:

Por fim, a classe Journal vai cuidar do registro das operações que fazemos no sistema de arquivos. Ela terá métodos que permitem registrar cada ação e também exibir o log para que possamos acompanhar tudo o que aconteceu
