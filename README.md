# PROJETO FINAL
Projeto final do curso técnico de informática. 

#Sumário

###1	ORIENTANDA<br/>
Juliana Rangel Roque<br/>

###2	ORIENTADORES<br/>
Moisés Omenna (Orientador)<br/>
Carlos (Co-orientador)<br/>
Fancisco Boldt (Co-orientador)<br/>

###3 TÍTULO DO PROJETO<br/>
CACWeb – Sistema de Interface Web do Centro de Atendimento ao 
Cidadão <br/>

###4 RESUMO DO PROJETO<br/>
O Centro  de  apoio  ao  cidadão  (CAC) é  uma  instituição  filantrópica sem  fins  lucrativos  que  surgiu  em  outubro  de  2001  devido  à necessidade  surgida  pelo  crescimento  da  epidemia  da  AIDS no estado  do  Espírito  Santo,  e  desde  então  faz  acompanhamento  de pacientes    portadores    de    HIV/AIDS,    além    de    ações    para conscientização da população.  
Entretanto,  os  registros  de  informações  e  acompanhamento  dos pacientes  ainda  ocorrem  de  maneira  manual,  além  disto,  existe  a necessidade  de  uma  melhoria  qual  melhoria?  que  possa  facilitar  o acesso de informações confiáveis sobre o HIV/AIDS pelas pessoas em geral. 
Neste projeto, desenvolveremos  um sistema  web  por meio  do  qual a  população  possa  obter  informações  confiáveis  e  a  equipe  CAC possa realizar cadastros de pacientes, voluntários, programas e ações.  Com  isso,  automatizar  o  registro  das  atividades  realizadas  no cotidiano do CAC. 
Por meio da  interface usuários comuns  (sem cadastro) poderão ter 
acesso a informações e orientação a respeito do HIV/AIDS. Também será permitido o cadastro de usuários que serão subdivididos em: equipe CAC, voluntários, pacientes. 
A equipe CAC poderá gerar relatórios dos programas e das ações realizadas além de gerar o acompanhamento dos pacientes. Cabe 
aos voluntários realizar o cadastro das ações e dados coletados nas mesmas para a coordenação conseguir gerar relatórios mensais, trimestrais e anuais.  
Como resultado espera-se que o CAC Web torne as atividades automatizadas e facilite o acompanhamento dos pacientes, ajude 
na organização e controle dos voluntários e equipe. Gere relatórios sobre os pacientes, voluntários, dos projetos e das ações. 
Além disso, possibilitar envio de mailing com informativos de campanhas e ações a serem realizadas.  

###5 INTRODUÇÃO E JUSTIFICATIVA<br/>


###6 PROBLEMA DA PESQUISA<br/>

###7 OBJETIVOS DE PESQUISA<br/>
####7.1 OBJETIVO GERAL

Desenvolver  um  sistema  web  para  automatizar  o  registro  das  atividades do Centro de Acompanhamento ao Cidadão (CAC) e facilitar o acesso da população a informações confiáveis sobre HIV/AIDS.<br>  

####7.2 OBJETIVO ESPECÍFICO
- Analisar os requisitos; 
- Modelar o banco de dados; 
- Implementar o banco de dados; 
- Implementar o sistema com os módulos A, B, C...
- Desenvolver relatórios gerenciais;  
-  Desenvolver  o  site  CAC  para  facilitar  a  busca  de  dados  e  organização  dos mesmos

###8 FUNDAMENTAÇÃO TEÓRICA<br/>

###9 METODOLOGIA<br/>

###10 RESULTADOS E IMPACTOS ESPERADOS<br/>

###11 RESULTADOS E IMPACTOS ESPERADOS<br/>

###12 CRONOGRAMA<br/>

###3	INTRODUÇÃO E MOTIVAÇAO<br>
Este documento contém a especificação do projeto do banco de dados do CAC, temática a qual foi escolhida para o desenvolvimento do projeto final do curso de informática do Ifes campus-serra.<br>

Com o aumenta da epidemia da AIDS 
Com o crescimento da epidemia da AIDS e a necessidade de se fazer algo mais para as pessoas vivendo com HIV/AIDS, surge no Outono de 2001 o C.A.C. - Centro de Apoio ao Cidadão, sendo uma Instituição Filantrópica da Sociedade Civil, de Fins Não Econômicos, pertencente ao Terceiro Setor enquanto ONG, de Utilidade Pública, inserida com o código de atividade principal de Associação de Defesa de Direitos Sociais, que busca vias e formas para sustentar o tratamento das pessoas acometidas com o vírus HIV/AIDS, no intuito de fornecer aos mesmos, informações, auxílios, ou simplesmente um apoio social e familiar para o enfrentamento da doença. Com a finalidade de com isso fazer da solidariedade, não uma utopia, mas um gesto de amor e doação para com o próximo, em valorização da vida humana e da cidadania.  

Trabalhando com doações, parcerias e serviços técnicos voluntários, o 

B – Problema (2 parágrafos) 

