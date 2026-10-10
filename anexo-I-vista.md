---
title: "ANEXO I – Modelo Estruturado de Projeto de Pesquisa"
subtitle: "Chamada CNPq/SETEC/SETAD/MCTI/FNDCT Nº 29/2026 – RHAE IA"
---

## Identificação do Projeto

| Campo | Informação |
|---|---|
| **Título do Projeto** | VISTA – Inteligência territorial preditiva baseada em IA para mobilidade ativa, segurança e valorização urbana |
| **Empresa Executora (nome, sigla e CNPJ)** | MASTER EDUCACAO LTDA – ME (nome fantasia: MASTER EDUCACAO) – CNPJ 48.055.955/0001-72 |
| **Home Page da Empresa Executora** | Nada a declarar. |
| **Atividade Econômica (CNAE)** | 62.01-5-01 – Desenvolvimento de programas de computador sob encomenda |
| **Nome do(a) Coordenador(a) do Projeto** | Ester Calazans |
| **Cargo ou Função do(a) Coordenador(a) na Empresa** | Sócia e CEO (função executiva) |
| **Missão(ões) da NIB (item 4.2)** | **Missão 3** – Infraestrutura, saneamento, moradia e mobilidade sustentáveis para a integração produtiva e o bem-estar nas cidades (principal). **Missão 4** – Transformação digital da indústria para ampliar a produtividade (secundária). |
| **A empresa se enquadra como Negócio de Impacto Socioambiental (item 4.3.1)?** | (X) Sim ( ) Não |
| **Empresa Liderada por Mulher (item 4.3.2): a proponente é sócia ou proprietária da empresa executora e exerce função executiva ou gerencial?** | (X) Sim ( ) Não |
| **Porte da empresa (item 6.3.b)** | Microempresa – ME (LC 123/2006) |
| **Instituições Parceiras** | Nada a declarar. |
| **Nível de maturidade tecnológica atual (TRL, Anexo II)** | **TRL 2 – Formulação da Tecnologia.** Conceito, arquitetura de dados, mecanismo de IA e modelo de negócio formulados; sem prova de conceito experimental. Meta: TRL 5 ao final do projeto. |

## Informações sobre a Empresa Executora

### 1. Perfil organizacional e dados gerais da empresa

A MASTER EDUCACAO LTDA – ME é uma empresa de desenvolvimento de software sediada em Maceió (AL), fundada em 22/09/2022 e com situação cadastral ativa. Sua atividade principal é o desenvolvimento de programas de computador sob encomenda (CNAE 62.01-5-01).

- **Produto próprio:** a empresa desenvolveu e operou em produção o **Orientei – Master Educação App**, plataforma própria com automação, *matching* e integração de dados. Esse produto foi apoiado pelo Programa Centelha (2022) e pela FAPEAL (2024) e reconhecido no Prêmio Mulheres Inovadoras (2026).
- **Quadro de pessoal:** 23 colaboradores contratados por prestação de serviço, sem empregados em regime CLT. A equipe inclui um mestre em engenharia (John Jairo).
- **Gestão:** a empresa é dirigida por Ester Calazans (CEO) e tem Marcos Oliveira como CTO, responsável pela arquitetura técnica das plataformas.

A sede em Maceió situa o projeto na região Nordeste, contemplada pela parcela mínima de 30% dos recursos da Chamada (item 7.4), e confere à equipe conhecimento local do território-piloto do projeto.

### 2. Relevância da empresa como Negócio de Impacto Socioambiental (Enimpacto)

Respondemos, um a um, aos quatro critérios do item 4.3.1:

1. **Intencionalidade.** A missão declarada da empresa no projeto VISTA é produzir informação territorial **positiva e não estigmatizante**, que oriente investimento privado e público para moradia, mobilidade ativa e espaço público de qualidade, inclusive em bairros hoje invisíveis aos instrumentos de mercado.
2. **Atividade principal resolve problema socioambiental real.** Decisões imobiliárias e de política urbana são tomadas com dados fragmentados: estatística criminal defasada e reativa de um lado, preço do m² de outro. Isso concentra investimento onde já há renda e reforça o estigma territorial de bairros periféricos. O índice VISTA mede oportunidade, e não risco, e por desenho cobre áreas sem dados de mercado (Fase 2, visão computacional).
3. **Receita própria, sem dependência de subsídio.** O modelo de negócio prevê licenciamento B2B (relatórios e API para imobiliárias e incorporadoras) e contratos B2G (painéis de inteligência territorial para secretarias de planejamento e segurança). O fomento do CNPq financia a fase de pesquisa; a operação comercial se sustenta com receita própria.
4. **Monitoramento do impacto.** O projeto adota indicadores de impacto acompanhados semestralmente: proporção de bairros de baixa renda cobertos pelo índice, número de decisões públicas ou privadas apoiadas pelo índice nos pilotos e auditoria de viés do índice frente à renda (o índice não pode apenas reproduzir renda; ver seção 6).

