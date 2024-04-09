# Especificações do Projeto

Identificação do problema e proposta de solução do ponto de vista do usuário, incluindo a elaboração de diagramas de personas, histórias de usuários e requisitos funcionais e não funcionais.

## Personas

### Sofia Ferreira

+ Idade: 35 anos
+ Ocupação: Mãe e consumidora consciente
+ Necessidades: Deseja entender melhor como seu consumo de energia afeta sua conta de luz e o meio ambiente, pensando no futuro de seus filhos.

### Paula Rodrigues

+ Idade: 45 anos
+ Ocupação: Profissional de marketing e consumidora consciente
+ Necessidades: Está sempre buscando maneiras de viver de forma mais sustentável. Ela deseja aprender e entender melhor como seu consumo de energia contribui para as emissões de CO2 e tomar medidas para reduzi-lo.

### Beatriz Silva

+ Idade: 30 anos
+ Ocupação: Gerente de equipe em uma empresa de tecnologia
+ Necessidades: Monitorar o consumo de energia do escritório e está interessada em encontrar maneiras de reduzir os custos operacionais e as emissões de CO2 da equipe.

### Mariana Leite

+ Idade: 33 anos
+ Ocupação: Técnica de manutenções em uma fábrica.
+ Necessidades: Precisa de uma plataforma que permita inserir informações detalhadas sobre os dispositivos eletrônicos utilizados na fábrica, para uma análise individualizada do consumo de cada equipamento.

### Alane Couto

+ Idade: 40 anos
+ Ocupação: Proprietária de uma pequena empresa de comércio. 
+ Necessidades: Deseja reduzir os custos operacionais e as emissões de CO2 de sua empresa, para maximizar os lucros e demonstrar um compromisso com a sustentabilidade.

### Gilvanilda Dias

+ Idade: 38 anos
+ Ocupação: Diretora de uma empresa de produção
+ Necessidade: Ela está preocupada com os custos operacionais crescentes e deseja encontrar maneiras de reduzir o consumo de energia, os custos e as emissões de CO2 da empresa.

## Histórias de Usuários

Partindo das informações que as Personas apresentaram, chegamos à conclusão das seguintes histórias de usuário relevantes aos problemas identificados.

|Eu como... `Persona`| Quero/Preciso ... `Funcionalidade` |Para ... `Motivo/Valor`                 |
|--------------------|------------------------------------|----------------------------------------|
|Sofia Ferreira  | Inserir detalhes específicos sobre seus dispositivos eletrônicos, como tipo, tempo de uso e potência.    | Para uma análise individualizada do consumo de energia e custo mensal de cada aparelho.               |
|Sofia Ferreira  | Uma ferramenta que informe o custo associado de Co2 com base no meu consumo de energia elétrica.           | Entender como meu consumo afeta diretamente o meio ambiente e tomar medidas para reduzir meu impacto ambiental.               |
|Paula Rodrigues  | Plataforma que forneça informações e dados sobre o impacto ambiental de seu consumo de energia e maneiras de reduzi-lo.           | Aumentar meu conhecimento sobre o consumo de energia e as alternativas para sua redução.               |
|Beatriz Silva  | Inserir informações sobre os dispositivos eletrônicos utilizados pela minha equipe, como quantidade, tipo e tempo de uso.         | Estabelecer metas e métricas para a equipe reduzir o consumo de energia e as emissões de CO2 da empresa.               |
|Mariana Leite  | Obter resultados individuais do consumo de cada dispositivo eletrônico.     | Auxiliar na hora da elaboração de relatórios detalhados à diretoria, onde poderei discriminar as informações de consumo de modo detalhado.  |
|Alane Couto  | Ferramenta que forneça uma conversão individualizada do consumo de energia em emissões de CO2 | Para incluir em sua estratégia de marketing verde e atrair mais clientes.             |
|Gilvanilda Dias  | Visualizar o consumo mensal de energia elétrica da minha empresa associada a cada aparelho e utilização | Gerenciar melhor meus custos operacionais e identificar oportunidades de economia de energia para reduzir despesas.

## Requisitos

Os requisitos são especificações detalhadas das funcionalidades, comportamentos e restrições que o software deve atender para satisfazer as necessidades dos usuários e product owner. Eles descrevem o que o software deve fazer e definem as bases para o seu desenvolvimento e teste.

### Requisitos Funcionais

Os requisitos funcionais têm como objetivo principal descrever as funcionalidades específicas que o sistema deve realizar para atender às necessidades e expectativas dos usuários, fornecendo uma base clara para o desenvolvimento, implementação e teste do software.

|     ID       |     Descrição                                                                                                                                                                     |     Prioridade    |
|--------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------|
|     RF-01    |     O sistema deve permitir uma funcionalidade de cadastro e login aos usuários, para que possam acessar suas informações pessoais.            |     Média          |
|     RF-02    |     O sistema deve permitir ao usuário o cadastramento de aparelhos eletrônicos, onde o usuário poderá fornecer informações quanto ao tipo de aparelho potência, tempo estimado de uso e o valor do kWh da localidade desejada.                                                                                                     |     Alta          |
|     RF-03    |     O sistema deve calcular o consumo do aparelho em kWh por dia ou por mês e o quanto isso implica em preço e valores e exibir para o usuário.                                                                                              |     Alta          |
|     RF-04    |     O sistema deve converter o valor do consumo de energia elétrica em emissão de dióxido de carbono (CO2) e exibir ao usuário.                                                                                                                        |     Alta          |
|     RF-05    |     O sistema deverá fornecer links informativos para recursos adicionais relacionados à eficiência energética                                                                                                               |     Alta          |

### Requisitos não Funcionais

Os requisitos não funcionais são padrões de qualidade do software, como o quão rápido ele deve ser ou o quão simples será a usabilidade (user friendly). Eles não descrevem o que o programa faz, mas sim como ele deve ser feito para ser eficiente e confiável.

|     ID        |     Descrição                                                                               |     Prioridade    |
|---------------|--------------------------------------------------------------------------------------------------------------------------|-------------------|
|     RNF-01    |     A aplicação deve ser publicada em ambiente acessível público na internet.    |     Alta          |
|     RNF-02    |     A aplicação deverá ser responsiva permitindo a visualização em dispositivos diversos de forma adequada.                                                               |     Alta          |
|     RNF-03    |     A aplicação deve ter um bom nível de contrate entre os elementos da tela.                          |     Média         |
|     RNF-04    |     A aplicação deve ser compatível com os navegadores. O site deve ser compatível com os principais navegadores do mercado: Google Chrome, Firefox e Microsoft Edge.                                                                                 |     Alta       |


## Restrições

Restrições são obrigações claras e objetivas do projeto. A tabela a seguir mostra a lista de restrições do projeto.

|     ID        |     Descrição                                                                                           |
|---------------|---------------------------------------------------------------------------------------------------------|
|     RE-01     |     A equipe   não pode subcontratar o desenvolvimento do trabalho.                                     |
|     RE-02     |     O site não pode   conter conhecimentos além daqueles aprendidos durante o semestre.                 |



