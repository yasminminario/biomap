# Artefato 1: Ideação

## 1. Título: Biomap

## 2. Objetivo do Projeto

&nbsp;&nbsp;&nbsp;&nbsp;O projeto busca resolver um problema comum: a falta de informações claras e fáceis de usar sobre as áreas verdes nas cidades. Isso dificulta que a população participe de decisões importantes sobre o ambiente urbano, pois os dados são muito técnicos. A ferramenta foi pensada para ajudar moradores, estudantes, ONGs e até mesmo as prefeituras a entenderem melhor a cidade. Para isso, a Inteligência Artificial é a peça central. Será usado um modelo de Rede Neural Convolucional que funciona como um "analista digital": ele aprende a olhar para fotos de satélite e a identificar, ponto a ponto, o que é vegetação, construção ou água, criando automaticamente mapas detalhados e fáceis de interpretar.

## 3. Descrição do Projeto

### 3.1. Escopo da Solução

<div align="center">
  <sub>Figura X - Matriz Faz e Não faz </sub>
  <br><br>
  <img src="assets/biomap_faznaofaz.png" alt="Matriz Faz e Não faz" width="100%">
  <br><br>
  <sup>Fonte: Material produzido pela autora (2025)</sup>
</div>

### 3.2. Problema do Público-Alvo

&nbsp;&nbsp;&nbsp;&nbsp;Embora o problema central seja a barreira de acesso à informação, a forma como essa dificuldade se manifesta varia. Cada segmento do público-alvo enfrenta desafios e dores distintas que justificam a necessidade de uma solução versátil como a proposta.

#### 3.2.1. Estudantes e Pesquisadores

&nbsp;&nbsp;&nbsp;&nbsp;Estudantes de áreas como Gestão Ambiental, Urbanismo, Geografia e Biologia enfrentam uma grande dificuldade para obter dados quantitativos e históricos para seus trabalhos acadêmicos. Eles necessitam de uma base de dados que lhes permita analisar tendências, comparar a evolução de diferentes bairros e fundamentar suas pesquisas com evidências concretas. A busca por esses dados hoje é um processo manual, demorado e frustrante, que envolve garimpar portais governamentais e lidar com formatos de arquivo complexos. Alguns estudantes foram entrevistados e um deles, Cauê Tavares Cabral Jorge, estudante de Gestão Ambiental, deu o seguinte relato:

    "Como estudante de Gestão Ambiental, uma das minhas maiores frustrações é a dificuldade de encontrar dados que vão além do óbvio. É fácil ver um parque no mapa, mas é quase impossível achar informações acessíveis que mostrem a saúde real daquela vegetação ou como a mancha verde do meu bairro mudou nos últimos cinco anos. Os dados existem, mas estão dispersos e em formatos muito técnicos para um trabalho rápido e prático."

#### 3.2.2. Para ONGs Ambientais e Coletivos de Bairro

&nbsp;&nbsp;&nbsp;&nbsp;Organizações não governamentais e grupos de moradores engajados dependem de evidências para fortalecer suas ações de advocacia e conscientização. A "dor" desse público é a falta de ferramentas para provar suas teses. Eles podem perceber que uma área está sendo desmatada ou que seu bairro sofre com altas temperaturas, mas não conseguem apresentar um relatório com dados claros para a prefeitura, para a mídia ou para potenciais doadores. A necessidade deles é por uma plataforma que transforme suas percepções em argumentos visuais e quantitativos, ajudando a direcionar a criação de projetos ambientais e a mobilizar a comunidade.

#### 3.2.3. Para Gestores Público

&nbsp;&nbsp;&nbsp;&nbsp;Embora possam ter mais acesso aos dados brutos, os técnicos e gestores de secretarias municipais (como a do Verde e Meio Ambiente) enfrentam desafios de eficiência e comunicação. O processo para gerar um único mapa de análise de vegetação pode ser demorado e exigir softwares caros e equipes especializadas. Além disso, há uma grande dificuldade em comunicar o progresso das políticas ambientais para o público geral de forma transparente e compreensível. Eles precisam de uma solução que otimize o tempo de análise e que gere dashboards e visualizações claras para prestação de contas e para o planejamento estratégico de novas intervenções urbanas.