### 3. Empresa Liderada por Mulher

A coordenadora e proponente, **Ester Calazans**, é sócia da Master e exerce função executiva na empresa como **CEO**. Como CEO, ela responde pela direção estratégica, pela gestão da empresa e pelo relacionamento institucional e comercial. No projeto, é a coordenadora formal perante o CNPq, preside o Comitê Gestor e é a responsável pela interlocução institucional e pela guarda das anuências da equipe. Fica autodeclarada, para os fins do item 4.3.2.1, a condição de sócia em função executiva/gerencial.

## Descrição do Projeto

### 4. Objetivos, metas e indicadores

**Objetivo geral.** Desenvolver e validar um índice territorial preditivo, baseado em inteligência artificial, que quantifique a relação entre mobilidade ativa agregada, segurança pública e potencial de valorização urbana, entregue como inteligência licenciável para os mercados imobiliário e público.

| Objetivo específico | Meta | Período | Indicador |
|---|---|---|---|
| OE1. Pipeline de ingestão e agregação de dados abertos e licenciados de mobilidade, segurança e território | Pipeline operando com ≥ 6 fontes integradas | Meses 1–6 | Nº de fontes integradas; % de atualização automática |
| OE2. Validar estatisticamente a hipótese central, controlando renda e infraestrutura, na região-piloto de Maceió | Prova de conceito concluída (TRL 3) | Meses 4–14 | Ganho informativo do índice sobre modelo baseado apenas em preço e renda |
| OE3. Modelo espaço-temporal sobre grafo viário com correção de viés amostral | Modelo validado em laboratório (TRL 4) | Meses 8–18 | Desempenho preditivo contra *baseline*; nº de segmentos viários cobertos |
| OE4. Camada de visão computacional sobre imagem aberta para cobrir áreas sem dados de mobilidade | 100% dos bairros de Maceió com índice estimado | Meses 12–24 | Nº de bairros cobertos; erro do índice em áreas sem dados de mobilidade |
| OE5. Validar o índice em ambiente relevante com parceiros de mercado e do setor público | ≥ 1 piloto B2B e ≥ 1 piloto B2G (TRL 5) | Meses 19–30 | Nº de pilotos ativos; nº de registros de PI depositados no INPI |

### 5. Relevância do projeto e aderência à temática IA e ao Eixo 4 do PBIA

**Relevância para a área e o setor produtivo.** O mercado brasileiro de *proptech* é estimado em cerca de US$ 1,09 bilhão em 2026, com crescimento de 13,7% ao ano. Localização explica até 70% do valor de imóveis de alto padrão (FIPE), e bairros com índices de segurança mais favoráveis têm valorização até 25% maior (IPEA, 2023). Ainda assim, nenhuma solução nacional usa o comportamento real das ruas como sinal antecedente de qualidade territorial.

**Hipótese de pesquisa.** O projeto **investiga e quantifica** a relação entre densidade de mobilidade ativa (caminhada, corrida, ciclismo) e indicadores de segurança e valorização territorial, **controlando renda e infraestrutura**. O objetivo é construir um índice com poder informativo próprio, isto é, que acrescente informação além do que preço e renda já explicam. Tratar a tese como hipótese, e não como fato, é deliberado. Viés amostral (usuários de aplicativos de atividade física têm perfil de renda específico), causalidade invertida e confundimento com infraestrutura são o objeto da pesquisa, e não uma limitação escondida.

**Aderência à definição de IA do PBIA (item 4.1.1).** O projeto produz exatamente "previsões, classificações, recomendações e decisões, a partir de processos de aprendizagem baseados em grande volume de dados":

- **Fase 1, aprendizado de máquina geoespacial (meses 1–14):**
  - redes neurais em grafo (GNN) sobre a malha viária do OpenStreetMap, para prever padrões de uso por segmento de rua e faixa horária;
  - correção de viés amostral por reponderação por propensão e calibração contra o Censo 2022 (IBGE);
  - regressão espacial com controles, para medir o valor informativo do índice;
  - clusterização não supervisionada de perfis espaço-temporais de uso do território.
