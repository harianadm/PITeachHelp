# TRABALHO DE PI:  TeachHelp
Trabalho desenvolvido durante a disciplina de Banco de Dados do Integrado

# Sumário

### 1. COMPONENTES<br>
Integrantes do grupo<br>
Davi Cardoso Salles: cardososallesdavi@gmail.com<br>
Evelyn Pereira Otavio: evelynpo59@gmail.com<br>
Harian Adami Chagas Radaelli: harianadami@gmail.com<br>
Wilsiman Santos Evangelista Silva: 
...

### 2.MINIMUNDO<br>
Descrever o mini-mundo! (Não deve ser maior do que 30 linhas, se necessário resumir para justar)
Entrevista com o usuário e identificação dos requisitos.(quando for o caso de sistemas com cliente real)
Descrição textual das regras de negócio definidas como um subconjunto do mundo real cujos elementos são propriedades que desejamos incluir, processar, armazenar, gerenciar, atualizar, e que descrevem a proposta/solução a ser desenvolvida.
<br>

> Você já se deparou com dificuldades no aprendizado de um conteúdo? 
Como você solucionou esse problema? Acredita que necessitava de professores à sua disposição? Inspirados nisso desenvolvemos uma plataforma de instrutores particulares, o TeachHelp
Nossa plataforma possibilita conectar instrutores especializados que ensinam conteúdos personalizados aos usuários. Não só matérias do meio acadêmico, mas diversos âmbitos e especializações, como esportes, música, informática, entre outros. 
Nosso sistema irá conter informações sobre os alunos (nome, e-mail, telefone e endereço) e dos instrutores (nome, e-mail, telefone, endereço, região em que dará aula, matéria e currículo). O aluno poderá procurar por professores por uma aba de pesquisa e filtrar por região e matéria que precisa; já o professor poderá realizar o cadastro e receberá uma solicitação assim que seus serviços forem acionados. O aplicativo irá disponibilizar um chat para um contato inicial do aluno com o professor/instrutor, além de tornar o currículo do instrutor/professor acessível para os alunos.

### 3.PMC<br>
Nosso PMC: https://docs.google.com/presentation/d/1yU2cTgEOXstYfytNe7FxaqfhF0bWs9rByE93pu4grcs/edit?usp=sharing <br>

![image](https://github.com/harianadm/PITeachHelp/assets/91471333/4148788a-356f-4e7d-8925-3dd42882f49c) <br>

#### 3.1. EAP - Estrutura Analítica do Projeto

![image](https://github.com/harianadm/PITeachHelp/assets/91471333/fa25f70f-9219-47e0-aadc-6417b6df7c64) <br>

Dicionário <br>

![image](https://github.com/harianadm/PITeachHelp/assets/91471333/1b5b87bc-4fb2-4d62-86cf-947ae2ab673b) <br>

![image](https://github.com/harianadm/PITeachHelp/assets/91471333/dbeae1d9-dbae-4339-a38b-09f1482889db) <br>


#### 3.2. Requisitos funcionais e não funcionais

![image](https://github.com/harianadm/PITeachHelp/assets/91471333/417eef31-dd44-4eb8-ab48-9623a5953171)
![image](https://github.com/harianadm/PITeachHelp/assets/91471333/f4eb2d28-3fe4-44f7-9a26-d0a352c705cd)


#### 3.3 Validação da Ideia.
[a) Link do formulário desenvolvido](https://forms.gle/4G4echLPE7DGumtc7)

[b) Link para Relatório/Apresentação de resultados obtidos](https://www.canva.com/design/DAFgficO0WU/ow7QRr0P9hOsrB-BuAmOnA/view?utm_content=DAFgficO0WU&utm_campaign=designshare&utm_medium=link&utm_source=publishsharelink)

### 4.Personas e Histórias de usuário<br>
Eu como aluno quero visualizar uma lista de instrutores de matérias e submatérias escolhidas por mim para contatar o intrutor escolhido por mim

Eu como Instrutor quero disponibilizar minhas competências para os usuarios da aplicação para ser contatado por eles

### 5. PROTÓTIPOS DO SISTEMA<br>
Neste ponto a codificação não e necessária, somente as ideias de telas devem ser desenvolvidas. O princípio aqui é pensar na criação da interface para identificar possíveis informações a serem armazenadas e/ou descartadas <br>

Sugestão: https://balsamiq.com/products/mockups/<br>

![Alt text](https://github.com/discproint/template_projeto_integrador/blob/main/arquivos/balsamiq.png?raw=true "Title")
![Arquivo PDF do Protótipo Balsamiq feito para Empresa Devcom](https://github.com/discproint/template_projeto_integrador/blob/main/arquivos/EmpresaDevcom.pdf?raw=true "Empresa Devcom")

#### 5.1 PROTÓTIPO DO SISTEMA MOBILE

#### 5.2 PROTÓTIPO DO SISTEMA WEB

#### 5.3 QUAIS PERGUNTAS PODEM SER RESPONDIDAS COM OS SISTEMA WEB/MOBILE PROPOSTOS?
    a) O sistema proposto poderá fornecer quais tipos de relatórios e informaçes? 
    b) Crie uma lista com os 5 principais relatórios que poderão ser obtidos por meio do sistema proposto!
    
> A Empresa DevCom precisa inicialmente dos seguintes relatórios:
* Relatório que informe quais são os gerentes de cada departamento incluindo as seguintes informações: número do departamento,  nome do departamento, e nome do gerente.
* Relatório de empregados por projeto incluindo as seguintes informações: número do projeto, nome do projeto, rg do empregado, nome do empregado e quantidade de horas de trabalho do empregado alocadas ao projeto.
* Relatório de empregados com dependentes incluindo as seguintes informações: rg do empregado, nome do empregado, nome do dependente, tipo de relação, data de nascimento do dependente e sexo do dependente.
* Relatório com a quantidade de empregados por cada departamento incluindo as seguintes informações: nome do departamento, supervisor e quantidade de empregados alocados no departamento.
* Relatório de supervisores e supervisionados incluindo as seguintes informações: nome do supervisor e nome do supervisionado.
 
 ### 6.MODELO CONCEITUAL<br>
    A) Utilizar a Notação adequada (Preferencialmente utilizar o BR Modelo 3)
    B) O mínimo de entidades do modelo conceitual pare este trabalho será igual a 4.
        * informe quais são as 3 principais entidades do sistema em densenvolvimento
      (se houverem mais de 3 entidades, pense na importância da entidade para o sistema)       
    C) Principais fluxos de informação/entidades do sistema (mínimo 2). <br>Dica: normalmente estes fluxos estão associados as tabelas que conterão maior quantidade de dados 
    D) Qualidade e Clareza
        Garantir que a semântica dos atributos seja clara no esquema (nomes coerentes com os dados).
        Criar o esquema de forma a garantir a redução de informação redundante, possibilidade de valores null, 
        e tuplas falsas (Aplicar os conceitos de normalização abordados).   
        
![Alt text](https://github.com/discproint/template_projeto_integrador/blob/main/arquivos/concept_sample.png?raw=true "Modelo Conceitual")
      
    
#### 7 Descrição dos dados 
    [objeto]: [descrição do objeto]
    
    EXEMPLO:
    CLIENTE: Tabela que armazena as informações relativas ao cliente<br>
    CPF: campo que armazena o número de Cadastro de Pessoa Física para cada cliente da empresa.<br>

### 8	RASTREABILIDADE DOS ARTEFATOS<br>
        a) Historia de usuários vs protótipo (Histórias de Usuário e em qual tela do protótipo aquela HU está sendo realizada).
        b) Protótipo vs Modelo conceitual (Histórias de Usuário e em quais tabelas aquele dado está sendo registrado).
        (modelos devem obrigatoriamente estar em conformidade de rastreabilidade)

### 9	MODELO LÓGICO<br>
        a) inclusão do esquema lógico do banco de dados
        b) verificação de correspondencia com o modelo conceitual 
        (não serão aceitos modelos que não estejam em conformidade)

