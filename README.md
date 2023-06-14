# TRABALHO DE PI:  TeachHelp
Trabalho desenvolvido durante a disciplina de Banco de Dados do Integrado

# Sumário

### 1. COMPONENTES<br>
Integrantes do grupo<br>
Davi Cardoso Salles: cardososallesdavi@gmail.com<br>
Evelyn Pereira Otávio: evelynpo59@gmail.com<br>
Harian Adami Chagas Radaelli: harianadami@gmail.com<br>
Wilsiman Santos Evangelista Silva: wilsiman.evangelista.ifes@gmail.com<br>
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
![image](https://github.com/harianadm/PITeachHelp/assets/103004390/9799f798-4ee4-4d03-9bab-25a94a15c833) <br>
![image](https://github.com/harianadm/PITeachHelp/assets/103004390/36caa5e3-f972-4a61-bc66-0e89e6b3b399) <br>
![image](https://github.com/harianadm/PITeachHelp/assets/103004390/a6d8edd6-68b2-467b-b275-72afa8f1b626) <br>

Eu como aluno quero visualizar uma lista de instrutores de matérias e submatérias escolhidas por mim para contatar o intrutor escolhido por mim

Eu como Instrutor quero disponibilizar minhas competências para os usuarios da aplicação para ser contatado por eles

### 5. PROTÓTIPOS DO SISTEMA<br>

Protótipo do sistema mobile: https://app.quant-ux.com/#/test.html?h=a2aa10azlPSGB1WKfzwmkbl8ybBReSbrF5OwUVs0Z3h4r8gQN4eyyMrRYg7G&ln=en

O professor ofertou a opção de escolhermos qual protótipo desenvolver e escolhemos por desenvolver apenas o protótipo mobile.

#### 5.3 QUAIS PERGUNTAS PODEM SER RESPONDIDAS COM OS SISTEMA WEB/MOBILE PROPOSTOS?

Relatório sobre quais instrutores estão relacionados a alguma matéria<br>
Relatório sobre quais horarios e quais dias da semana estão disponiveis por algum instrutor<br>
Relatório da quantidade de instrutores em uma determinada região<br>
Relatório de quais matérias foram mais escolhidas pelos usuários<br>
Relatório sobre as avaliações realizadas entre os usuários<br>
    
 ### 6.MODELO CONCEITUAL<br>
 ![image](https://github.com/harianadm/PITeachHelp/assets/91471333/bdbe4c93-5bb5-4ff4-b8d5-1714462b2b1a)
     
    
#### 7 Descrição dos dados 
    [objeto]: [descrição do objeto]
PESSOA: Tabela que indica todos os usuários cadastrados no site.<br>
-nome: campo que obtém o nome completo da pessoa cadastrada.<br>
-foto: campo que possui uma foto da pessoa cadastrada para identificação<br>
-data_nascimento: campo com a data de nascimento da pessoa cadastrada.<br>
-descricao: campo que contém uma descrição opcional da pessoa.<br>
-cpf: campo para identificação da pessoa.<br>
-id: campo de identificação do usuário da pessoa cadastrada.<br>
INSTRUTOR: Tabela que herda os atributos de PESSOA, mas com informações adicionais para identificar um instrutor na plataforma.<br>
-currículo: campo com um link para o currículo do instrutor.<br>
PESSOA_AVALIA_INSTRUTOR: relação onde um usuário cadastrado poderá avaliar um instrutor.<br>
-codigo: código da avaliação para identificá-la.<br>
-nota: atributo que armazena a nota da avaliação, que será utilizada para calcular a nota média do instrutor.<br>
INSTRUTOR_AVALIA_PESSOA: relação onde um instrutor cadastrado poderá avaliar outro usuário cadastrado (que não seja instrutor).<br>
-codigo: código da avaliação para identificá-la.<br>
-nota: atributo que armazena a nota da avaliação, que será utilizada para calcular a nota média do aluno.<br>
MATERIA: Tabela que possui as matérias cadastradas no site.<br>
-codigo: atributo para identificar a matéria.<br>
-descricao: atributo que armazena o nome da matéria.<br>
SUBMATERIAS: Tabela que possui submatérias, correspondentes a uma matéria.<br>
-codigo: atributo para identificar a submatéria.<br>
-descricao: atributo que armazena o nome da submatéria.<br>
HORA: Tabela que possui os horários possíveis para o instrutor adicionar a sua agenda.<br>
-codigo: identificação do horário.<br>
-hora: atributo que mostra o horário.<br>
DIA_SEMANA: tabela que mostra os dias da semana.<br>
-codigo: atributo que identifica cada dia.<br>
-dia: atributo que nomeia o dia em questão.<br>
Agenda: relação que armazena um determinado número de atributos de DIA_SEMANA e HORA (selecionados pelo instrutor), e os combina para criar uma agenda.<br>
ENDERECO: Tabela que apresentará os endereços dos usuários cadastrados na plataforma.<br>
-nome_logradouro: atributo que contém o nome do logradouro do endereço cadastrado.<br>
-numero: atributo que possui o número do endereço cadastrado.<br>
-cep: atributo que armazena o cep do endereço cadastrado.<br>
-codigo: atributo de identificação do endereço.<br>
TIPO_LOGRADOURO: tabela que possui os tipos de logradouros para ser utilizada no cadastro do endereço.<br>
-codigo: atributo de identificação do tipo de logradouro.<br>
-descricao: atributo que nomeia o tipo de logradouro.<br>
BAIRRO: tabela que irá conter os bairros para o cadastro do endereço.<br>
-codigo: atributo de identificação do bairro.<br>
-nome: atributo que nomeia o bairro.<br>
MUNICIPIO: tabela que irá conter os municípios para o cadastro do endereço.<br>
-codigo: atributo de identificação do município.<br>
-nome: atributo que nomeia o município.<br>
COMPLEMENTO: tabela que contém os complementos de cada endereço.<br>
-codigo: atributo de identificação do complemento.<br>
-nome: atributo que nomeia o complemento.<br>
CONTATO: tabela que contém os contatos inseridos pelo usuário no seu cadastro.<br>
-codigo: atributo de identificação do contato.<br>
-descricao: atributo que representa o contato em si, seja composto por números (telefone) ou pelo corpo do e-mail.<br>
TIPO_CONTATO: tabela que representa o tipo do contato (e-mail ou telefone).<br>
-codigo: atributo de identificação do tipo do contato.<br>
-descricao: atributo que nomeia o tipo do contato.<br>

### 8	RASTREABILIDADE DOS ARTEFATOS<br>
![image](https://github.com/harianadm/PITeachHelp/assets/103004390/1af71482-bf6d-4039-a7a5-01f5d8e3c703)

### 9	MODELO LÓGICO<br>
 ![image](https://github.com/harianadm/PITeachHelp/assets/91471333/ab2edbb3-b16a-4596-b71e-0a654c86d623)

### 10	MODELO FÍSICO<br>
       CREATE TABLE BAIRRO (
    codigo SERIAL PRIMARY KEY,
    nome VARCHAR
);<br>

CREATE TABLE MUNICIPIO (
    codigo SERIAL PRIMARY KEY,
    nome VARCHAR
);<br>

CREATE TABLE ESTADO (
    codigo SERIAL PRIMARY KEY,
    nome VARCHAR
);<br>

CREATE TABLE COMPLEMENTO (
    codigo SERIAL PRIMARY KEY,
    descricao VARCHAR
);<br>

CREATE TABLE TIPO_LOGRADOURO (
    codigo INTEGER PRIMARY KEY,
    descricao VARCHAR
);<br>

CREATE TABLE CONTATO (
    codigo SERIAL PRIMARY KEY,
    descricao VARCHAR,
    FK_PESSOA_id SERIAL,
    FK_TIPO_CONTATO_codigo SERIAL,
    FOREIGN KEY (FK_PESSOA_id) REFERENCES PESSOA (id),
    FOREIGN KEY (FK_TIPO_CONTATO_codigo) REFERENCES TIPO_CONTATO (codigo)

);<br>

CREATE TABLE TIPO_CONTATO (
    codigo SERIAL PRIMARY KEY,
    descricao VARCHAR
);<br>

CREATE TABLE MATERIA (
    codigo SERIAL PRIMARY KEY,
    descricao VARCHAR
);<br>

CREATE TABLE SUBMATERIAS (
    codigo SERIAL PRIMARY KEY,
    descricao VARCHAR,
    FK_MATERIA_codigo SERIAL,
    FOREIGN KEY (FK_MATERIA_codigo) REFERENCES MATERIA (codigo)
);<br>

CREATE TABLE ENDERECO (
    nome_logradouro VARCHAR,
    numero INTEGER,
    codigo SERIAL PRIMARY KEY,
    cep INTEGER,
    FK_TIPO_LOGRADOURO_codigo INTEGER,
    FK_BAIRRO_codigo SERIAL,
    FK_MUNICIPIO_codigo SERIAL,
    FK_ESTADO_codigo SERIAL,
    FOREIGN KEY (FK_TIPO_LOGRADOURO_codigo) REFERENCES TIPO_LOGRADOURO (codigo),
    FOREIGN KEY ( FK_BAIRRO_codigo) REFERENCES BAIRRO (codigo),
    FOREIGN KEY (FK_MUNICIPIO_codigo) REFERENCES MUNICIPIO (codigo),
    FOREIGN KEY (FK_ESTADO_codigo) REFERENCES ESTADO (codigo)
);<br>

CREATE TABLE ENDERECO_COMPLEMENTO (
    fk_ENDERECO_codigo SERIAL,
    fk_COMPLEMENTO_codigo SERIAL,
    FOREIGN KEY (fk_ENDERECO_codigo) REFERENCES ENDERECO (codigo),
    FOREIGN KEY (fk_COMPLEMENTO_codigo) REFERENCES COMPLEMENTO (codigo)
);<br>

CREATE TABLE FAVORITA (
    FK_INSTRUTOR_FK_PESSOA_id SERIAL,
    FK_PESSOA_id SERIAL,
    FOREIGN KEY (FK_INSTRUTOR_FK_PESSOA_id) REFERENCES PESSOA (id),
    FOREIGN KEY (FK_PESSOA_id) REFERENCES PESSOA (id)
);<br>

CREATE TABLE PESSOA_AVALIA_INSTRUTOR (
    fk_INSTRUTOR_FK_PESSOA_id SERIAL,
    fk_PESSOA_id SERIAL,
    codigo SERIAL PRIMARY KEY,
    nota INTEGER,
    FOREIGN KEY (fk_INSTRUTOR_FK_PESSOA_id) REFERENCES PESSOA (id),
    FOREIGN KEY (fk_PESSOA_id) REFERENCES PESSOA (id)
);<br>

CREATE TABLE INSTRUTOR_AVALIA_PESSOA (
    FK_INSTRUTOR_FK_PESSOA_id SERIAL,
    FK_PESSOA_id SERIAL,
    nota INTEGER,
    codigo SERIAL PRIMARY KEY,
    FOREIGN KEY (FK_INSTRUTOR_FK_PESSOA_id) REFERENCES PESSOA (id),
    FOREIGN KEY (FK_PESSOA_id) REFERENCES PESSOA (id)

);<br>

CREATE TABLE INSTRUTOR_MATERIA (
    fk_INSTRUTOR_FK_PESSOA_id SERIAL,
    fk_MATERIA_codigo SERIAL,
    FOREIGN KEY (fk_INSTRUTOR_FK_PESSOA_id) REFERENCES PESSOA (id),
    FOREIGN KEY (fk_MATERIA_codigo) REFERENCES PESSOA (id)
);<br>

CREATE TABLE PESSOA_MATERIA (
    fk_MATERIA_codigo SERIAL,
    fk_PESSOA_id SERIAL,
    FOREIGN KEY (fk_MATERIA_codigo) REFERENCES MATERIA (codigo),
    FOREIGN KEY (fk_PESSOA_id) REFERENCES PESSOA (id)
);<br>

CREATE TABLE INSTRUTOR (
    curriculo VARCHAR,
    FK_PESSOA_id SERIAL PRIMARY KEY,
    FOREIGN KEY (FK_PESSOA_id) REFERENCES PESSOA (id)
);<br>

CREATE TABLE PESSOA (
    nome VARCHAR,
    foto VARCHAR,
    descricao VARCHAR,
    cpf INTEGER,
    data_nascimento INTEGER,
    id SERIAL PRIMARY KEY,
    FK_ENDERECO_codigo SERIAL,
    FOREIGN KEY (FK_ENDERECO_codigo) REFERENCES ENDERECO (codigo)
);<br>

CREATE TABLE DIA_SEMANA (
    codigo SERIAL PRIMARY KEY,
    dia VARCHAR
);<br>

CREATE TABLE HORA (
    codigo SERIAL PRIMARY KEY,
    hora INTEGER
);<br>

CREATE TABLE Agenda_HORA_INSTRUTOR_DIA_SEMANA (
    fk_HORA_codigo SERIAL,
    fk_INSTRUTOR_FK_PESSOA_id SERIAL,
    fk_DIA_SEMANA_codigo SERIAL,
    FOREIGN KEY (fk_INSTRUTOR_FK_PESSOA_id) REFERENCES PESSOA (id),
    FOREIGN KEY (fk_DIA_SEMANA_codigo) REFERENCES DIA_SEMANA (codigo)
);<br>

        
### 11	INSERT APLICADO NAS TABELAS DO BANCO DE DADOS<br>
insert into bairro (nome) values ('jardim da penha'), ('Itaparica'), ('São Diogo'), ('Laranjeiras'), ('Morada de Laranjeiras'), ('Jacaraipe'), ('Jucutuquara'), ('Maria Ortiz'), ('Colina da Laranjeiras'), ('Goiabeiras');<br>

insert into municipio (nome) values ('Serra'), ('Vitória'), ('Vila Velha'), ('Cariacica');<br>

insert into estado (nome) values ('Espírito Santo'), ('São Paulo'), ('Rio de Janeiro'), ('Bahia'), ('Minas Gerais');<br>

insert into complemento (descricao) values ('Apt 104'), ('Apt 302, bloco 5'), ('Apt 900'), ('Apt 100, bloco 1'), ('Apt 503'), ('Apt 208, bloco 8'), ('Apt 150, bloco 2'), ('Apt 385'), ('Apt 103');<br>

insert into tipo_logradouro (descricao) values ('Rua'), ('Avenida'), ('Viela');<br>

INSERT INTO contato (descricao, fk_pessoa_id, fk_tipo_contato_codigo)
VALUES
    ('(28) 99594-9598', 1, 1),
    ('(27) 98127-4043', 2, 1),
    ('(27) 99727-3667', 3, 1),
    ('(28) 99560-5862', 4, 1),
    ('Rayssa.Silva@gmail.com', 4, 2),
    ('(27) 97534-5534', 5, 1),
    ('ana.nunes98@gmail.com', 5, 2),
    ('harianadami@gmail.com', 6, 2),
    ('fbruno3409@hotmail.com', 7, 2),
    ('(28) 98673-2373', 8, 1),
    ('fideliszanetti@hotmail.edu.com', 8, 2),
    ('(28) 99965-4897', 9, 1),
    ('(28) 98113-0608', 10, 1),
    ('camilafraga@gmail.com', 11, 2),
    ('(28) 98985-4821', 12, 1),
    ('(27) 99772-4715', 13, 1),
    ('nauviasouza18@gmail.edu.com', 13, 2),
    ('(27) 99966-3287', 14, 1),
    ('(27) 97525-8539', 15, 1),
    ('davinunesribeiro@hotmail.com', 15, 2),
    ('(27) 97699-2345', 16, 1),
    ('rosilene@gmail.com', 16, 2);<br>

insert into tipo_contato (descricao) values ('Telefone'), ('E-mail');<br>

insert into materia (descricao) values ('Português'), ('Matemática'), ('História'), ('Música'), ('Esportes');<br>

insert into submaterias (descricao, fk_materia_codigo) values ('Redação', 1), ('Português Geral',1), ('Grmática',1), ('Matemática geral', 2), ('Contabilidade', 2), ('Trigonometria',2), ('Matemática financeira',2), ('História geral', 3), ('Teoria musical',4), ('Violão',4), ('Teclado',4), ('Vôlei', 5), ('Futsal',5), ('Futebol',5), ('Basquete',5);<br>

insert into endereco (nome_logradouro, numero, cep, fk_tipo_logradouro_codigo, fk_bairro_codigo, fk_municipio_codigo, fk_estado_codigo) values ('Comissário Octavio de Queiroz', 10, 29027090,1,1,2,1), ('Dr. Antônio Basílio', 103, 29067890,1,1,2,1), ('Dr. Gilson Santos', 209, 25049384,1,2,3,1), ('Dom Pedro II', 2, 28078970,3,4,1,1), ('Copacabana', 442, 26090879,2,5,1,1), ('Manoel Bandeira', 200, 28090854, 1,3,1,1), ('Ludwick Macal', 390, 29087990,1,1,2,1), ('Alberto Tôrres', 1030, 28090843,2,3,2,1), ('Ouro Preto', 102, 27089030,3,10,2,1), ('São Pedro', 940, 29065080,1,8,2,1), ('Monte Líbano', 330, 28079040,2,9,1,1), ('Jatobá', 209, 28045060, 1,9,1,1), ('Antônio Almeida Filho', 810, 27060050,2,2,3,1), ('Silvana Rosa', 304, 29070080,1,10,2,1), ('Copacabana', 400, 27094045,2,5,1,1);<br>


INSERT INTO endereco_complemento (fk_endereco_codigo, fk_complemento_codigo)
VALUES (1, 6),
       (3, 1),
       (5, 2),
       (6, 3),
       (11, 5),
       (12, 7),
       (14, 8),
       (15, 9);<br>


INSERT INTO favorita (fk_pessoa_id, fk_INSTRUTOR_FK_PESSOA_id)
VALUES
    (4, 7),
    (2, 16),
    (7, 13),
    (5, 4),
    (11, 8),
    (10, 9),
    (12, 10),
    (1, 2),
    (4, 9),
    (10, 4);<br>

INSERT INTO pessoa_avalia_instrutor (nota, fk_pessoa_id, fk_INSTRUTOR_FK_PESSOA_id)
VALUES
    (4, 1, 2),
    (5, 6, 13),
    (5, 3, 4),
    (2, 11, 4),
    (5, 5, 16),
    (5, 6, 16),
    (4, 12, 10),
    (3, 14, 7),
    (5, 15, 7),
    (1, 1, 8);<br>

INSERT INTO instrutor_avalia_pessoa (nota, fk_pessoa_id, fk_INSTRUTOR_FK_PESSOA_id)
VALUES
    (3, 2, 3),
    (4, 2, 6),
    (5, 10, 12),
    (5, 9, 14),
    (2, 8, 15),
    (5, 8, 1),
    (4, 16, 5),
    (4, 13, 11);<br>

INSERT INTO instrutor_materia (fk_materia_codigo, fk_INSTRUTOR_FK_PESSOA_id)
VALUES
    (1, 2),
    (2, 10),
    (3, 8),
    (4, 13),
    (5, 9),
    (1, 7),
    (2, 4),
    (3, 16),
    (4, 10),
    (5, 13);<br>

INSERT INTO pessoa_materia (fk_materia_codigo, fk_pessoa_id)
VALUES
    (2, 1),
    (3, 3),
    (2, 5),
    (4, 4),
    (1, 5),
    (5, 2),
    (2, 14),
    (3, 14),
    (4, 2),
    (5, 6);<br>

INSERT INTO instrutor (fk_pessoa_id, curriculo)
VALUES
    (8, 'http://lattes.cnpq.br/2373180848461397'),
    (2, 'http://lattes.cnpq.br/7420005616548454'),
    (4, 'http://lattes.cnpq.br/1456784568486514'),
    (7, 'http://lattes.cnpq.br/3645648694578534'),
    (13, 'http://lattes.cnpq.br/7515984919866826'),
    (10, 'http://lattes.cnpq.br/005922104339977'),
    (9, 'http://lattes.cnpq.br/1403241645360917'),
    (16, 'http://lattes.cnpq.br/7420005697745769');<br>


INSERT INTO pessoa (nome, cpf, foto, data_nascimento, descricao, fk_endereco_codigo)
VALUES
    ('Davi Cardoso Salles', '147.404.657-60', 'https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.gettyimages.com.br%2Ffotos%2Fadolescente&psig=AOvVaw2_Of62XrUCAvd19Dv55L6V&ust=1683812146695000&source=images&cd=vfe&ved=0CBEQjRxqFwoTCNDws5jv6v4CFQAAAAAdAAAAABAE', '2005-03-18', 'Busco aprender principalmente biologia e exatas, aprendo rápido e sou direto', 1),
    ('Renato Albani de Souza', '134.456.435', 'https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.institutousiminas.com%2Fprogramacao%2Frenato-albani-em-novo-show-stand-up%2F&psig=AOvVaw2EmvbY62aCtftm70dRvG4V&ust=1683812086143000&source=images&cd=vfe&ved=0CBEQjRxqFwoTCKikjPzu6v4CFQAAAAAdAAAAABAE', '1985-08-24', 'Leciono desde o ensino médio, então já tive todos os tipos possíveis de alunos: crianças, adolescentes, idosos', 2),
    ('Carlos Eduardo de Andrade', '275.846.645-70', 'https://www.google.com/url?sa=i&url=https%3A%2F%2Fbr.freepik.com%2Ffotos-premium%2Fretrato-de-adolescente-bonito-caucasiano-com-espinhas-no-rosto-no-tratamento-de-acne-ao-ar-livre-em-adolescentes_24424442.htm&psig=AOvVaw2_Of62XrUCAvd19Dv55L6V&ust=1683812146695000&source=images&cd=vfe&ved=0CBEQjRxqFwoTCNDws5jv6v4CFQAAAAAdAAAAABAV', '2005-05-03', 'Gosto muito de geografia, e busco aprender muito', 3),
    ('Rayssa Silva Nunes', '232.648.529-64', 'https://www.google.com/url?sa=i&url=https%3A%2F%2Fpt.vecteezy.com%2Ffotos-gratis%2Fprofessor&psig=AOvVaw1IFbQ73n3qJTTD1HFJwHq9&ust=1683812028801000&source=images&cd=vfe&ved=0CBEQjRxqFwoTCLC4k-Du6v4CFQAAAAAdAAAAABAU', '2002-04-09', 'Sou licenciada em Letras (Português/Literatura) pela Universidade Federal de Viçosa - UFV.', 4),
    ('Ana Julia Nunes Salles', '748.673.231-38', 'https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.unicef.org%2Fbrazil%2Fhistorias%2Fadolescente-convoca-estudantes-participar-das-politicas-publicas-de-joao-camara-rn&psig=AOvVaw3s8AJKmnRSIIB6OZvezdED&ust=1683812175461000&source=images&cd=vfe&ved=0CBEQjRxqFwoTCPio4qbv6v4CFQAAAAAdAAAAABAE', '2005-04-18', 'Sou estudante do instituto federal e busco ampliar meu conhecimento', 4),
    ('Harian Adami Chagas', '342.683.926-57', 'https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.unicef.org%2Fbrazil%2Fhistorias%2Ffotos-na-migracao-adolescentes-revelam-olhar-em-exposicao&psig=AOvVaw3s8AJKmnRSIIB6OZvezdED&ust=1683812175461000&source=images&cd=vfe&ved=0CBEQjRxqFwoTCPio4qbv6v4CFQAAAAAdAAAAABAJ', '2005-03-19', 'Gosto de estudar, acho interessante estudar por fora matérias ligadas a informática', 5),
    ('Fabrício Bruno Ferreira Castro', '683.926.093-56', 'https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.jornalcontabil.com.br%2Fcarreira-saiba-como-se-tornar-professor%2F&psig=AOvVaw1IFbQ73n3qJTTD1HFJwHq9&ust=1683812028801000&source=images&cd=vfe&ved=0CBEQjRxqFwoTCLC4k-Du6v4CFQAAAAAdAAAAABAJ', '1973-12-20', 'Biólogo, graduado com honras em Ciências Biológicas pela Universidade Federal do Ceará (UFC) e Mestre em Bioquímica pela Universidade Federal de Santa Catarina (UFSC).', 6),
    ('Fidelis Zanetti Castro', '352.735.819-56', 'https://www.google.com/url?sa=i&url=https%3A%2F%2Fmasterjuris.com.br%2Feducacao-pos-pandemia-a-importancia-do-professor-diante-do-cenario-atual%2F&psig=AOvVaw18E-HtVlvSthmi2MVe4wi4&ust=1683811883438000&source=images&cd=vfe&ved=0CBEQjRxqFwoTCODwzZvu6v4CFQAAAAAdAAAAABAL', '1984-06-29', 'Desde 2002 trabalho com aulas particulares de matemática, com alunos de todas as idades, auxiliando-os com metodologias e didática de fácil compreensão e contribuindo para seu aprimoramento em qualquer área de matemática (geometria, álgebra, etc.).', 7),
    ('Fellipe Frechiani', '562.900.356-54', 'https://www.google.com/url?sa=i&url=https%3A%2F%2Fvaidebolsa.com.br%2Fblog%2Fmercado-de-trabalho%2Fvagas-para-professor-universitario%2F&psig=AOvVaw3ed5BU0tNyYNgKRi1sl_CF&ust=1683812109233000&source=images&cd=vfe&ved=0CBEQjRxqFwoTCNjjpIfv6v4CFQAAAAAdAAAAABAJ', '1986-08-13', 'Faço uso de uma metodologia inovadora que mescla duas das maiores metodologias de língua e uma nova proposta moderna. As aulas serão ministradas no principio metodológico AAC (Acional Aquisicional Comunicacional) respeitando sempre as necessidades e os objetivos dos alunos.', 8),
    ('Moises Savedra Omena', '789.546.001-20', 'https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.cpt.com.br%2Fcursos-metodologia-de-ensino%2Fartigos%2Fperfil-e-atributos-de-um-bom-professor&psig=AOvVaw3ed5BU0tNyYNgKRi1sl_CF&ust=1683812109233000&source=images&cd=vfe&ved=0CBEQjRxqFwoTCNjjpIfv6v4CFQAAAAAdAAAAABAE', '1982-10-04', 'Olá. Sou um professor Americano morando em Brasil. Minha esposa é Brasileira e decidi vir morar no Brasil faz dois anos.', 9),
    ('Camila Fraga Egydio', '453.876.901-37', 'https://www.google.com/url?sa=i&url=https%3A%2F%2Fdrsantosneto.com.br%2Fmamoplastia-redutora-em-adolescentes%2F&psig=AOvVaw3s8AJKmnRSIIB6OZvezdED&ust=1683812175461000&source=images&cd=vfe&ved=0CBEQjRxqFwoTCPio4qbv6v4CFQAAAAAdAAAAABAS', '2006-04-14', 'Quero passar de ano', 10), 
    ('Sofia Andrade Nascimento', '289.009.647-90', 'https://www.google.com/url?sa=i&url=http%3A%2F%2Fwww.centropsicologialopezdefez.es%2Fblog%2Ffalta-de-motivacion-en-adolescentes%2F&psig=AOvVaw3s8AJKmnRSIIB6OZvezdED&ust=1683812175461000&source=images&cd=vfe&ved=0CBEQjRxqFwoTCPio4qbv6v4CFQAAAAAdAAAAABAb', '2006-01-28', 'Quero refazer meu ensino médio, pois tive na pandemia', 11),
    ('Nauvia de Souza Ferreira', '490.768.190-69', 'https://www.google.com/url?sa=i&url=https%3A%2F%2Fbr.depositphotos.com%2Fstock-photos%2Fdia-do-professores.html&psig=AOvVaw1IFbQ73n3qJTTD1HFJwHq9&ust=1683812028801000&source=images&cd=vfe&ved=0CBEQjRxqFwoTCLC4k-Du6v4CFQAAAAAdAAAAABAq', '1987-09-02', 'Sou professora há sete anos e tenho experiência em lecionar para o Ensino Fundamental e Médio, turmas de disciplinas isoladas em Física, Química e Matemática, aulas em grupo e individuais de Redação, Português, Inglês, Química, Física, Matemática, Biologia, História, Geografia e Ciências.', 12),
    ('Isabelly Balestrassi Andrade', '390.897.010-29', 'https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.cuerpomente.com%2Ftemas%2Fadolescencia&psig=AOvVaw3s8AJKmnRSIIB6OZvezdED&ust=1683812175461000&source=images&cd=vfe&ved=0CBEQjRxqFwoTCPio4qbv6v4CFQAAAAAdAAAAABAj', '2006-03-08', 'Gosto muito de matemática e quero aprender além da escola', 13),
    ('Davi Nunes de Souza', '389.090.618-19', 'https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.pexels.com%2Fpt-br%2Fprocurar%2Fadolescentes%2F&psig=AOvVaw2_Of62XrUCAvd19Dv55L6V&ust=1683812146695000&source=images&cd=vfe&ved=0CBEQjRxqFwoTCNDws5jv6v4CFQAAAAAdAAAAABAJ', '2005-06-23', 'Quero aprender um novo instrumento musical', 14),
    ('Rosilene de Freitas', '873.902.546-00', 'https://www.google.com/url?sa=i&url=https%3A%2F%2Fbr.depositphotos.com%2Fstock-photos%2Fprofessores.html&psig=AOvVaw1IFbQ73n3qJTTD1HFJwHq9&ust=1683812028801000&source=images&cd=vfe&ved=0CBEQjRxqFwoTCLC4k-Du6v4CFQAAAAAdAAAAABAf', '1979-10-21', '* Sou engenheira civil (UFMG) e especialista em engenharia de estruturas (UFMG).', 15);<br>

INSERT INTO dia_semana (dia)
VALUES
    ('Domingo'),
    ('Segunda-Feira'),
    ('Terça-Feira'),
    ('Quarta-Feira'),
    ('Quinta-Feira'),
    ('Sexta-Feira'),
    ('Sábado');<br>


INSERT INTO hora (hora)
VALUES
    ('08:00-08:30'),
    ('08:30-09:00'),
    ('09:00-09:30'),
    ('09:30-10:00'),
    ('10:00-10:30'),
    ('10:30-11:00'),
    ('11:00-11:30'),
    ('11:30-12:00'),
    ('12:00-12:30'),
    ('12:30-13:00'),
    ('13:00-13:30'),
    ('13:30-14:00'),
    ('14:00-14:30'),
    ('14:30-15:00'),
    ('15:00-15:30'),
    ('15:30-16:00'),
    ('16:00-16:30'),
    ('16:30-17:00'),
    ('17:00-17:30'),
    ('17:30-18:00');<br>


INSERT INTO agenda_hora_instrutor_dia_semana (fk_hora_codigo, fk_instrutor_fk_pessoa_id, fk_dia_semana_codigo)
VALUES
    (1, 2, 8),
    (1, 2, 2),
    (2, 2, 4),
    (3, 3, 4),
    (4, 3, 7),
    (8, 4, 13),
    (6, 4, 10),
    (1, 5, 9),
    (1, 5, 16),
    (2, 6, 10),
    (2, 6, 16),
    (5, 7, 8),
    (4, 7, 2),
    (6, 5, 7),
    (8, 1, 10);<br>

        b) Criar um novo banco de dados para testar a restauracao 
        (em caso de falha na restauração o grupo não pontuará neste quesito)
        c) formato .SQL

#### 12 PRINCIPAIS CONSULTAS DO SISTEMA 
 Inserir as principais consultas (relativas aos 5 principais relatórios) definidas previamente no iten 3.1 deste template.

https://colab.research.google.com/drive/1aj4wgpYyQ_izeBhBh8uaTrZiBQbsB7NF?usp=sharing

 ### 13 Gráficos, relatórios, integração com Linguagem de programação e outras solicitações.<br>
     https://colab.research.google.com/drive/1aj4wgpYyQ_izeBhBh8uaTrZiBQbsB7NF?usp=sharing
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