- **Fase 2, visão computacional (meses 12–30):** classificação e segmentação de imagens abertas (Sentinel-2, Mapillary) para extrair cobertura arbórea, calçadas, iluminação, praças e densidade construída. Esses atributos são independentes dos aplicativos de atividade física e permitem estimar o índice em bairros periféricos sem dados de mobilidade, corrigindo o viés territorial.

**Eixo 4 do PBIA, IA para Inovação Empresarial.** A IA é o próprio produto da empresa: um ativo de dados e modelos proprietários, licenciável e escalável para outras cidades. O projeto converte pesquisa aplicada em inovação empresarial de base tecnológica no Nordeste.

### 6. Metodologia

1. **Fontes de dados.** O núcleo usa fontes abertas e de uso comercial livre: OpenStreetMap (malha viária e equipamentos), IBGE/Censo 2022 (setores censitários), dados abertos de segurança pública (SSP-AL, SINESP, Atlas da Violência/IPEA), Sentinel-2/Copernicus e Mapillary. Indicadores agregados de mobilidade ativa de provedores licenciados (por exemplo, Strava Metro) entram como **enriquecimento opcional**, mediante licença compatível com o uso comercial do indicador derivado. A execução das metas não depende criticamente dessas fontes.
2. **Engenharia de dados.** O pipeline é indexado espacialmente em hexágonos H3 e segmentos viários, com versionamento de datasets e registro de proveniência.
3. **Modelagem.** A modelagem segue a arquitetura em duas fases descrita no item 5:
   - engenharia de atributos espaço-temporais;
   - modelos de grafo;
   - correção de viés;
   - composição ponderada e calibrada do Índice VISTA.
4. **Validação.** A validação cruzada é espacial, para evitar vazamento entre áreas vizinhas, e compara o índice com *baselines* que usam apenas preço e renda. A métrica de sucesso do projeto é o **ganho informativo incremental** do índice. Há ainda verificação de campo na região-piloto e auditoria de viés por estrato de renda.
5. **Proteção de dados (LGPD).** O projeto não trata dados pessoais. As fontes de mobilidade são consumidas exclusivamente como indicadores **agregados e anonimizados na origem** pelo provedor, com granularidade mínima de segmento viário ou hexágono H3 e janela temporal agregada, o que torna tecnicamente inviável a reidentificação (LGPD, art. 12). As fontes de segurança são dados abertos oficiais já agregados. Nenhum produto do projeto é gerado em nível individual ou de endereço, e a arquitetura veda, por desenho, a ingestão de dados individuais. Salvaguardas adotadas:
   - supressão de células com contagem baixa;
   - proibição contratual de reidentificação;
   - índice sempre positivo e não estigmatizante.

### 7. Cronograma de execução

| Atividade | T1 | T2 | T3 | T4 | T5 | T6 | T7 | T8 | T9 | T10 |
|---|---|---|---|---|---|---|---|---|---|---|
| Pipeline de dados (OE1) | ■ | ■ |  |  |  |  |  |  |  |  |
| Validação da hipótese / PoC – TRL 3 (OE2) |  | ■ | ■ | ■ | ■ |  |  |  |  |  |
| Modelo em grafo e correção de viés – TRL 4 (OE3) |  |  | ■ | ■ | ■ | ■ |  |  |  |  |
| Visão computacional (OE4) – marco: mês 12 |  |  |  | ■ | ■ | ■ | ■ | ■ |  |  |
| Pilotos B2B e B2G – TRL 5 (OE5) |  |  |  |  |  |  | ■ | ■ | ■ | ■ |
| Registros de PI (INPI) e publicações |  |  |  |  | ■ |  |  | ■ |  | ■ |
| Relatórios de acompanhamento e REO |  | ■ |  | ■ |  | ■ |  | ■ |  | ■ |

*T = trimestre (30 meses = 10 trimestres).*

## Viabilidade do Projeto

### 1. Técnica

O projeto parte de tecnologias consolidadas e abertas (Python, PostGIS, H3, PyTorch Geometric, imagens Sentinel-2) e de fontes de dados abertas e de uso comercial permitido. Isso elimina a dependência crítica de um único fornecedor privado. A equipe reúne liderança técnica com experiência em arquitetura de plataformas de dados em produção e um pesquisador mestre dedicado integralmente ao projeto. A empresa aporta infraestrutura de nuvem e uma estação de trabalho com GPU para o treino dos modelos de imagem, como contrapartida.