### 10	MODELO FÍSICO<br>
        a) inclusão das instruções de criacão das estruturas em SQL/DDL 
        (criação de tabelas, alterações, etc..) 
        
       
### 11	INSERT APLICADO NAS TABELAS DO BANCO DE DADOS<br>
        a) inclusão das instruções de inserção dos dados nas tabelas criadas pelo script de modelo físico
        (Drop para exclusão de tabelas + create definição de para tabelas e estruturas de dados 
 <br> + insert para dados a serem inseridos)
        b) Criar um novo banco de dados para testar a restauracao 
        (em caso de falha na restauração o grupo não pontuará neste quesito)
        c) formato .SQL

#### 12 PRINCIPAIS CONSULTAS DO SISTEMA 
 Inserir as principais consultas (relativas aos 5 principais relatórios) definidas previamente no iten 3.1 deste template.
 <br>
  a) Você deve apresentar as consultas em formato SQL para cad um dos relatórios.
 <br>
  b) Além da consulta deve ser apresentada uma imagem com o resultado obtido para cada consulta.<br>

 ### 13 Gráficos, relatórios, integração com Linguagem de programação e outras solicitações.<br>
     OBS: Observe as instruções relacionadas a cada uma das atividades abaixo.<br>
 #### 13.1	Integração com Linguagem de programação; <br>
 #### 13.2	Desenvolvimento de gráficos/relatórios pertinentes, juntamente com demais <br>
 #### solicitações feitas pelo professor. <br>
 
 ### 14 Slides e Apresentação em vídeo. <br>
     OBS: Observe as instruções relacionadas a cada uma das atividades abaixo.<br>
 #### 14.1 Slides; <br>
 #### 14.2 Apresentação em vídeo <br>

    
##### About Formatting
    https://help.github.com/articles/about-writing-and-formatting-on-github/
    
##### Basic Formatting in Git
    
    https://help.github.com/articles/basic-writing-and-formatting-syntax/#referencing-issues-and-pull-requests
   
    
##### Working with advanced formatting
    https://help.github.com/articles/working-with-advanced-formatting/

#### Mastering Markdown
    https://guides.github.com/features/mastering-markdown/

### OBSERVAÇÕES IMPORTANTES

#### Todos os arquivos que fazem parte do projeto (Imagens, pdfs, arquivos fonte, etc..), devem estar presentes no GIT. Os arquivos do projeto vigente não devem ser armazenados em quaisquer outras plataformas.
1. Caso existam arquivos com conteúdos sigilosos, comunicar o professor que definirá em conjunto com o grupo a melhor forma de armazenamento do arquivo.

#### Todos os grupos deverão fazer Fork deste repositório e dar permissões administrativas ao usuário deste GIT, para acompanhamento do trabalho.

#### Os usuários criados no GIT devem possuir o nome de identificação do aluno (não serão aceitos nomes como Eu123, meuprojeto, pro456, etc). Em caso de dúvida comunicar o professor.


Link para BrModelo:<br>
http://sis4.com/brModelo/brModelo/download.html
<br>


Link para curso de GIT<br>
![https://www.youtube.com/curso_git](https://www.youtube.com/playlist?list=PLo7sFyCeiGUdIyEmHdfbuD2eR4XPDqnN2?raw=true "Title")
