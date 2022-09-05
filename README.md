# Database Experience
## Banco de Dados
Um banco de dados é uma coleção organizada de informações - ou dados - estruturadas, normalmente armazenadas eletronicamente em um sistema de computador.
Representa o mundo real, Tem coerência, Tem um propósito
* Tipos de Bancos de Dados
  - Bancos de dados relacionais
  - Bancos de dados não-relacionais
  - Bancos de dados orientados a objetos
  - Bancos de dados OLTP
  - Bancos de dados distribuídos
  - Outros.
## SGBD - Sistema de Gerenciamento de Banco de Dados(DBMS Database Manager Sistem)
  Abordagem normal o próprio sistema gerência os dados, isso é trabalhoso, se mais de uma aplicação precisar acessar os dados fica trabalhoso.
* Vantagens
  - Controle de redundância
  - Restrição de acesso - Update, Read-only
  - Storage - prover persistência - o sistema não sabe como os arquivos são gravados eles apenas solicitam e informam  
  - Storage - prover estrutura
  - Backup e Recovery
  - Ganhos com uso de SGBD
   - Padronização
   - Redução do tempo de desenvolvimento da aplicação.
   - Flexibilidade
   - Disponibilidade infos atualizadas
   - Economia com escalabilidade
* Principais característica que definem a escolha de um SGBD.
  - Tempo de Mercado
  - Popularidade
  - Documentação
  - Robustez
  - Confiabilidade
  - Segurança
  - Multiplataforma
  
* SGBD's mais utilizados no mercado
  - Oracle DB - pioneiro, mais utilizado.
  - MySQL - opensource, aplicações web.
  - SQL Server - Microsoft - BI.
  - Postgre SQL
  - mongo DB - noSQL - orientado a documentos. Dados em bloco, dados e metadados no mesmo bloco(objeto).
  - redis - noSQL - orientado a chave valor.
* Abordagem de Um SGBD
  - Abstração - Isolamento entre programa e dados
  - Auto-descrição - possui uma descrição específica e concisa - Metadados e Schema - Estrutura bem definida dos dados sem a inserção dos mesmos.
  - Compartilhamento - os dados podem ser compartilhados com vários sistemas/usuários - Dificuldade em integração e manutenção - Controle de concorrência - Atomicidade, ou executa a transação total ou não executa. OLTP Transação
  - Controle de concorrência - o SGBD gerencia o acesso aos dados.
  - Usuários de BD: 
      - Designer - identifica os dados e requisitos - Representação e estrutura, fase preliminar, contexto de interação quais dados serão consumidos.
      - DBA - Adminstrador do BD - Gerencia os recursos, Orquestra, Autorização de acessos.
      - Usuários finais - 
      - Background - Operação e Manutenção - Responsáveis pelo ambiente de software e hardware do SGBD. Ferramentas opcionais como performance, modelagem, análise.
## Modelagem de Dados
Representação, Modelo, Referência - Possui foco na descrição e relacionamento dos elementos que compõem a representação do contexto(mini-mundo). 
![image](https://user-images.githubusercontent.com/28981742/188493544-5acd1831-ab24-40f2-be33-fb1d9b35de3e.png)
* Entidade-Relacionamento
![image](https://user-images.githubusercontent.com/28981742/188493607-4786a1a2-31ca-4164-9aea-9b47ef51859d.png)
* SQL - Structured Query Language, ou Linguagem de Consulta Estruturada - Linguagem declarativa - 
## Mercado de Data
* Engenheiro de dados - Desenho e construção, extrair os dados de fontes heterogêneas e disponibilizar para o consumo dos analistas e cientistas.
* Cientista de dados - Modelagem/ Reconhecimento de Padrões, Predição - técnicas de modelagem.
* Analista de Dados - Criação de dashboards, apresentação visual dos dados, busca entender o comportamento do negócio através dos dados.
* Data driven - análise de dados voltada para a estratégia da empresa onde o consumidor é o centro do negócio.
* No SQL - surge para tratar o gap deixado pelo Modelo Relacional.