### 3.3. Proposta de Valor com IA

<div align="center">
  <sub>Figura X - Canvas de Proposta de Valor </sub>
  <br><br>
  <img src="assets/biomap_vpc.png" alt="Canvas de Proposta de Valor" width="100%">
  <br><br>
  <sup>Fonte: Material produzido pela autora (2025)</sup>
</div>

### 3.4. Impacto Esperado

&nbsp;&nbsp;&nbsp;&nbsp;O impacto esperado do Biomap está centrado na democratização do acesso à informação ambiental urbana. Ao fornecer evidências visuais e quantitativas de forma acessível, espera-se que a plataforma capacite diversos públicos interessados na causa ambiental, como ONGs e estudantes, oferecendo-lhes uma base sólida para suas pesquisas ou ações de advocacia, por exemplo. A consequência dessa capacitação é o fomento de um debate público mais qualificado sobre qualidade ambiental no cenário urbano. Assim, o sucesso do projeto será medido por sua utilidade prática e sua contribuição para cidades mais sustentáveis.

### 3.5. Relevância e Atualidade

&nbsp;&nbsp;&nbsp;&nbsp;A relevância do Biomap está inserida no contexto de um dos maiores desafios do século XXI: a rápida e contínua urbanização global. As cidades, que já abrigam mais da metade da população mundial, continuam a se expandir, e no Brasil, essa realidade é ainda mais acentuada, com mais de 85% da população vivendo em áreas urbanas, segundo dados do IBGE [[1]](#referências) [[2]](#referências). Esse crescimento, embora represente desenvolvimento, frequentemente ocorre de forma desordenada, exercendo uma imensa pressão sobre os ecossistemas naturais. A consequência direta é a impermeabilização do solo e a supressão de áreas verdes, que são substituídas por concreto e asfalto, criando um cenário urbano mais vulnerável e menos saudável para seus habitantes.

&nbsp;&nbsp;&nbsp;&nbsp;A diminuição da cobertura vegetal nas cidades não é um problema estético, mas uma questão de saúde pública e resiliência climática. A Sociedade Brasileira de Arborização Urbana (Sbau) recomenda um mínimo de 15m² de área verde por habitante, um índice que muitas metrópoles brasileiras lutam para atingir [[3]](#referências). A arborização urbana é um dos serviços ecossistêmicos mais eficientes: segundo um estudo da revista científica Nature Communications, árvores pode reduzir a temperatura das cidades em até 12°C, combatendo diretamente o fenômeno das ilhas de calor [[4]](#referências). Além disso, a vegetação ajuda na drenagem da água da chuva, reduzindo o risco de enchentes, e está diretamente associada à melhoria da saúde mental e física da população, incentivando a prática de atividades físicas e reduzindo o estresse [[5]](#referências).

&nbsp;&nbsp;&nbsp;&nbsp;Nesse cenário, a capacidade de monitorar, analisar e gerir a infraestrutura verde torna-se uma prioridade estratégica, mas é aqui que se encontra o problema atual. Os métodos tradicionais de mapeamento são caros, lentos e muitas vezes não acompanham a dinâmica das cidades. A relevância e a atualidade do Biomap emergem exatamente para preencher essa lacuna. O projeto utiliza tecnologias atuais e acessíveis, como os dados abertos de satélites e a Inteligência Artificial, para criar uma solução ágil e de baixo custo. A proposta não é apenas gerar dados, mas democratizá-los, oferecendo uma ferramenta que permite a qualquer cidadão, ONG ou gestor público entender e agir sobre a realidade ambiental de seu território, justificando sua importância como um instrumento para a construção de cidades mais transparentes e sustentáveis.

## 4. Análise de Mercado

### 4.1. Design Research Methodology (DRM)

&nbsp;&nbsp;&nbsp;&nbsp;Foi feito uma breve pesquisa de mercado utilizando a metodologia DRM com objetivo de guiar o desenvolvimento do projeto Biomap de forma estruturada, garantindo que a solução proposta seja relevante, bem fundamentada e validada de acordo com as necessidades do setor e do público-alvo. O processo seguirá quatro etapas principais: Setor, PEsquisa, Hipótese e Validação.

#### 4.1.1. Setor (Definição de Objetivo e Escopo)
&nbsp;&nbsp;&nbsp;&nbsp;Nesta primeira fase, o objetivo é delimitar o universo da pesquisa, estabelecendo fronteiras para o projeto.

- Objetivo Geral: O objetivo central da pesquisa é investigar como a aplicação de Inteligência Artificial e dados de sensoriamento remoto pode democratizar o acesso à informação ambiental urbana, capacitando atores da sociedade civil e melhorando a transparência na gestão pública.

- Escopo do Setor: O projeto se insere na intersecção de três grandes setores: Tecnologia Cívica (Civic Tech), que usa a tecnologia para fortalecer a cidadania; Geoprocessamento e Sensoriamento Remoto, que lida com a análise de dados espaciais; e Sustentabilidade Urbana, focada na qualidade ambiental das cidades.

- Delimitação: A solução se concentrará na análise de infraestrutura verde em áreas urbanas no contexto brasileiro. Serão utilizadas exclusivamente imagens de satélite de fontes públicas e gratuitas (como o programa Sentinel). Estão fora do escopo inicial a análise de áreas rurais/agrícolas, o monitoramento de fauna, a análise de poluição atmosférica/hídrica e o uso de imagens de fontes privadas ou de drones.

#### 4.1.2. Pesquisa (Mapeamento do Setor)

&nbsp;&nbsp;&nbsp;&nbsp;Essa etapa consiste em uma investigação do cenário atual para entender os atores, as ferramentas existentes e as lacunas que o Biomap pode preencher.

##### Atores Envolvidos

- Órgãos Públicos: Secretarias Municipais do Verde e Meio Ambiente, de Urbanismo, subprefeituras.

- Sociedade Civil Organizada: ONGs ambientais de grande porte (ex: SOS Mata Atlântica, WWF Brasil) e coletivos de bairro focados em pautas locais.

- Comunidade Acadêmica: Universidades e institutos de pesquisa (INPE, Embrapa Territorial) que produzem conhecimento sobre o tema.

&nbsp;&nbsp;&nbsp;&nbsp;Para aprofundar o entendimento das dores, foram realizadas conversas iniciais com atores do setor, como [Ex: Cauê Tavares Cabral Jorge e Gyovanna Bevenuto, estudantes de Gestão Ambiental na Universidade de São Paulo].

*colocar quotes aqui*

##### Soluções existentes

- Publicações Científicas: Artigos que apresentam análises específicas de uma área, mas que não são ferramentas contínuas ou interativas.

- Portais Governamentais (Ex: GeoSampa): O GeoSampa é o portal oficial de dados geoespaciais da cidade de São Paulo. Embora seja uma fonte de dados oficial, ele apresenta barreiras significativas. Primeiramente, sua atuação é restrita ao município de São Paulo, não sendo uma solução escalável para outras cidades. Além disso, a experiência de usuário na plataforma é considerada pouco intuitiva e complexa, com uma interface datada que exige um esforço considerável do usuário apenas para encontrar, entender e baixar as camadas de dados desejadas. Ele funciona mais como um repositório de dados brutos do que como uma ferramenta de análise para o público geral.

- Softwares SIG Profissionais (Ex: ArcGIS e QGIS): Estas são as ferramentas padrão do mercado para análise geoespacial.

  - ArcGIS: É um software extremamente poderoso, capaz de realizar análises complexas e produzir mapas de altíssimo nível. Sua principal barreira, no entanto, é o custo, com licenças comerciais que o tornam financeiramente inviável para estudantes, ONGs, coletivos e cidadãos comuns.

  - QGIS: É a alternativa de código aberto mais conhecida ao ArcGIS. Embora seja gratuito, ele impõe duas grandes barreiras. A primeira é a instalação e configuração, um processo que pode ser confuso para usuários não técnicos, com múltiplos instaladores e componentes que, por vezes, não resultam em um programa facilmente localizável no sistema. A segunda e maior barreira é sua curva de aprendizado extremamente íngreme. Sua interface é densa, repleta de ferramentas especializadas, e exige um conhecimento prévio significativo em cartografia e geoprocessamento para ser utilizada de forma eficaz.

&nbsp;&nbsp;&nbsp;&nbsp;A principal lacuna identificada é a ausência de uma ferramenta que ocupe o meio-termo entre a complexidade dos softwares SIG profissionais e a limitação dos portais de dados. É precisamente nesta lacuna que a Inteligência Artificial se torna a tecnologia chave. Falta uma solução que empregue modelos de IA para realizar o trabalho pesado da análise de dados, automatizando tarefas como a classificação de cobertura do solo e o cálculo de NDVI, para entregar ao usuário final não especializado um resultado já processado, visual e intuitivo via web.

#### 4.1.3 Hipótese (Formulação de Modelos e Ferramentas)

&nbsp;&nbsp;&nbsp;&nbsp;Com base na pesquisa, foi formulada uma hipótese clara sobre como uma nova solução pode gerar valor.

- Hipótese: "Se for desenvolvida uma plataforma web de código aberto que automatiza a análise de dados de satélite com Inteligência Artificial, então estudantes, ONGs e gestores públicos conseguirão extrair informações sobre o status ambiental urbano de forma rápida e intuitiva, capacitando-os a tomar decisões e a participar do debate público com mais embasamento."

- Modelo da Solução Proposta: Para testar essa hipótese, propõe-se o desenvolvimento de uma plataforma web composta por:

  - Módulo de Aquisição de Dados: Integração com o Google Earth Engine para acesso ao acervo do satélite Sentinel-2.

  - Módulo de IA: Um modelo de Rede Neural Convolucional para realizar a segmentação semântica da cobertura do solo.

  - Módulo de Análise: Funções para cálculo de NDVI e detecção de mudanças temporais.

  - Módulo de Visualização: Um dashboard interativo com mapas, filtros por região e capacidade de exportação de dados.

#### 4.1.4 Validação (Plano de Teste da Hipótese)

&nbsp;&nbsp;&nbsp;&nbsp;A fase final da DRM se concentra em delinear o plano para testar a hipótese do projeto, garantindo que a solução atenda a uma necessidade existente antes do desenvolvimento começar.

- Verificação do Problema: O primeiro passo do plano é aprofundar e confirmar empiricamente as lacunas e "dores" identificadas na fase de Pesquisa. Isso será feito por meio de conversas com o público-alvo, focadas em seus processos de trabalho e desafios atuais, sem apresentar a solução proposta para evitar vieses. Essa etapa já foi iniciado.

- Teste do Conceito da Solução: Apenas com as premissas do problema confirmadas, o passo seguinte é testar a aceitação do conceito do Biomap. O plano envolve a criação de um protótipo de baixa fidelidade (wireframes ou mockups interativos) para apresentar aos perfis de usuário. O objetivo aqui é avaliar se a proposta de valor é clara e se as funcionalidades centrais são percebidas como relevantes para resolver os problemas discutidos.

- Ciclo de Aprendizado: Os insights coletados em ambas as etapas alimentarão o refinamento da hipótese e do escopo do projeto. Este ciclo garante que o desenvolvimento futuro da plataforma esteja firmemente alinhado com as necessidades validadas dos usuários.

### 4.2. Customer Development

&nbsp;&nbsp;&nbsp;&nbsp;De forma a especificar ainda mais a etapa de "Validação" do DRM, a metodologia de Customer Development será aplicada para garantir que o projeto seja desenvolvido com base em necessidades reais do mercado. O processo se concentrará nas duas fases iniciais da metodologia:

#### 4.2.1. Customer Discovery

&nbsp;&nbsp;&nbsp;&nbsp;O objetivo desta fase é validar a hipótese do problema. A meta é descobrir se as "dores", necessidades e tarefas que identificamos na fase de pesquisa da DRM são reais, significativas e compartilhadas por um segmento de público.

- Método: Realização de entrevistas qualitativas e abertas com o público-alvo (estudantes, membros de ONGs, etc.). As conversas serão focadas em entender suas experiências passadas e presentes, e, novamente, sem apresentar a ideia da solução para não enviesar as respostas.

- Hipóteses a serem testadas:

  - H1 (Hipótese da Dor): Estudantes e ONGs realmente sentem que a dificuldade de acesso a dados ambientais de qualidade é um obstáculo significativo que prejudica a qualidade e a agilidade de seus trabalhos.

  - H2 (Hipótese da Ferramenta Atual): As soluções existentes são percebidas como inadequadas pela maioria deste público, seja pelo custo, pela complexidade técnica ou pela limitação de funcionalidades.

  - H3 (Hipótese do Desejo): Existe um desejo por uma solução que vá além de um mapa estático, oferecendo análises mais profundas como a saúde da vegetação e a evolução temporal.

#### 4.2.2. Customer Validation

&nbsp;&nbsp;&nbsp;&nbsp;Com as hipóteses do problema validadas, esta etapa busca validar a hipótese da solução. O objetivo é testar se o Biomap, como foi entitulado, é a solução correta e desejável para resolver os problemas identificados.

- Método: Desenvolvimento de um Protótipo de Baixa Fidelidade para ser apresentado em uma nova rodada de conversas com o público-alvo.

- Hipóteses a serem testadas:

  - H4 (Hipótese do Valor): Ao ver o protótipo, os usuários percebem o valor de uma plataforma que automatiza a análise de imagens de satélite com IA e a apresenta de forma intuitiva.

  - H5 (Hipótese da Usabilidade): Os usuários conseguem entender a proposta do dashboard interativo e navegar pelas funcionalidades principais sem necessidade de um treinamento extensivo.

  - H6 (Hipótese da Adoção): Os usuários expressam um interesse genuíno em utilizar a ferramenta em seus projetos reais, confirmando a adequação da solução ao mercado.

### 4.3. Análise TAM, SAM, SOM

<div align="center">
  <sub>Figura X - Canvas do TAM, SAM, SOM </sub>
  <br><br>
  <img src="assets/biomap_tamsamsom.png" alt="Matriz Faz e Não faz" width="100%">
  <br><br>
  <sup>Fonte: Material produzido pela autora (2025)</sup>
</div>

#### 4.3.1. TAM (Total Addressable Market)

O TAM para o Biomap representa o mercado máximo de usuários que poderiam, teoricamente, se beneficiar de uma ferramenta de análise de dados ambientais urbanos. Este mercado é global e inclui qualquer indivíduo ou organização envolvida com sustentabilidade urbana, planejamento de cidades e pesquisa ambiental. Isso inclui a seguinte estimativa de público:

- Estudantes e Pesquisadores: Milhões de estudantes universitários em cursos de Urbanismo, Arquitetura, Biologia, Gestão Ambiental e Geografia em todo o mundo.

- Organizações da Sociedade Civil: Dezenas de milhares de ONGs, coletivos e associações de bairro com foco ambiental em escala global.

- Setor Público: Centenas de milhares de municípios globalmente que possuem departamentos de planejamento urbano e meio ambiente.

#### 4.3.2. SAM (Serviceable Available Market)

O SAM é a parte do TAM que o Biomap pode realisticamente atender, considerando as barreiras iniciais de idioma (português) e contexto (cidades brasileiras). Nosso mercado acessível são os atores que atuam no Brasil. Isso inclui a seguinte estimativa de público:

- Estudantes e Pesquisadores no Brasil: Número total de estudantes matriculados em cursos de graduação e pós-graduação correlatos no país.

- ONGs no Brasil: Número de Organizações da Sociedade Civil ativas com foco em meio ambiente e desenvolvimento urbano no país.

- Setor Público no Brasil: Número de municípios brasileiros, especialmente os de médio e grande porte, que possuem secretarias de meio ambiente e urbanismo.

#### 4.3.3. SOM (Serviceable Obtainable Market)

O SOM representa a meta de adoção inicial e realista para os primeiros períodos do projeto. É o público que será engajado diretamente através de esforços de divulgação, focando primariamente no ecossistema de São Paulo. Isso inclui a seguinte estimativa de público:

- Comunidade Acadêmica Local: Estudantes e professores do Inteli e de outras universidades em São Paulo (como USP, Mackenzie, etc.) para utilizar a ferramenta em projetos e trabalhos acadêmicos.

- ONGs e Coletivos Parceiros: ONGs ou coletivos de bairro em São Paulo que foram entrevistados na fase de validação, para que se tornem os primeiros usuários e forneçam feedback contínuo.

- Contatos no Setor Público: Secretarias municipais de São Paulo, buscando um projeto piloto ou o uso da plataforma para uma análise específica.

## 5. Público-Alvo

### 5.1. Persona 1: [Nome Fictício da Persona]
* **Dados demográficos e contextuais:** 
* **Perfil tecnológico e educacional:** 
* **Dores e Problemas:** 
* **Objetivos:** 
* **Adequação da Solução:** 

### 5.2. Persona 2: [Nome Fictício da Persona]
* **Dados demográficos e contextuais:** 
* **Perfil tecnológico e educacional:** 
* **Dores e Problemas:** 
* **Objetivos:** 
* **Adequação da Solução:**

### 5.3. Persona 3: [Nome Fictício da Persona]
* **Dados demográficos e contextuais:** 
* **Perfil tecnológico e educacional:** 
* **Dores e Problemas:** 
* **Objetivos:** 
* **Adequação da Solução:**

## 6. Requisitos do Sistema

### 6.1 Requisitos Funcionais
| Código | Descrição da Funcionalidade | Prioridade | Observações Técnicas Relevantes |
| :--- | :--- | :--- | :--- |
| RF01   |                              |            |                                 |
| RF02   |                              |            |                                 |
| RF03   |                              |            |                                 |
| RF04   |                              |            |                                 |
| RF05   |                              |            |                                 |
| RF06   |                              |            |                                 |

### 6.2 Requisitos Não Funcionais
| Código | Descrição Clara do Requisito | Tipo do Requisito | Observações Complementares |
| :--- | :--- | :--- | :--- |
| RNF01  |                              |                   |                            |
| RNF02  |                              |                   |                            |
| RNF03  |                              |                   |                            |
| RNF04  |                              |                   |                            |


## 7. Componente de Inteligência Artificial

### 7.1 Técnica de IA Aplicada
### 7.2 Justificativa da Técnica
### 7.3 Métricas de Avaliação


## 8. Orçamento Estimado (Se aplicável)
| Item de Custo | Descrição | Custo Estimado (R$) |
| :--- | :--- | :--- |
| Infraestrutura de Hospedagem | Custos com serviços de nuvem (ex: Google Cloud, AWS). | |
| Licenciamento de APIs/Modelos | Se aplicável, custo de uso de APIs de terceiros. | |
| Outros Custos Operacionais | Custos com domínios, ferramentas, etc. | |
| **Total Estimado** | **Soma de todos os custos.** | **R$ 0,00** |

## Referências

[1] - https://brasil.un.org/pt-br/188520-onu-habitat-popula%C3%A7%C3%A3o-mundial-ser%C3%A1-68-urbana-at%C3%A9-2050

[2] - https://agenciadenoticias.ibge.gov.br/agencia-noticias/2012-agencia-de-noticias/noticias/41901-censo-2022-87-da-populacao-brasileira-vive-em-areas-urbanas

[3] - https://www.al.sp.gov.br/noticia/?id=306090

[4] - https://revistagalileu.globo.com/Um-So-Planeta/noticia/2021/11/arvores-podem-reduzir-em-ate-12c-temperatura-das-cidades-diz-estudo.html

[5] - https://g1.globo.com/ms/mato-grosso-do-sul/cidade-das-arvores/noticia/2023/11/29/presenca-de-arvores-ajuda-na-saude-mental-da-populacao.ghtml