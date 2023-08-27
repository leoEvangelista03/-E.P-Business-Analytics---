# E.P | Business Analytics


## Documentação do processo de análise dos dados
O objetivo do projeto é obter novos insights que possam ser utilizados de alguma maneira para evoluir as estratégias de marketing da empresa, melhorar a experiência do cliente e também conhecer melhor o mercado. Para isso, foram obtidos dados de um banco de dados disponível no MySQL e a análise dos dados foi feita em Python e também no Tableau.

### Processo de análise dos dados
#### Obtenção dos dados:
- Os dados estavam disponíveis em um banco no MySQL, sendo assim, foi utilizado o MySQL Workbench para extrair os dados e convertê-los para arquivos de texto (.csv) que depois foram carregados no Python.
- Ferramentas utilizadas: MySQL, MySQL Workbench e Python.

#### Análise Exploratória de Dados - Pt.1:
- Nesta etapa, foi feita uma exploração inicial dos dados, apenas para saber algumas informações básicas como o tipo e formato dos dados, a distribuição deles e se havia dados faltantes, a fim de entender melhor com o que se estava trabalhando.

#### Pré-Processamento dos dados:
- Etapa em que é feita a formatação, conversão, manipulação, limpeza e preparação dos dados em geral.
- Foi necessário pelos seguintes motivos:
- Dados faltantes;
- Dados mal-formatados;
- Dados desnecessários para o fim em que seriam utilizados;
- Dados tipados incorretamente;

#### Engenharia de Atributos:
- Etapa essencial para criação de novas variáveis e tabelas que pudessem ajudar a obter melhores informações a partir dos dados disponíveis.
- Foram criadas novas tabelas como a “investor_data”, onde havia todos os dados a respeito do investidor; a” investment_plus”, onde havia todos os
 dados a respeito do investimento, como a modalidade e categoria; “investor_charact”, onde havia todas as informações à respeito do investidor e seus investimentos;
- Foram criadas novas variáveis como a “age_created”, que representa com que idade o investidor começou a investir com a empresa.

#### Análise Exploratória dos Dados - Pt.2:
- A partir daqui, agora com os dados preparados, o foco da análise se tornou outro: Obter insights, e para isso foram definidas algumas perguntas para guiarem a análise dos dados.

#### Conclusão:
- O objetivo desta etapa é responder às perguntas que foram definidas anteriormente, sendo elas:
- Quais são os cargos das pessoas que mais investem?
- De que canais provêm mais frequentemente os clientes?
- Quando o cliente vem através da indicação de outra pessoa, de certa forma, isso gera uma maior confiança do cliente na empresa. Sendo assim, será que esta confiança influencia o montante investido?
- Quais categorias de projetos são mais investidas?
- Com que idade é que os clientes normalmente começam a investir com a empresa? Essa idade influencia no montante que é investido?


## Conclusão
### Possíveis atitudes que podem ser tomadas em cima do que foi descoberto
- Algumas plataformas como o Facebook e o Youtube podem ser melhor aproveitadas, para isso pode-se oferecer algum tipo de crédito ou bonus para clientes que vierem por meio dessas plataformas, por exemplo;
- Ter algum programa de incentivo para aqueles que indicam o serviço a outras pessoas. Por exemplo, ao indicar alguém, se a pessoa se tornar realmente cliente, a pessoa que indicou recebe um montante em investimentos ou um desconto;
- Fazer mais parcerias com influenciadores (tanto pessoas como páginas), porque além de terem um maior poder de influência, podem atingir uma audiência maior;
- Manter uma página ativa nas redes sociais (como Instagram, Twitter e Facebook), interagindo com o público, publicando com frequência etc;
- Oferecer benefícios para casais, visto que boa parte dos investidores são casados, para incentivar que ambos os envolvidos na relação invistam ou pelo menos invistam mais;
- Criar programas de fidelização para o cliente, como eventuais promoções para clientes mais antigos, por exemplo.

### Outras sugestões e ideias
- Coletar dados a respeito da saída ou não do cliente da empresa (churn);
- Criar um modelo de previsão de churn para evitar que os clientes deixem a
empresa;
- Usar ferramentas como o Google Analytics para analisar o comportamento
dos clientes e como eles interagem com as publicações, para poder gerar
conteúdos com mais engajamento;
- Coletar mais informações sobre os clientes, como salário, por exemplo;
- Criar um sistema de recomendação de portfólio de acordo com o perfil do
cliente.