### 2. Econômica e Mercadológica

- **Oportunidade:** inteligência territorial que combina sinal comportamental e segurança, lacuna não coberta pelos *players* atuais. A Urbit opera dossiês estáticos de camadas; a Mappo foca em preço e no corretor; as grandes *proptechs* vendem transação; os painéis das SSP publicam dado bruto e reativo.
- **Público-alvo:**
  - B2B: incorporadoras, imobiliárias e investidores;
  - B2G: secretarias estaduais e municipais de planejamento urbano e segurança.
- **Mercado potencial:**
  - *proptech* no Brasil com cerca de US$ 1,09 bi em 2026 (+13,7% a.a.);
  - 1.209 *proptechs* mapeadas em 2024;
  - serviços imobiliários representam cerca de 10% do PIB.
- **Forma de comercialização:** a empresa licencia o **indicador derivado**, produto autoral da empresa, e nunca o dado bruto de terceiros:
  - relatório *white-label* e API para B2B;
  - painel de inteligência territorial por contrato para B2G.
- **Estratégia de validação:** a prospecção de imobiliárias, incorporadoras e órgãos públicos de Maceió começa no mês 1, com a meta de ao menos um piloto B2B e um B2G a partir do mês 19. A expansão segue para as capitais do Nordeste e, depois do projeto, para licenciamento SaaS nacional.

## Grau de Inovação e Potencial de Impacto dos Resultados

- **Científico:** quantifica, com controle de confundimento, o valor da mobilidade ativa como indicador antecedente de qualidade territorial. É uma contribuição publicável em ciência de dados urbanos.
- **Tecnológico:** combina modelos em grafo sobre a malha viária com visão computacional sobre imagens abertas, para estimar o índice inclusive onde não há dados de mobilidade.
- **Econômico:** cria um ativo de dados licenciável, gera empregos qualificados em IA no Nordeste e fixa mestres e doutores no setor produtivo.
- **Socioambiental:**
  - orienta investimento para mobilidade ativa, áreas verdes e espaço público;
  - substitui mapas de risco que estigmatizam bairros por um índice de oportunidade;
  - inclui bairros periféricos na leitura de mercado.

## Pesquisa em Bases de Propriedade Intelectual

O posicionamento abaixo baseia-se em levantamento preliminar do estado da técnica. No mês 1 do projeto será feita e registrada uma busca sistemática nas bases INPI, Espacenet, Google Patents e Lens.org, com os termos "índice territorial", "urban safety index", "automated valuation model", "active mobility data", "crime prediction geospatial" e "street network graph neural network".

O estado da técnica concentra-se em modelos automatizados de avaliação imobiliária (AVM), baseados em preço e transações, e em policiamento preditivo, focado em risco. A inovação proposta está na **inversão do sinal**: a mobilidade ativa agregada é usada como **indicador antecedente** de qualidade e segurança territorial, e o produto é um **índice de oportunidade**, e não um escore de risco. Não foram identificados registros que combinem essas características.

Como algoritmos e programas de computador não são patenteáveis no Brasil (Lei 9.279/96, art. 10), a proteção prevista é:

- registro de programa de computador e de marca no INPI;
- segredo industrial sobre pesos e calibração do índice;
- direito autoral sobre a base de dados derivada (Lei 9.610/98).

Requer-se a **restrição de acesso** prevista no item 12.12.b.

## Equipe Executora

| Nome | Titulação | Especialidade | Atividades a serem desenvolvidas | Início (mês/ano) | Duração (meses) | Carga horária semanal |
|---|---|---|---|---|---|---|
| Ester Calazans | [A PREENCHER] | CEO – gestão e negócios de inovação | Coordenação geral; interlocução com o CNPq; validação de mercado e pilotos; Comitê Gestor | Mês 1 | 30 | 10 h |
| Marcos Oliveira | [A PREENCHER] | CTO – arquitetura de software e BI | Liderança técnica; arquitetura da plataforma e do pipeline; integração das camadas; camada de entrega | Mês 1 | 30 | 20 h |
| John Jairo | Engenheiro eletricista; Mestre (2024) | Engenharia elétrica, automação e controle; IA | Pesquisador responsável (bolsa SET): desenho experimental, correção de viés, modelos em grafo, métrica de ganho informativo, publicações e PI | Mês 1 | 30 | 40 h |

