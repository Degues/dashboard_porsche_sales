# dashboard_porsche_sales
Sobre o Projeto

Este projeto consiste na criação de uma dashboard de vendas da Porsche utilizando HTML, CSS e JavaScript, com foco em análise comercial e apoio à tomada de decisão.

A solução foi desenvolvida utilizando Inteligência Artificial Generativa por meio do ChatGPT e do recurso Canvas, permitindo a criação de uma dashboard interativa com filtros, KPIs e visualizações executivas inspiradas na identidade visual da Porsche.

O dashboard permite explorar dados de vendas por modelo, cidade, ano do veículo e forma de pagamento, apresentando uma visão consolidada de desempenho comercial e faturamento.

1. Perguntas de negócio escolhidas
As perguntas de negócio foram definidas para fornecer uma visão estratégica da operação comercial, equilibrando análises de volume, receita e comportamento de compra.

Perguntas implementadas:

  Quais são os modelos mais vendidos?

  Quais cidades possuem maior volume de vendas?

  Quais cidades geram maior faturamento?

  Quais modelos possuem o maior ticket médio?

  Como as vendas estão distribuídas entre as formas de pagamento?

  Qual modelo é mais popular em cada cidade?

  Por que essas perguntas?

Essas perguntas permitem identificar:

  Os produtos de maior demanda;

  Os mercados geográficos mais relevantes;

  As regiões com maior geração de receita;

  Os veículos com maior valor agregado;

  O comportamento de pagamento dos clientes;
  
  A preferência de modelos em cada localidade.

Com isso, a dashboard entrega uma visão executiva focada tanto em volume quanto em rentabilidade.

2. Prompt utilizado e evolução até a versão final

Prompt inicial

A primeira versão foi gerada utilizando o recurso Canvas do ChatGPT com os seguintes requisitos:

  Dashboard em HTML;

  Filtros por:

  Modelo Porsche;

  Model Year;

  Cidade;

  Forma de Pagamento;

  Perguntas de negócio relacionadas a vendas;

  Referência visual baseada no site oficial da Porsche Brasil;

  Aparência elegante e refinada.

Evolução durante o desenvolvimento

Após a geração inicial foram realizadas diversas melhorias iterativas utilizando IA:

  Evolução visual
  Alteração do tema claro para um tema escuro premium;
  Utilização de cores inspiradas na identidade visual Porsche;
  Ajustes de contraste e legibilidade;
  Refinamento da experiência visual e da organização dos painéis.
  Evolução analítica
  Foi identificado que alguns gráficos apresentavam informações redundantes.

Por isso foram realizadas as seguintes alterações:

  Inclusão do KPI "Cidade Líder em Receita";

  Inclusão do gráfico "Receita por Cidade";

  Remoção do gráfico "Vendas por Model Year";

  Inclusão do gráfico "Ticket Médio por Modelo" em barras verticais;

  Substituição do ranking de formas de pagamento por um gráfico Donut de participação percentual;

  Ajustes nos insights automáticos para manter coerência com os dados exibidos.

  Essas mudanças tornaram a dashboard mais executiva e menos repetitiva visualmente.

3. Tratamento da base de dados
Antes da utilização da Inteligência Artificial, a base passou por um processo de sanitização baseado em um schema fornecido no desafio.

  O schema definiu um pipeline responsável por padronizar e validar os dados antes da etapa de visualização.

  Principais tratamentos realizados

  Padronização dos modelos Porsche;

  Normalização dos anos dos veículos;

  Sanitização dos preços de venda;
  
  Padronização das formas de pagamento;

  Tratamento de cidades e estados;

  Padronização dos status de entrega;

  Sanitização das datas de venda;

  Identificação de registros inválidos.

Além disso, o processo gerou colunas sanitizadas específicas para os principais atributos da base, aumentando a qualidade e a consistência dos dados consumidos pela dashboard.

Durante a análise também foram observados registros com datas ausentes e datas futuras, motivo pelo qual foram priorizadas análises de vendas, faturamento e participação ao invés de análises temporais.

4. Ferramentas de IA utilizadas
ChatGPT

  Utilizado para:

  Definição das perguntas de negócio;

  Evolução dos gráficos;

  Revisão de UX/UI;

  Geração e refinamento do código HTML, CSS e JavaScript;

  Construção dos indicadores executivos.

  ChatGPT Canvas

  Utilizado para:

  Geração da versão inicial da dashboard;

  Iteração visual dos componentes;

  Ajustes estruturais da interface.

Portanto, foram utilizados tanto o ChatGPT quanto o recurso Canvas durante o desenvolvimento do projeto.

5. Dashboard publicada

Repositório GitHub

  https://github.com/Degues/dashboard_porsche_sales

GitHub Pages

  https://SEU-USUARIO.github.io/SEU-REPOSITORIO/

  Tecnologias Utilizadas

  HTML5

  CSS3

  JavaScript (Vanilla JS)

  GitHub / GitHub Pages

  ChatGPT

Autor:

  Dennis Rodrigues

O objetivo deste projeto não foi apenas construir uma dashboard visual, mas demonstrar a utilização de IA Generativa em conjunto com processos de tratamento de dados e análise de negócio para criação de uma solução de Business Intelligence orientada a tomada de decisão.
