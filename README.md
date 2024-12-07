Metodologia
O simulador será desenvolvido em Java. Ele receberá chamadas de métodos pelos respectivos parâmetros e executará as funcionalidades necessárias para cada comando. O programa executará cada uma das funcionalidades e exibirá seus resultados na tela.

Parte 1: Introdução ao sistema de arquivos de registro em diário
Descrição do sistema de arquivos: Um sistema de arquivos é responsável por organizar, armazenar, recuperar e manipular dados em um dispositivo de armazenamento. Ele fornece maneiras estruturadas de armazenar e acessar arquivos de maneira eficiente e segura.

Registro no diário: O registro no diário é uma técnica de sistema de arquivos que mantém os dados intactos; mantém registros (diário) de todas as operações realizadas e os utiliza para restaurar o sistema em caso de falha. Existem diferentes tipos de registro no diário, como registro write-ahead e registro estruturado, que são diferentes em suas especificidades.

Parte 2: Arquitetura do Simulador
Estruturas de dados: O sistema de arquivos será representado como classes em Java que modelam arquivos e diretórios e o próprio sistema de arquivos. As aulas principais incluem:

Arquivo: Esta classe representa um arquivo.
Diretório: representa um diretório que contém arquivos e subdiretórios.
Diário: cuida do log das operações realizadas no sistema de arquivos.
Journaling: O Journaling será implementado pela classe Journal, que manterá um log de todas as operações realizadas (criação, remoção, renomeação de arquivos e diretórios). Isto, por sua vez, garantirá a integridade dos dados e a possibilidade de recuperação em caso de falha.

Parte 3: Classe de Implementação Java: FileSystemSimulator Implementa o simulador do sistema de arquivos, com métodos para cada operação. Recebe comandos do usuário e executa a operação correspondente, que é, naturalmente, registrada no jornal.

Classes Arquivo e Diretório: Representa um arquivo e um diretório, respectivamente. Inclui métodos para manipulação (criando, removendo, renomeando) de arquivos e diretórios.

Classe Journal: Trata do log de todas as operações realizadas no sistema de arquivos. Inclui métodos para operações de registrador e exibição de log.