## Bolsas Solicitadas

| Modalidade e Nível | Duração (meses) | Perfil do Bolsista | Atividades de pesquisa a serem realizadas | Carga horária semanal | Início (mês/ano) |
|---|---|---|---|---|---|
| SET-D | 30 | Mestre ou doutor em Computação, Estatística, Engenharia ou Geoprocessamento; ML e estatística espacial | Validação da hipótese central; correção de viés amostral; modelo espaço-temporal em grafo; métrica de ganho informativo | 40 h | Mês 1 |
| DTI-B | 24 | Graduado(a) em Computação/Engenharia com experiência em dados geoespaciais (PostGIS, H3, OSM, ETL, nuvem) | Pipeline de ingestão e agregação; camada que veda dados individuais; proveniência e versionamento; automação do índice | 40 h | Mês 1 |
| DTI-C | 18 | Técnico(a) ou graduando(a) em Geografia, Geoprocessamento ou Urbanismo (QGIS, Sentinel-2, Censo IBGE) | Curadoria de dados abertos de segurança e do Censo; verificação de campo; rotulagem de imagens para a visão computacional | 20 h | Mês 6 |

*Total solicitado em bolsas (valores da tabela vigente do CNPq): SET-D 30 × R$ 5.200,00 = R$ 156.000,00; DTI-B 24 × R$ 3.900,00 = R$ 93.600,00; DTI-C 18 × R$ 1.430,00 = R$ 25.740,00. **Total: R$ 275.340,00.***

## Governança

- **Comitê Gestor:** formado pela coordenadora (Ester Calazans), pela liderança técnica (Marcos Oliveira) e pelo pesquisador SET. Reúne-se mensalmente, com ata, e delibera sobre escopo, riscos e replanejamento.
- **Rotina de acompanhamento:**
  - ciclos quinzenais de entregas da equipe técnica;
  - revisão trimestral das metas contra os indicadores do item 4;
  - relatório semestral interno no formato do REO.
- **Indicadores de gestão:**
  - % de marcos do cronograma entregues no prazo;
  - cobertura do índice;
  - desempenho preditivo;
  - ganho informativo do índice;
  - nº de pilotos ativos.
- **Relação com o CNPq:** a coordenadora é a interlocutora única com o CNPq e responde pela comunicação prévia de alterações (item 13.5). A equipe participa do acompanhamento à distância e da Reunião de Acompanhamento presencial (13.7).
- **Arranjos cooperativos:** não há instituições parceiras formalizadas nesta submissão. Parcerias com universidades e cartas de intenção de clientes serão buscadas ao longo da execução, com comunicação ao CNPq.

## Apoios anteriores por meio de Programas de Fomento à PD&I

| Instituição Financiadora | Chamada | Projeto contemplado |
|---|---|---|
| FINEP / FAPEAL | Programa Centelha (2022) | Orientei – Master Educação App |
| FAPEAL | Edital FAPEAL (2024) | Orientei – Master Educação App |
| FINEP | Prêmio Mulheres Inovadoras (2026) | Orientei – Master Educação App |

## Contrapartida

| Descrição do item de custeio e/ou capital | Justificativa | Valor (R$) |
|---|---|---|
| Custeio – remuneração da liderança técnica (Marcos Oliveira, CTO), 20 h/sem × 30 meses | Arquitetura e integração não cobertas por bolsa (8.2.4.a) | 36.000,00 |
| Custeio – remuneração da coordenação (Ester Calazans, CEO), 10 h/sem × 30 meses | Coordenação, gestão e validação de mercado (8.2.4.a) | 15.000,00 |
| Custeio – infraestrutura de nuvem (processamento e armazenamento), 30 meses | Treino e operação dos modelos e do pipeline | 18.000,00 |
| Capital – estação de trabalho com GPU | Treino dos modelos de visão computacional (Fase 2) | 14.000,00 |
| Custeio – passagens e diárias para a Reunião de Acompanhamento | Previsto no item 8.2.6 | 6.000,00 |
| Custeio – registros no INPI (programa de computador e marca) | Estratégia de proteção da PI | 1.500,00 |

| Valor Total da Contrapartida | Quanto (%) este valor corresponde ao solicitado em bolsas? |
|---|---|
| **R$ 90.500,00** | **32,9%** (R$ 90.500,00 / R$ 275.340,00) |
