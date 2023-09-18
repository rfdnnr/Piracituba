#Nimbus Meteorologia


***Quem?*** 
- Nimbus é uma empresa da área de metereologia que fez parte do "desafio COR", programa de inovação do Centro de Operações da Prefeitura do Rio, e ganhou certificado do órgão com o seu programa Cronos. O sistema, além de ser utilizado pelo órgão da prefeitura, é voltado para o mercado de construção civil, sendo assim, engenheiros, mestres e peões de obra também o utilizam, assim como outras áreas que dependam da situação climática para operar como estaleiros.

***O quê?***
- O sistema "Cronos" da empresa visa, principalmente, prever condições climáticas para planejamento de cronograma de obras além de previsões climáticas em geral. Conectados a datas e horários e locais, o histórico de dados liberados são: temperatura, direção e velocidade do vento, visibilidade, umidade e outros. 

***Onde?*** 
- Iniciada no Rio, a empresa já expandiu para mais estados do Sudeste e está iniciando projetos em Coritiba. Dentro do sistema, os dados serão apresentados em uma dashboard com mapa interativo, gráficos e tabelas conectados a datas que o usuário desejar. Além disso, o sistema pode ser acessado em qualquer lugar, através de computadores e smartphones conectados à internet.

***Como?*** 
- O sistema terá como entrada: dados de radar, raios, estações metereológicas e aspectos da obra. Com essas informações, o sistema usa cálculos físicos e matemáticos, para prever condições metereológicas. Além disso, o usuário tem acesso ao sistema através de seu navegador e pode exportar esses dados para relatórios e laudos;
O cliente tem acesso a uma API em que escolhe suas preferências de localização e janela de tempo e exporta o histórico de dados no formato de arquivo de tabela.

***Quando?*** 
- Com o uso variando de acordo com o usuário, em geral, o sistema é utilizado ao inicio de uma obra e no decorrer dela, ou com outros fins que demandem uso diário ou semanal. 
Os dados tem um histórico diário e semanal, e os dados de deslocamento de tempestades podem ser vistos em tempo real.

***Por quê?***
- A empresa entende que "controlar a natureza é impossível, mas entendê-la é essencial", por isso, ela fornece serviços de metereologia para prefeituras e para o mercado de construção civil, ajudando na gestão de risco climático, na redução de prejuízos com  menos perda de materiais, planejamento e cronograma mais eficientes, maior segurança dos trabalhadores e aumento da produtividade.

***Propósito do sistema:***
- Juntar os dados necessários fornecidos ao sistema para que, retorne ao usuário de forma menos complexa e centralizada as informações que deseja, visando atender os pontos de venda centrais da empresa.
Isso, sendo feito através de uma nova página e seus dados, com atenção ao usuário mobile, visando a legibilidade e estética.



***Requisitos Funcionais:***

- [RF-1]: O *sistema* deve ter, na parte superior da janela, um formulário onde o usuário digita os limites de tempo, variável meteorológica e ponto de monitoramento.

- [RF-2]: O *sistema* deve oferecer um gráfico dinâmico que mostra: direção dos ventos, velocidades e rajadas; juntos ao intervalo de tempo submetido no formulário.

- [RF-3]: O *sistema* deve permitir baixar uma tabela com os dados submetidos no formulário e ser exportável para CSV, PDF e PNG.

- [RF-4]: O *sistema* deve apresentar os dados de acordo com o desejo do usuário no formulário.

- [RF-5]: O *sistema* deve oferecer, no canto inferior esquerdo, um mapa interativo onde o usuário pode selecionar um marcador, que representa uma estação meteorológica, com um clique único ou selecionar uma ou várias estações com a criação de um polígono com o mouse.

- [RF-6]: O *sistema* deve preencher o mapa com cores de acordo com a criticidade do nível de chuva.


***Requisitos não funcionais:***

- [RNF-1]: O *sistema* deve ser desenvolvido com React.

- [RNF-2]: O *sistema* deve estar disponível na web.

- [RNF-3]: O *sistema* deve estar disponível 24 horas por dia.

- [RNF-4]: O *sistema* deve oferecer adaptação intuitiva para mobile.

- [RNF-5]: O *sistema* deve exibir uma tabela com um design de fácil legibilidade e esteticamente otimizada.

- [RNF-6]: O *sistema* deve ser versionado (no projeto será feito através do GitHub).

- [RNF-7]: O *sistema* deve possuir um código de fácil manutenção.

- [RNF-8]: O *sistema* deve ser responsivo.