O CAC já possui um domínio registrado e permanecem pagando-o, no entanto ainda não conseguiram colocar em prática algumas ideias devido à atuação ocorrer apenas através de doações, parcerias e serviço voluntário. 

Existe a necessidade de um site que possa ser usado como ferramenta para acesso de informações e, além disso, um sistema web com o qual possam realizar o cadastro de pacientes, voluntários, ações além de gerar relatórios, pois estas atividades até hoje são feitas de maneira manual. 

C – Propósito 

A proposta inicial é o desenvolvimento de um sistema web com o qual possam ser realizados cadastros de pacientes, voluntários, equipe CAC, programas, ações. Com isso, um melhor acompanhamento dos dados dos pacientes e dos resultados das ações e dos programas.
###4	MINI-MUNDO<br>
Descrever o mini-mundo. Não deve ser maior do que 30 linhas <br>

###5	RASCUNHOS BÁSICOS DA INTERFACE (MOCKUPS)<br>
neste ponto a codificação não e necessária, somente as ideias de telas devem ser criadas, o princípio aqui é pensar na criação da interface para identificar possíveis informações a serem armazenadas ou descartadas <br>

Sugestão: https://balsamiq.com/products/mockups/<br>

![Alt text](https://github.com/discipbd1/trab01/blob/master/balsamiq.png?raw=true "Title")


###6	MODELO CONCEITUAL<br>
    6.1 NOTACAO ENTIDADE RELACIONAMENTO
![Alt text](https://github.com/discipbd1/trab01/blob/master/sample_MC.png?raw=true "Modelo Conceitual")
    
    6.2 NOTACAO UML (Caso esteja fazendo a disciplina de analise)

####5.1 Validação do Modelo Conceitual
    [Grupo01]: [Nomes dos que participaram na avaliação]
    [Grupo02]: [Nomes dos que participaram na avaliação]

####5.2 DECISÕES DE PROJETO
    [atributo]: [descrição da decisão]
    
    EXEMPLO:
    a) Campo endereço: em nosso projeto optamos por um campo multivalorado e composto, pois a empresa 
    pode possuir para cada departamento mais de uma localização... 
    b) justifique!

####5.3 DESCRIÇÃO DOS DADOS 
    [objeto]: [descrição do objeto]
    
    EXEMPLO:
    CLIENTE: Tabela que armazena as informações relativas ao cliente<br>
    CPF: campo que armazena o número de Cadastro de Pessoa Física para cada cliente da empresa.<br>


###6	MODELO LÓGICO<br>
###7	MODELO FÍSICO<br>

        Entrega até este ponto em 25/10/2016
        
        
###8	INSERT APLICADO NAS TABELAS DO BANCO DE DADOS<br>
####8.1 DETALHAMENTO DAS INFORMAÇÕES
        Detalhamento sobre as informações e processo de obtenção ou geração dos dados.
        Referenciar todas as fontes referentes a :
        a) obtenção dos dados
        b) obtenção de códigos reutilizados
        c) fontes de estudo para desenvolvimento do projeto
        
####8.2 INCLUSÃO DO SCRIPT PARA CRIAÇÃO DE TABELA E INSERÇÃO DOS DADOS
        a) inclusão das instruções para criação das tabelas e estruturas de amazenamento do BD
        b) inclusão das instruções de inserção dos dados nas referidas tabelas
        c) inclusão das instruções para execução de outros procedimentos necessários


        Entrega até este ponto em 01/11/2016
        
###9	TABELAS E PRINCIPAIS CONSULTAS<br>
OBS: Incluir para cada tópico as instruções SQL + imagens (print da tela) mostrando os resultados.<br>
####9.1	CONSULTAS DAS TABELAS COM TODOS OS DADOS INSERIDOS (Todas) <br>
####9.2	CONSULTAS DAS TABELAS COM FILTROS WHERE (Mínimo 3) <br>
####9.3	CONSULTAS QUE USAM OPERADORES LÓGICOS, ARITMÉTICOS E CAMPOS RENOMEADOS (Mínimo 2)<br>
####9.4	CONSULTAS QUE USAM OPERADORES LIKE (Mínimo 3)  <br>
####9.5	ATUALIZAÇÃO E EXCLUSÃO DE DADOS (Mínimo 6)<br>
####9.6	CONSULTAS COM JUNÇÃO (Todas Junções)<br>
####9.7	CONSULTAS COM GROUP BY (Mínimo 5)<br>
        Entrega até este ponto em 08/11/2016
        
####9.8	CONSULTAS COM LEFT E RIGHT JOIN (Mínimo 4) <br>
####9.9	CONSULTAS COM SELF JOIN (todas) E VIEW (mais importantes) <br>
####9.10	SUBCONSULTAS (Mínimo 3) <br>
###10	ATUALIZAÇÃO DA DOCUMENTAÇÃO DOS SLIDES<br>
###11	DIFICULDADES ENCONTRADAS PELO GRUPO<br>

        Entrega final em 23/11/2016
###12  FORMATACAO NO GIT: https://help.github.com/articles/basic-writing-and-formatting-syntax/




