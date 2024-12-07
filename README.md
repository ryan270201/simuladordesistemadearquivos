# simuladordesistemadearquivos

### Metodologia
O simulador será desenvolvido em Java. Ele receberá chamadas de métodos com os parâmetros correspondentes e implementará as funcionalidades requeridas para cada comando. O programa executará cada funcionalidade e exibirá os resultados na tela.

### Parte 1: Introdução ao Sistema de Arquivos com Journaling

**Descrição do sistema de arquivos:**
Um sistema de arquivos é responsável pela organização, armazenamento, recuperação e manipulação de dados em um dispositivo de armazenamento. Ele fornece uma maneira estruturada de armazenar e acessar arquivos de forma eficiente e segura.

**Journaling:**
O journaling é uma técnica utilizada em sistemas de arquivos para garantir a integridade dos dados. Consiste em manter um log (jornal) de todas as operações realizadas, permitindo a recuperação do sistema em caso de falhas. Existem diferentes tipos de journaling, como o write-ahead logging e o log-structured, cada um com suas particularidades.

### Parte 2: Arquitetura do Simulador

**Estrutura de Dados:**
O sistema de arquivos será representado por classes Java que modelam arquivos, diretórios e o próprio sistema de arquivos. As principais classes são:
- **File**: Representa um arquivo.
- **Directory**: Representa um diretório e contém arquivos e subdiretórios.
- **Journal**: Gerencia o log de operações realizadas no sistema de arquivos.

**Journaling:**
O journaling será implementado através da classe `Journal`, que manterá um registro de todas as operações realizadas (criação, remoção, renomeação de arquivos e diretórios). Isso garantirá a integridade dos dados e permitirá a recuperação em caso de falhas.

### Parte 3: Implementação em Java

**Classe `FileSystemSimulator`:**
Implementa o simulador do sistema de arquivos, incluindo métodos para cada operação. Recebe comandos do usuário e executa as operações correspondentes, registrando-as no journal.

**Classes `File` e `Directory`:**
Representam arquivos e diretórios, respectivamente. Incluem métodos para manipulação (adicionar, remover, renomear) de arquivos e diretórios.

**Classe `Journal`:**
Gerencia o log de operações realizadas no sistema de arquivos. Inclui métodos para registrar operações e exibir o log.
