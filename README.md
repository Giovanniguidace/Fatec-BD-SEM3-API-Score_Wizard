
# Projeto Integrador 3º Semestre

## :orange_book: <b>Desafio do PI 3º Semestre:</b>


![img1_javahype](https://gitlab.com/giovannimarassi/score-wizard/uploads/3af170f1cf52220384ad369aaf783563/img1_javahype.jpg)

Em parceria com ![img_spc](https://gitlab.com/giovannimarassi/score-wizard/uploads/6857783e3815331197ff74e74a95a480/img_spc.png)

O SPC, em parceria com os alunos do 3º semestre do curso de Banco de Dados da Fatec de SJC, necessita de um software para obter uma análise estatística da evolução do consumidor em relação ao histórico de pagamentos e também da evolução da nota de score. Esse software é usado por qualquer pessoa física ou jurídica, que possua cadastro positivo e que, ao utilizá-lo, espera melhorar seu score de uma forma melhor do que as outras alternativas existentes no mercado. Espera também, obter dados de sua evolução financeira, afim de contribuir para uma melhora de seu score, e, possivelmente, efetuar novas solicitações de crédito para as instituições financeiras.

## <b>:dart: Objetivo da Aplicação Score Wizard</b>

Foram levantadas ideias de calcular de uma forma mais exata possível o score de cada pessoa cadastrada na aplicação, onde ela possui um banco de dados com todos os dados de transação, empréstimo, financiamento e cartão de crédito de uma pessoa física.

Com estes dados e cálculo em mãos, foi levantada uma ideia de uma espécie de jogo, onde o usuário teria metas para cumprir, e, com as metas concluídas, teria um saldo de XP de experiência. Desta forma, há um incentivo para que as pessoas acessem a aplicação e cumpram as metas de melhoras no score.

A aplicação consiste de um Back-End criado com Gradle(Java) e o banco de dados postgreSQL. O Front-End criado com HTML, CSS e Javascript. O cálculo do score, análise de dados, metas e XP são criados  no Back-End. 

A aplicação possui um cadastro de pessoa física e jurídica, e, com o cpf ou cnpj cadastrado, a aplicação consegue analisar em uma massa de dados quais seriam seus dados de transações bancárias. 

* Criação do layout e funcionalidades do Front-End:

	*	Pensando em trazer uma experiência única e simples, ao mesmo tempo que atenda a necessidade, criamos um Front-End com um layout inovador e iterativo.

#

### Tela de Login

Na tela de Login, é possível realizar o acesso com CPF ou CNPJ, pois o acesso é o mesmo para Pessoa Física e Pessoa Jurídica.

![image](https://user-images.githubusercontent.com/62898187/139615048-514bb650-e99d-4684-89b7-2957f6f0036f.png)

#
### Tela de Cadastro de Pessoa Física ou Jurídica

Na tela de cadastro, é possível cadastrar tanto Pessoa Física quanto Jurídica.

![imagem_2021-10-31_234725](https://user-images.githubusercontent.com/62898187/139614715-edf61b3a-838b-4da5-b6ef-4fb5b450e680.png)

#

### Tela Inicial

Após realizar o login, o acesso será direcionado para a tela inicial da simulação.

![image](https://user-images.githubusercontent.com/62898187/142008215-7bc8c8ad-0282-4ed2-b62d-1362b4b06aff.png)

#
### Tela para selecionar o objetivo

Nesta tela, o usuário poderá selecionar o seu objetivo, para que a aplicação possa retornar a ele qual a porcentagem de alcançá-lo. Esta é uma forma de tornar a aplicação mais interessante ao usuário e ao mesmo tempo trazer uma informação útil no qual ele deseja naquele momento.

![image](https://user-images.githubusercontent.com/62898187/142009421-b9c27006-e192-4e94-989c-a60c649b7810.png)

#

### Tela para selecionar metas

Nesta tela, o usuário deverá selecionar pelo menos uma opção para que o cálculo da simulação seja feito. Estas opções são trazidas pela aplicação, após a análise completa de seus dados. São metas que o usuário poderá cumprir e assim, chegar mais próximo de seu objetivo.

![image](https://user-images.githubusercontent.com/62898187/142014566-aa341200-83d6-49a1-a41e-59bc6e9c5eb8.png)

#
### Tela com o resultado da simulação

Nesta tela, o usuário será informado sobre qual a porcentagem que ele terá para conquistar seu objetivo, ao cumprir as metas selecionadas na tela anterior. Também é informado quanto ficará seu Score.

![image](https://user-images.githubusercontent.com/62898187/142014688-c84e63e7-695e-436c-aab8-655fc0079831.png)

#


## <b>⚙️ Tecnologias Adotadas na Solução:</b>

-   MySql Community - Motivo: Foi realizada a utilização desta ferramenta para a modelagem do modelo EER de nossa base de dados;
-   Java 1.8 - Motivo: Versão válida e segura para a utilização em projetos em Java;
-   Gradle - Motivo: Foi realizada uma votação em grupo para a utilização deste framework para a criação da aplicação;
-   Maven - Motivo: Foi realizada uma votação em grupo para a utilização deste framework para a criação da aplicação;
-   Bootstrap 4 - Motivo: Foi realizada a escolha de implementar no projeto o Bootstrap 4 para realizar a criação do layout do Front-End;
-   Html5 - Motivo: Foi utilizado para a criação de templates;
-   JavaScript - Motivo: Foi escolhido a linguagem Javascript para implementar funcionalidades do Front-End;
-   CSS - Motivo: Foi realizado o uso de CSS para criar o layout do Front-End;

Para a escolha destas tecnologias, foram levantados alguns pontos, mas o mais crucial é que as matérias do semestre atual estavam preferindo a utilização de Java e aproveitamos para nos aperfeiçoar, para que pudéssemos tirar boas notas.

Particularmente, eu estava mais aprofundado em Python/Django devido aos outros projetos e matérias, mas, com o andar dos estudos em aula e a necessidade de me aprofundar para este API, corri atrás de aprender mais sobre Java e Spring Boot.

## <b> :wrench: Contribuições individuais/pessoais</b>

* Como SCRUM Master, tive algumas obrigações a serem feitas, como: Burndown das Sprints; Daily's; Planning's; Organizar o BackLog do produto; Criar os User's Story; conforme exemplos abaixo:

	* Burndown das sprints:
		![Captura_de_tela_de_2020-12-02_14-53-09](https://gitlab.com/giovannimarassi/score-wizard/uploads/e4b5f1a0aca003b73064f1559d825db3/Captura_de_tela_de_2020-12-02_14-53-09.png)

	*	Foi criada a User Story com BackLog definido:
		![Captura_de_tela_de_2020-11-03_10-20-07](https://gitlab.com/giovannimarassi/score-wizard/uploads/7f1aa202cc3691d204566d00916cf5ab/Captura_de_tela_de_2020-11-03_10-20-07.png)

	*	Exemplo de User Story:		

![image](https://user-images.githubusercontent.com/62898187/142046214-3e3ceeb7-4a70-41bb-96ef-335040497ee5.png)


*	Contribui também para a criação do Caso de Uso:		

![CASO_DE_USO_-SCORE_WIZARD__3](https://gitlab.com/giovannimarassi/score-wizard/uploads/f20e716a081edc21bbe86301d5f21a81/CASO_DE_USO_-_SCORE_WIZARD__3_.png)

* Criei o fluxograma de Cadastro de Pessoa Física; Cadastro de Pessoa Jurídica; Login; conforme imagens abaixo:

	* Cadastro de Pessoa Física
	
![Untitled__1_](https://gitlab.com/giovannimarassi/score-wizard/uploads/3dc6e9a6d03dca035a3b373b50abfaff/Untitled__1_.png)

* Cadastro de Pessoa Jurídica

![Untitled__2_](https://gitlab.com/giovannimarassi/score-wizard/uploads/55a603700a82f9c5ac6240ec6d2a3ae9/Untitled__2_.png)

*	Login

![Untitled__3_](https://gitlab.com/giovannimarassi/score-wizard/uploads/4d96ffa0717698e3700ac27f83767739/Untitled__3_.png)

* Auxilio na formulação do cálculo de score:
	*	O cálculo do Score não foi passado para a equipe, portanto houve a necessidade de estudar quais seriam os requisitos que seriam necessários para o cálculo do Score de cada pessoa física.
	
	Para entender melhor este estudo, clique no link: https://marbled-range-ed0.notion.site/Entenda-o-que-comp-e-o-c-lculo-do-Score-1348e1d22dbb49098a775e9d973c86e4

* Desenvolvimento das telas do simulador:
	*	As telas para que o usuário possa realizar a simulação foram desenvolvidas utilizando HTML/CSS/BootsTrap 4, e a linguagem de programação Javascript.


## <b>🧠 Aprendizados Efetivos</b>

* Metodologia ágil como SCRUM;
	*	Neste API eu atuei como Scrum Master e isso foi um grande desfio, pois eu nunca havia sido e foi maravilhoso ter essa função no time e aprender coisas novas. Fizemos Sprint Reviews, Plannings, Daily's, dentre outras funções que um Scrum Master possui. 

* Aprendizado de como funciona o cálculo do score;
	* O cálculo do Score utiliza de muitos fatores para que seja criado um Score compatível com a atual  situação de cada pessoa. São muitas variáveis e métricas que resultam em um valor, não sendo o mesmo para SPC, SERASA e etc... Cada empresa possui um cálculo distinto, são métricas distintas, mas para que possamos analisar um pouco o que seriam estes cálculos, temos a seguir as seguintes variáveis:
	 
		-Pontos Negativos:
		*	Quantidade de parcelas atrasadas com cartão de crédito;
		* Situação das parcelas atrasadas e se é uma pessoa que não costuma pagar em dia;
		* Solicitação de empréstimos e recusa do banco;
		* Empréstimos contratados recentemente;
		* Utilização de LIS;
		* Solicitação de cartão de crédito e recusa do banco;
		* Quantidade de vezes que o CPF é consultado;
		* Contas não pagas e nome sujo;

		-Pontos Positivos
		*	Solicitação de cartão de crédito e aceite pelo banco;
		* Nome limpo;
		* Não possuir empréstimos contratados;
		* Faturas de cartão pagas e em dia;
		* Poucas consultas de CPF;

* Aprendizado a trabalhar com dados "mockados":

	*	Para que pudéssemos criar os filtros e cálculos do Score, recebemos do SPC dados Mockados em .csv, onde realizamos a criação dos filtros e análises de Score. Foram filtrados dados das seguintes tabelas: Fontes; Modalidades; Pessoa Física; Movimentos; Pagamentos; Operáveis; 
	![image](https://user-images.githubusercontent.com/62898187/139692376-5567e68d-7221-4a3e-8e9a-013ffee50222.png)


* Aprendizado em trabalhar com layout do Front-End, utilizando Bootstrap 4, CSS e HTML:

	*	Para este projeto, utilizamos Bootstrap 4 e CSS Puro para criar os layouts juntamente com o HTML. A ideia da utilização do Bootstrap foi que existe uma facilidade para se trabalhar com Forms e CheckButtons utilizando este framework. Facilitou e nos deu agilidade na criação de nosso Front-End.

