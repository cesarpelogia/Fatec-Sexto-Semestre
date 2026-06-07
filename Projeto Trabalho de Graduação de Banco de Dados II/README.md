# Cesar Augusto Anselmo Pelogia Truyts

![perfil](https://github.com/cesarpelogia.png)

## Introdução

Este portfólio acadêmico foi construído com projetos realizados em minha formação em Tecnologia em Banco de Dados pela [Faculdade de Tecnologia de São José dos Campos - Prof. Jessen Vidal](https://fatecsjc-prd.azurewebsites.net/).

Ingressei no segundo semestre do ano de 2023, após uma transição de carreira de 15 anos na indústria, onde atuava como técnico em mecânica formado pelo Instituto de Tecnologia de Jacareí. Desde então, tive a oportunidade de trabalhar em equipe, desenvolvendo habilidades técnicas enquanto construía soluções para problemas reais, trazidos por empresas parceiras.

Durante minha trajetória na FATEC, construí uma formação abrangente que une desenvolvimento full-stack, gestão de equipes ágeis e arquitetura de sistemas. Percorri um caminho que foi dos fundamentos em HTML, CSS e JavaScript até a implementação de soluções backend robustas com Java e Spring Boot, passando por experiências significativas com dados geoespaciais, integração de APIs REST e bancos de dados relacionais e geoespaciais (PostgreSQL, PostGIS). Atuei como Scrum Master em múltiplos projetos, desenvolvendo competências em liderança técnica, planejamento de sprints e adaptação a ambientes dinâmicos.

Me encontrei na área de dados e arquitetura de sistemas, onde busco constantemente evoluir como desenvolvedor e arquiteto de soluções.

## Meus Projetos

## :heavy_check_mark: Em 2023-2

### Parceiro Acadêmico
[Faculdade de Tecnologia de São José dos Campos - Prof. Jessen Vidal](https://fatecsjc-prd.azurewebsites.net/)

<img src="./image/Fatec/Fatec.png" alt="Fatec São José dos Campos - Prof. Jessen Vidal">

Criada em 2 de março de 2006, a FATEC São José dos Campos - Prof. Jessen Vidal é uma Faculdade de Tecnologia do Estado de São Paulo que pertence ao Centro Estadual de Educação Tecnológica Paula Souza (CEETEPS) e oferece cursos gratuitos no formato Tecnólogo.

Sendo a empresa parceira no primeiro semestre, com a alcunha de PBLTex, a Fatec propôs um desafio relacionado à gestão educacional: a instituição utiliza ciclos de avaliação para cálculo do FEE (Fator de Ensino Evolutivo), porém não possuía um sistema para gerenciamento e acompanhamento desses dados. O problema central era a ausência de uma ferramenta que permitisse controle e rastreabilidade das avaliações realizadas em cada ciclo.

A [CoderHood](https://github.com/CoderHood-Fatec/ProjetoCoderHood) desenvolveu uma aplicação web para gerenciamento dos ciclos de avaliação, cobrindo desde o cadastro de turmas, alunos e professores até o lançamento de notas por ciclo e a exportação dos resultados em CSV. O backend, implementado com Flask, expõe endpoints REST que respondem tanto à renderização de páginas via Jinja quanto a requisições assíncronas do frontend. A persistência é feita em arquivos JSON, com carregamento em memória na inicialização e gravação a cada operação. O cálculo da média ponderada por aluno é realizado no servidor a partir das notas registradas em cada ciclo, e o resultado é exibido na tela de detalhes da turma.

### Tecnologias Utilizadas

- **HTML5 / CSS3:** Estruturação e estilização das páginas da aplicação, com estilos isolados por tela (login, área do professor, detalhe de turma, lançamento de notas).
- **JavaScript:** Responsável pela lógica do frontend, incluindo requisições assíncronas via `fetch` para os endpoints do backend e manipulação dinâmica do DOM.
- **Flask:** Microframework Python utilizado como backend monolítico, concentrando roteamento, regras de negócio, geração de ID e persistência em um único módulo.
- **JSON:** Formato utilizado para persistência dos dados de turmas, alunos e professores em arquivos no servidor, sem uso de banco de dados relacional.
- **Git / GitHub:** Ferramentas de versionamento e colaboração utilizadas para controle de versão e trabalho em equipe.

### Contribuições Pessoais

Atuei no desenvolvimento de funcionalidades de front-end e back-end, com foco em integração de dados e estilização da interface.

1. **Edição de Alunos**
   - Interface de edição integrada ao menu de professor, com listagem de alunos e ação "Alterar Aluno"
   - Rota de consulta por ID no back-end (`GET /aluno/<id>`) e integração com o front-end via `fetch`

2. **Reestruturação de Dados (JSON)**
   - Reorganização de `alunos.json` e `turmas.json`, criando vínculos consistentes entre alunos e turmas

3. **Estilização (CSS)**
   - Padronização de tipografia, cores e layout nas telas de login, área do professor e gestão de alunos

4. **Documentação**
   - Padronização dos requisitos funcionais e reorganização do backlog por diretrizes ágeis

### Hard Skills

- Estruturação de páginas web com HTML5 e CSS3: Sei fazer com autonomia;
- Lógica de programação com JavaScript: Sei fazer com ajuda;
- Desenvolvimento de rotas com Flask: Sei fazer com ajuda;
- Manipulação de dados em formato JSON: Sei fazer com autonomia;
- Versionamento com Git e GitHub: Sei fazer com ajuda;
- Metodologia Ágil SCRUM: Sei fazer com ajuda.

### Soft Skills

- **Adaptação:** Primeiro contato com desenvolvimento de software em equipe, o que exigiu rápida adaptação ao fluxo colaborativo de trabalho e à metodologia ágil, até então desconhecida para mim.
- **Organização e gestão do tempo:** Necessidade de conciliar o aprendizado de novas tecnologias com os prazos do projeto e das demais disciplinas do semestre, o que exigiu planejamento e disciplina desde o início.
- **Comunicação:** Desenvolvimento da capacidade de alinhar expectativas com a equipe, definindo responsabilidades e garantindo que as entregas atendessem aos critérios acordados.

---

## :heavy_check_mark: Em 2024-1

### Parceiro Acadêmico
[Faculdade de Tecnologia de São José dos Campos - Prof. Jessen Vidal](https://fatecsjc-prd.azurewebsites.net/)

No segundo semestre de parceria com a FATEC, o desafio apresentado foi o desenvolvimento de uma ferramenta para consolidar e gerenciar dados climáticos de estações meteorológicas do estado de São Paulo. A solução deveria ser capaz de processar múltiplos arquivos CSV provenientes de diferentes estações, organizar os dados de forma consistente e possibilitar sua análise por meio de relatórios.

Com o [Zeus](https://github.com/FatecCoderHood/Coderhood), a equipe desenvolveu uma aplicação desktop em Java com interface JavaFX para carga e gestão de dados climáticos. O sistema processa arquivos CSV do INMET em dois formatos distintos, automático e manual, detectando o formato e extraindo metadados diretamente do nome do arquivo. Os dados ingeridos são normalizados, classificados como válidos ou suspeitos com base em limites configuráveis por variável climática, e persistidos em um banco PostgreSQL com garantia de idempotência nas inserções. A aplicação oferece CRUD de cidades e estações, relatório de valor médio por período, relatório de situação com a última leitura válida por variável, dados para geração de gráfico BoxPlot e tratamento de registros suspeitos.

### Tecnologias Utilizadas

- **Java:** Linguagem principal do projeto, utilizada para toda a lógica de negócio, processamento de arquivos e acesso ao banco de dados via JDBC.
- **JavaFX:** Framework para construção da interface gráfica desktop, com telas definidas em FXML e controllers vinculados por injeção de dependência.
- **PostgreSQL:** Banco de dados relacional utilizado para armazenamento dos registros climáticos. O schema é criado automaticamente na inicialização da aplicação, incluindo constraints de unicidade que garantem a integridade das inserções.
- **Git / GitHub:** Controle de versão e colaboração entre os membros da equipe ao longo das quatro sprints do projeto.
### Contribuições Pessoais

Atuei como Scrum Master e desenvolvedor, sendo responsável pela organização das sprints e pela implementação do módulo de gerenciamento de estações.

1. **Gerenciamento de Estações (Java + JavaFX)**
   - CRUD completo com integração nas camadas Controller → Service → Repository
   - Validação de duplicidade de sigla e exclusão com garantia de integridade referencial

2. **Integração com Banco (SQL)**
   - Persistência via `EstacaoSQL` com regras de negócio centralizadas em `EstacaoService`

3. **Módulo de Dados Suspeitos**
   - Estruturação inicial do `SuspeitoService` e da interface `Suspeito.fxml` com tabela e colunas principais

4. **Documentação e Gestão**
   - README atualizado, burndown das Sprints 1, 2 e 3 e organização das histórias de usuário

### Hard Skills

- Desenvolvimento de aplicação desktop com Java e JavaFX: Sei fazer com ajuda;
- Arquitetura em camadas (Controller → Service → Repository): Sei fazer com autonomia;
- Operações CRUD com banco de dados relacional (PostgreSQL): Sei fazer com autonomia;
- Testes unitários com cobertura superior a 80%: Sei fazer com autonomia;
- Metodologia Ágil SCRUM: Sei fazer com autonomia.

### Soft Skills

- **Liderança técnica:** Primeira experiência prática como Scrum Master, envolvendo distribuição de tarefas, acompanhamento do burndown e mediação de impasses entre os membros da equipe, o que exigiu equilíbrio entre a gestão do projeto e a contribuição técnica.
- **Comunicação técnica:** Desenvolvimento da capacidade de apresentar resultados e justificar decisões técnicas para stakeholders com diferentes níveis de conhecimento sobre o sistema.
- **Organização:** Planejamento e acompanhamento contínuo das entregas por sprint, garantindo o cumprimento dos critérios de aceitação definidos com o cliente.

---

## :heavy_check_mark: Em 2024-2

### Parceiro Acadêmico
[GSW](http://www.gsw.com.br)

Atuando no mercado desde 1991, a GSW é uma empresa nacional especializada em gerar soluções para o gerenciamento e controle de processos e negócios.

Neste semestre, a GSW nos trouxe o desafio de desenvolver uma aplicação para captura e armazenamento automatizado de notícias e dados estratégicos. A ferramenta deveria permitir o mapeamento de fontes de informação, a coleta periódica de conteúdo e a construção de um histórico estruturado, com possibilidade futura de análises baseadas em inteligência artificial.

Com o [Morpheus](https://github.com/Morpheus-Fatec/morpheus), a equipe entregou uma plataforma web de monitoramento de informações construída com Spring Boot no backend e Vue.js no frontend. O sistema realiza web scraping configurável de portais de notícias, com seletores CSS definidos por fonte cadastrada, permitindo adicionar novos portais pela interface sem alteração de código.

A coleta é agendada via expressão cron ajustável em runtime, com scraping e consumo de APIs externas executados em paralelo. As notícias capturadas passam por filtragem baseada em tags com suporte a sinônimos e regionalismos: o sistema expande automaticamente cada termo para suas variações antes de verificar o conteúdo, tanto na coleta quanto na consulta.

A busca pelo usuário utiliza filtros dinâmicos compostos por título, conteúdo, autor, portal de origem e período, com resultados paginados.

### Tecnologias Utilizadas

- **Java / Spring Boot:** Linguagem de programação e framework utilizados para desenvolvimento do backend, responsável pelas rotas, regras de negócio e integração com o banco de dados.
- **JavaScript / Vue.js:** Framework JavaScript utilizado para desenvolvimento da interface do usuário, com comunicação via Axios para integração com a API REST.
- **MySQL:** Sistema gerenciador de banco de dados relacional utilizado para persistência das notícias e informações coletadas pelas fontes cadastradas.
- **Git / GitHub:** Ferramentas de versionamento e colaboração em equipe, com gestão de tarefas via GitHub Projects.

### Contribuições Pessoais

Atuei exclusivamente como Scrum Master, com gestão integral das sprints e contribuições pontuais na integração do módulo de APIs.

1. **Integração Front-end ↔ Back-end (módulo de APIs)**
   - Substituição de rotas inconsistentes por padrões definitivos via Vue.js + Axios
   - Ajuste do payload de criação/edição de APIs (tagCodes, flags GET/POST) e correção das chamadas REST (`/morpheus/api/{code}`)

2. **Correções no Back-end**
   - Organização de imports e padronização de classes de resposta em `ApiService.java`

3. **Padronização de UI e Navegação**
   - Reestruturação do menu com agrupamentos lógicos ("Gerenciar", "Conteúdos")

4. **Documentação e Gestão**
   - Atualização do README com status das sprints e manutenção contínua do burndown

### Hard Skills

- Integração Vue.js + Axios com APIs REST: Sei fazer com ajuda;
- Desenvolvimento backend com Spring Boot: Sei fazer com ajuda;
- Padronização de payloads e rotas REST: Sei fazer com autonomia;
- Gestão técnica via GitHub Projects com critérios e estimativas por tarefa: Sei fazer com autonomia;
- Metodologia Ágil SCRUM: Sei fazer com autonomia.

### Soft Skills

- **Liderança em cenários adversos:** Gerenciei a equipe em um momento de recomposição de integrantes e baixo engajamento, o que exigiu capacidade de manter o alinhamento e a motivação do time sem comprometer os prazos das entregas.
- **Planejamento de capacitação:** Identifiquei lacunas técnicas na equipe e organizei direcionamentos para nivelamento de conhecimento, garantindo que todos pudessem contribuir nas sprints seguintes.
- **Comunicação:** Mantive alinhamento constante com o Product Owner para que as entregas refletissem corretamente as prioridades do cliente, mesmo diante das dificuldades internas do semestre.

---

## :heavy_check_mark: Em 2025-1

### Parceiro Acadêmico
[Visiona Tecnologia Espacial](https://www.visionaespacial.com.br/)

Criada em 28 de maio de 2012, a Visiona Tecnologia Espacial é resultante de uma iniciativa do Governo nacional de estimular a criação de uma empresa integradora na indústria espacial. Ela corresponde a uma das ações selecionadas como prioritárias no Programa Nacional de Atividades Espaciais (PNAE) para atender aos objetivos e às diretrizes da Política Nacional de Desenvolvimento das Atividades Espaciais (PNDAE) e da Estratégia Nacional de Defesa (END).

A empresa nos trouxe o desafio de desenvolver um sistema web para edição e análise de dados geoespaciais no contexto agrícola. A solução deveria permitir a manipulação de polígonos, análise de dados e acompanhamento por meio de dashboards, visando contribuir para a melhoria de modelos de inteligência artificial aplicados à classificação de áreas.

Com o [Demeter](https://github.com/Morpheus-Fatec/API_4S_Visiona_PolygonEditor), desenvolvemos uma plataforma web para visualização e edição de polígonos geoespaciais agrícolas. O sistema recebe arquivos GeoJSON com classificações automáticas geradas por modelos de IA, converte as geometrias para o formato MultiPolygon com validação estrutural e persiste os dados em PostgreSQL com a extensão PostGIS utilizando SRID 4326.

O fluxo de trabalho envolve três perfis: o analista edita manualmente as classificações sobre o mapa, desenhando polígonos diretamente na interface; o consultor revisa o trabalho do analista, anotando regiões com comentários georreferenciados e aprovando ou rejeitando o talhão. O sistema identifica automaticamente falsos positivos e falsos negativos comparando as classificações automáticas e manuais via operações espaciais, expondo essas divergências como camadas GeoJSON separadas para apoiar o refinamento dos modelos.

Talhões aprovados podem ser exportados em GeoJSON estruturado para reintegração ao pipeline de IA da Visiona. Dashboards analíticos consolidam métricas de desempenho por analista e consultor, comparando produtividade individual com a média da equipe e acompanhando a evolução mensal das áreas classificadas.

### Tecnologias Utilizadas

- **Java / Spring Boot:** Linguagem e framework utilizados no desenvolvimento do backend, responsável pelo processamento das geometrias, controle de perfil e exposição das APIs REST.
- **PostgreSQL / PostGIS:** Banco de dados relacional com extensão espacial, utilizado para armazenamento e execução de consultas sobre geometrias georreferenciadas com SRID 4326, incluindo operações de interseção espacial para identificação de divergências entre classificações.
- **JTS Topology Suite:** Biblioteca Java para manipulação de geometrias vetoriais, utilizada na conversão bidirecional entre GeoJSON e MultiPolygon, com validação de fechamento de anéis.
- **JavaScript / Vue.js:** Framework frontend utilizado para construção da interface interativa de visualização e edição de polígonos.
- **Leaflet:** Biblioteca JavaScript para renderização de mapas interativos no navegador, fundamental para a visualização e edição das geometrias no frontend.
- **Pinia:** Gerenciador de estado do Vue.js, utilizado para controle centralizado dos dados da aplicação no frontend.
- **AWS:** Plataforma de computação em nuvem utilizada para deploy e armazenamento da aplicação em ambiente de produção.
- **Git / GitHub:** Ferramentas de versionamento e colaboração em equipe.

### Contribuições Pessoais

Atuei como Scrum Master e desenvolvedor, com ênfase no processamento de dados geoespaciais e implementação de consultas espaciais avançadas.

1. **Processamento e Persistência Geoespacial**
   - Implementação do conversor `GeoJsonToJTSConverter`, responsável por transformar coordenadas GeoJSON em objetos `MultiPolygon` da biblioteca JTS, com validação estrutural de fechamento de anéis via `ensureClosedRing`: caso o primeiro e o último ponto de um anel não coincidam, o conversor insere automaticamente uma cópia do ponto inicial ao final do array, garantindo geometrias válidas antes da persistência
   - Implementação do conversor inverso `ConverterToMultipolygon`, que serializa objetos `MultiPolygon` do JTS de volta para a estrutura de coordenadas aninhadas do GeoJSON, percorrendo anéis exteriores e interiores de cada polígono
   - Persistência via PostGIS com SRID 4326, cobrindo o fluxo completo: recebimento via API REST, conversão para geometria JTS, armazenamento no banco e retorno em GeoJSON para o frontend

2. **Consultas Espaciais para Identificação de Divergências**
   - Implementação dos endpoints de false positives e false negatives, que comparam as classificações automáticas geradas pela IA com as classificações manuais dos analistas usando operações de interseção espacial via PostGIS
   - False positives: regiões que a IA classificou mas o analista não confirmou; false negatives: regiões que o analista classificou mas a IA não detectou. Ambos retornam como coleções GeoJSON independentes, permitindo que a equipe da Visiona identifique padrões de erro nos modelos

3. **Fluxo de Classificação e Controle por Perfil**
   - Controle de edição por perfil via `ClassificationControl`: analistas registram tempo de edição, contagem de interações e geometrias manuais; consultores registram revisões georreferenciadas com comentários e definem o status final do talhão (aprovado, rejeitado ou em revisão)
   - Bloqueio de edição concorrente: o sistema valida se o `analystResponsable` ou `consultantResponsable` já está atribuído ao controle antes de permitir novas edições, evitando sobrescrita de trabalho entre usuários

4. **Exportação de GeoJSON Estruturado**
   - Implementação dos endpoints de download em dois formatos: `SaidaDTO` para talhões aprovados, com geometria e atributos agrícolas no padrão esperado pelo pipeline da Visiona; `ManualDTO` para exportação das classificações manuais com classe de uso do solo por polígono

5. **Arquitetura e Estabilidade**
   - Refatoração de payloads de resposta para separação clara entre DTO de criação, atualização e visualização
   - Correção de `NullPointerException` em coleções não inicializadas em entidades JPA

6. **Documentação e Gestão**
   - Reestruturação do README, manuais com evidências visuais e backlog alinhado à execução real das sprints

### Hard Skills

- Modelagem e manipulação de dados geoespaciais com PostGIS: Sei fazer com autonomia;
- Conversão entre formatos geoespaciais (GeoJSON ↔ geometrias JTS) com validação estrutural: Sei fazer com autonomia;
- Consultas espaciais avançadas para análise de divergências entre classificações: Sei fazer com autonomia;
- Desenvolvimento de APIs REST com Spring Boot e controle de acesso por perfil: Sei fazer com autonomia;
- Desenvolvimento frontend com Vue.js e Leaflet: Sei fazer com ajuda;
- Deploy em ambiente AWS: Sei fazer com ajuda;
- Metodologia Ágil SCRUM: Sei fazer com autonomia.

### Soft Skills

- **Adaptação a mudanças de escopo:** Capacidade de replanejamento diante de requisitos que chegaram tardiamente, mantendo a qualidade das entregas dentro do prazo acordado com o cliente.
- **Resiliência:** Manutenção do foco e da produtividade em um ambiente marcado por conflitos internos e oscilações no engajamento da equipe ao longo das sprints.
- **Liderança técnica:** Coordenação das decisões arquiteturais e mediação entre os diferentes perfis técnicos da equipe, garantindo a consistência da solução entregue à Visiona.

---

## :heavy_check_mark: Em 2025-2

### Parceiro Acadêmico
[Necto Systems](https://www.necto.com.br/)

A empresa nos trouxe o desafio de desenvolver uma solução corporativa integrada, baseada em arquitetura de microserviços, voltada ao processamento eficiente, integração e visualização de dados para apoio à tomada de decisão empresarial. O projeto abrangeu automação de ETL, exposição de APIs RESTful seguras e construção de dashboards analíticos responsivos.

Com o [NeoHorizon](https://github.com/FatecNeoHorizon/API_5S), a equipe entregou uma plataforma de inteligência operacional estruturada em modelo dimensional, com pipeline ETL automatizado integrado ao Jira, API REST segura com controle de acesso granular por perfil e dashboards interativos para análise de produtividade, custos e apontamentos de horas.

O sistema extrai issues diretamente da API do Jira via JQL, transforma os dados em fatos e dimensões seguindo o modelo estrela, e os carrega no banco PostgreSQL por meio da própria API backend. O controle de acesso é implementado com JWT stateless e quatro perfis distintos: DEVELOPER, MANAGER, ADMIN e ETL, cada um com permissões mapeadas por rota e método HTTP diretamente na cadeia de filtros do Spring Security.

### Tecnologias Utilizadas

- **Java 21 / Spring Boot:** Linguagem e framework utilizados para o desenvolvimento do backend, com foco em APIs RESTful seguras, documentadas e com controle de permissões por perfil.
- **Python (Pandas, SQLAlchemy):** Utilizados na construção dos pipelines de ETL para extração via API Jira, transformação dos dados em modelo dimensional e carga via API REST.
- **PostgreSQL:** Banco de dados relacional utilizado para persistência dos dados no modelo estrela, com tabelas de fato e dimensão indexadas e com constraints de unicidade por granularidade.
- **React (TypeScript):** Biblioteca frontend utilizada para construção da SPA com dashboards interativos, roteamento protegido e autenticação JWT.
- **Docker Compose:** Ferramenta para orquestração dos serviços da aplicação em containers isolados.
- **GitHub Actions:** Plataforma de CI/CD utilizada para automatização de builds, testes e publicação dos módulos.
- **JWT:** Padrão de autenticação stateless utilizado para controle de acesso às APIs, com roles embutidas no payload do token.
- **Swagger / OpenAPI:** Utilizados para documentação dos contratos das APIs, facilitando a integração entre os módulos.
- **Git / GitHub:** Ferramentas de versionamento e colaboração em equipe.

### Contribuições Pessoais

Atuei como integrador do ecossistema, coordenando backend, ETL e frontend num monorepo com CI/CD automatizado end-to-end.

1. **Modelagem Dimensional e Schema do Banco**
   - Definição do modelo estrela com três tabelas de fato: `fato_atividade` (quantidade de issues por projeto, período, status e tipo), `fato_apontamento_horas` (horas trabalhadas por dev e atividade) e `fato_custo_hora` (custo calculado por dev e projeto)
   - Constraints de unicidade por granularidade em cada tabela de fato, garantindo idempotência nas inserções do ETL e impedindo duplicidade ao reprocessar os dados do Jira

2. **Pipeline ETL em Python**
   - Pipeline sequencial orquestrado em `main.py`, cobrindo extração, transformação e carga de todas as dimensões e fatos em ordem de dependência: projetos, issues Jira, atividades, períodos, tipos, devs, status, fatos
   - Extração de issues via JQL por projeto com limite de 1000 registros, usando a sessão autenticada da API Jira configurada por variáveis de ambiente
   - Transformação dos fatos com agrupamento por chave de granularidade (combinação de IDs de dimensão), acumulando quantidades incrementalmente antes da carga
   - Carga via POST na própria API REST do backend, com autenticação JWT gerada no início do pipeline usando o perfil ETL, capturando e registrando o ID retornado para rastreabilidade

3. **Autenticação JWT e Controle de Acesso por Perfil**
   - Implementação do `JwtUtils` com geração de tokens HS512 de 1 hora de validade, embutindo email e roles no claim `UserDetails` como JSON serializado
   - Implementação do `JwtAuthenticationFilter` como `GenericFilterBean`, interceptando o header `Authorization: Bearer`, validando expiração e populando o `SecurityContext` antes de encaminhar a requisição
   - Mapeamento granular de permissões no `SecurityConfig` por rota e método HTTP para quatro perfis: DEVELOPER (leitura de atividades e métricas próprias), MANAGER (leitura de custos e gestão de usuários), ADMIN e ETL (escrita em dimensões e fatos)

4. **Métricas de Produtividade (DevHoursMetricsService)**
   - Serviço de métricas de horas por desenvolvedor com filtros opcionais por dev, atividade e intervalo de datas, usando `parallelStream()` com `groupingBy` para agrupamento eficiente em grandes volumes
   - Resultado estruturado por dev, com total de horas, detalhamento por atividade e lista de apontamentos diários com descrição do trabalho

5. **Arquitetura e Integração dos Módulos**
   - Monorepo com submódulos Git independentes para backend, ETL e frontend, com contratos REST e autenticação padronizados
   - Pipelines GitHub Actions para build, teste e publicação de cada módulo, com Docker Compose para orquestração local dos serviços

### Hard Skills

- Modelagem dimensional (modelo estrela com fatos e dimensões): Sei fazer com autonomia;
- Desenvolvimento de APIs RESTful seguras com Spring Boot e JWT: Sei fazer com autonomia;
- Construção de pipelines ETL em Python com integração via API REST: Sei fazer com autonomia;
- Controle de acesso granular por perfil com Spring Security: Sei fazer com autonomia;
- Desenvolvimento de SPA com React/TypeScript: Sei fazer com ajuda;
- Orquestração de containers com Docker Compose: Sei fazer com autonomia;
- Documentação de APIs com Swagger/OpenAPI: Sei fazer com autonomia;
- Metodologia Ágil SCRUM: Sei fazer com autonomia.

### Soft Skills

- **Liderança de integração:** Coordenação entre squads responsáveis por módulos distintos (backend, ETL e frontend), garantindo compatibilidade entre as interfaces e coerência na entrega final.
- **Gestão de incidentes técnicos:** Identificação e resolução de bloqueios que afetavam múltiplos módulos simultaneamente, mantendo o ritmo das entregas sem comprometer a qualidade.
- **Comunicação técnica:** Facilitação do onboarding de novos membros e defesa de decisões arquiteturais perante a equipe e stakeholders, traduzindo escolhas técnicas em linguagem acessível.

---

## :heavy_check_mark: Em 2026-1

### Parceiro Acadêmico
[Tecsys do Brasil](https://www.tecsysbrasil.com.br/)

Fundada em 2000 e sediada em São José dos Campos, a Tecsys do Brasil é uma empresa de base tecnológica especializada no desenvolvimento de soluções customizadas para as áreas de Broadcast, Broadband, Telecom e Smart Grid, atendendo clientes como Elektro, EDP, Globo e SBT.

A empresa nos trouxe o desafio de transformar dados públicos da ANEEL em inteligência de mercado escalável. Sem um processo estruturado de ingestão e análise desses dados, a identificação de regiões críticas e a priorização comercial dependiam de análises manuais, não rastreáveis e sujeitas a erros, comprometendo a tomada de decisão estratégica.

Com o [Zeus](https://github.com/FatecCoderHood/Zeus_Coderhood_FATEC), a equipe entregou uma plataforma web de inteligência de mercado para o setor de energia elétrica. O sistema ingere dados públicos da ANEEL por meio de um pipeline ETL versionado, calcula TAM e SAM, ranqueia regiões por criticidade com base nos indicadores DEC/FEC e projeta tendências via modelos de séries temporais, tudo exposto por APIs REST e visualizado em dashboards interativos.

A arquitetura dual de banco de dados (MongoDB para dados analíticos públicos e PostgreSQL para dados sensíveis) garante rastreabilidade e resultados reproduzíveis. A conformidade com a LGPD é tratada como requisito de produto, com trilhas de auditoria append-only, anonimização lógica e criptografia de campos sensíveis. A autenticação é gerenciada via Keycloak com fluxo OAuth 2.0 Authorization Code com PKCE.


### Tecnologias Utilizadas

- **Python / FastAPI:** Linguagem e framework utilizados no desenvolvimento do backend e do pipeline ETL, responsável pela ingestão, transformação e carga dos dados da ANEEL.
- **MongoDB:** Banco de dados orientado a documentos utilizado para armazenamento dos dados analíticos públicos processados pelo ETL.
- **PostgreSQL:** Banco de dados relacional utilizado para persistência de dados sensíveis, com schema de conformidade LGPD.
- **Keycloak:** Servidor de identidade e acesso utilizado para autenticação e autorização via OAuth 2.0 com fluxo Authorization Code e PKCE.
- **React:** Biblioteca frontend utilizada para construção dos dashboards interativos de visualização dos indicadores DEC/FEC e TAM.
- **Docker Compose:** Ferramenta para orquestração dos serviços da aplicação em containers isolados.
- **GitHub Actions:** Plataforma de CI/CD utilizada para automatização de builds, testes e publicação dos módulos.
- **Git / GitHub:** Ferramentas de versionamento e colaboração em equipe.

### Contribuições Pessoais

Atuei como Scrum Master e desenvolvedor, com foco na infraestrutura de autenticação, observabilidade e pipeline de dados.

## 1. Pipeline ETL (Python / FastAPI)
   - Implementação das etapas de extração e transformação dos dados públicos da ANEEL, incluindo processamento dos indicadores DEC/FEC e arquivos geoespaciais BDGD
   - Carga incremental no MongoDB com upsert idempotente, garantindo reprocessamento seguro sem duplicação de dados

## 2. Autenticação e Autorização com Keycloak e OAuth 2.0

A autenticação do sistema é delegada ao Keycloak como servidor de identidade centralizado, com o backend atuando como resource server — validando tokens, gerenciando sessões próprias e emitindo seus próprios JWTs para as chamadas subsequentes à API.

---

### 2.1 Topologia do Keycloak

O Keycloak é configurado com um realm dedicado ao projeto Zeus e dois clientes distintos:

| Cliente      | Tipo         | Fluxo                        | Finalidade                                          |
|--------------|--------------|------------------------------|-----------------------------------------------------|
| Frontend     | Público      | Authorization Code + PKCE    | Login do usuário via navegador, sem client_secret   |
| Backend      | Confidencial | Client Credentials           | Service account para provisionamento via Admin API  |

A separação de clientes garante que o frontend nunca precise de um segredo compartilhado — o PKCE substitui essa necessidade — enquanto o backend mantém credenciais privadas para operações administrativas.

---

### 2.2 Fluxo OAuth 2.0 Authorization Code com PKCE (`oauth_callback`)

```
User             Frontend             Keycloak           Backend (FastAPI)
   │                 │                    │                      │
   │  Clicks Login   │                    │                      │
   │────────────────>│                    │                      │
   │                 │ Generates          │                      │
   │                 │ code_verifier      │                      │
   │                 │ code_challenge     │                      │
   │                 │ (SHA-256)          │                      │
   │                 │                    │                      │
   │                 │ Sends redirect_uri │                      │
   │                 │ + code_challenge   │                      │
   │                 │───────────────────>│                      │
   │   Redirects to Keycloak login page   │                      │
   │<─────────────────────────────────────│                      │
   │ Enters login    │                    │                      │
   │ and password    │                    │                      │
   │─────────────────────────────────────>│                      │
   │                 │   authorization_code                      │
   │                 │<───────────────────│                      │
   │                 │ Sends code +       │                      │
   │                 │ code_verifier      │                      │
   │                 │───────────────────>│                      │
   │                 │                    │ Validates PKCE       │
   │                 │                    │ (hash of verifier    │
   │                 │                    │  == challenge)       │
   │                 │  access_token      │                      │
   │                 │  refresh_token     │                      │
   │                 │<───────────────────│                      │
   │                 │ Authorization:     │                      │
   │                 │ Bearer <token>     │                      │
   │                 │──────────────────────────────────────────>│
   │                 │                    │    Validates token   │
   │                 │                    │    via JWKS          │
   │                 │                    │    Checks profile    │
   │                 │<──────────────────────────────────────────│
   │                 │    API Response    │                      │
```

Ao receber o `code` e o `code_verifier` do frontend, o `oauth_callback` executa a seguinte sequência:

1. **Troca do code pelo token do Keycloak** — POST para o endpoint `/token` do Keycloak com `grant_type=authorization_code` e o `code_verifier`, que o Keycloak valida contra o `code_challenge` enviado no início do fluxo.

2. **Validação via JWKS** — o `access_token` retornado é validado localmente usando `PyJWKClient`, que busca a chave pública do Keycloak no endpoint `/certs` e mantém cache das chaves. A assinatura RS256 é verificada sem round-trip adicional ao Keycloak.

3. **Extração de identidade** — do payload do token são extraídos o `sub` (identificador do usuário no Keycloak, `keycloak_sub`) e o perfil a partir de `realm_access.roles`, aceitando apenas os valores `ADMIN`, `MANAGER` ou `ANALYST`. Tokens sem nenhuma dessas roles retornam `403 no_valid_profile_role`.

4. **Verificação no PostgreSQL** — o `keycloak_sub` é usado para localizar o usuário no banco local. Se não encontrado: `401 user_not_registered`. Se inativo: `403 inactive_user`. O Keycloak é a fonte de verdade para autenticação, mas o PostgreSQL é a fonte de verdade para autorização e status da conta.

5. **Emissão de tokens próprios** — o backend gera um par de tokens independentes do Keycloak:
   - **Access token RS256** com payload `{sub, sid, profile, username, exp, type: "access"}`, assinado com chave privada própria e de curta duração
   - **Refresh token opaco** gerado com `secrets.token_urlsafe(48)`, armazenado no banco apenas como `SHA-256(token)` — nunca o valor em claro

```python
# Validação do token Keycloak via JWKS com cache de chaves
signing_key = _get_jwks_client().get_signing_key_from_jwt(kc_access_token)
kc_payload = _jwt.decode(kc_access_token, signing_key, algorithms=["RS256"], ...)

# Extração de perfil a partir das realm roles
kc_roles = kc_payload.get("realm_access", {}).get("roles", [])
profile_name = next((r for r in kc_roles if r in ("ADMIN", "MANAGER", "ANALYST")), None)
```

---

### 2.3 Refresh Token Rotation

A cada renovação de token, o refresh token anterior é **invalidado atomicamente** no banco via `rotate_refresh_token`, que em uma única operação localiza o hash atual, invalida-o e grava o hash do novo token. Se o hash não for encontrado ou a sessão estiver expirada, retorna `401 invalid_or_expired_refresh_token`.

Essa estratégia de rotation garante que, em caso de vazamento de um refresh token, qualquer tentativa de reutilizá-lo após já ter sido rotacionado será bloqueada — o token só é válido uma única vez.

```python
session_data = rotate_refresh_token(
    conn,
    refresh_token_hash=hash_token(payload.refresh_token),      # hash do token atual
    new_refresh_token_hash=hash_token(new_refresh_token),      # hash do próximo
    refresh_expires_at=refresh_expires_at,
)
```

---

### 2.4 Logout Duplo

O logout invalida a sessão em duas camadas:

1. **PostgreSQL** — `invalidate_session()` marca a sessão como inativa pelo `session_id` contido no JWT. Se a sessão já não existir, retorna `401 invalid_or_expired_session`.
2. **Keycloak SSO** — `KeycloakAdminClient.delete_user_sessions(keycloak_sub)` chama `DELETE /admin/realms/{realm}/users/{sub}/sessions`, encerrando todas as sessões SSO ativas do usuário no Keycloak. Essa chamada é feita em bloco `try/except` — falhas no Keycloak não impedem o logout local, garantindo degradação graciosa.

Sem o logout duplo, mesmo com a sessão invalidada no banco, o token SSO do Keycloak permaneceria válido, permitindo re-autenticação silenciosa sem nova digitação de senha.

---

### 2.5 `KeycloakAdminClient` — Singleton com Cache de Token

O `KeycloakAdminClient` é instanciado como singleton via `get_keycloak_admin_client()`, garantindo que o cache de token de service account persista entre requisições. O token é obtido via `client_credentials` e reutilizado enquanto válido (com margem de 10 segundos para renovação antecipada).

As operações suportadas via Admin API cobrem todo o ciclo de vida do usuário no Keycloak:

| Método                        | Operação                                              |
|-------------------------------|-------------------------------------------------------|
| `create_user`                 | Cria usuário com `requiredActions: [UPDATE_PASSWORD]` |
| `get_user` / `get_users`      | Consulta por ID ou listagem com busca e paginação     |
| `update_user`                 | Atualiza username e/ou email                          |
| `set_user_enabled`            | Ativa ou desativa o usuário                           |
| `assign_realm_role`           | Atribui um perfil (`ADMIN`, `MANAGER`, `ANALYST`)     |
| `update_user_role`            | Troca de perfil: remove o antigo e atribui o novo     |
| `send_required_actions_email` | Envia e-mail para o usuário completar ações pendentes |
| `delete_user_sessions`        | Encerra todas as sessões SSO do usuário               |
| `delete_user`                 | Remove o usuário do Keycloak                          |

Os erros são tipados em três exceções distintas — `KeycloakUserAlreadyExistsError`, `KeycloakUserNotFoundError` e `KeycloakAdminError` — permitindo tratamento granular na camada de serviço sem depender de inspeção de status HTTP.

---

### 2.6 Pseudoanonimização de IP (LGPD)

O IP de origem é mascarado antes de ser persistido na sessão, via `mask_source_ip()`:

- **IPv4**: zera o último octeto — `192.168.1.42` → `192.168.1.0`
- **IPv6**: mantém apenas os quatro primeiros grupos — `2001:db8:85a3:0:...` → `2001:db8:85a3:0000::`

```python
def mask_source_ip(source_ip: str | None) -> str:
    parsed = ip_address(value)
    if parsed.version == 4:
        octets = value.split(".")
        return f"{octets[0]}.{octets[1]}.{octets[2]}.0"
    hextets = parsed.exploded.split(":")
    return f"{':'.join(hextets[:4])}}::"
```

Essa técnica preserva granularidade suficiente para fins de auditoria e detecção de anomalias (identificar a sub-rede de origem), sem armazenar o endereço exato do usuário — configurando pseudoanonimização conforme o Art. 13 da LGPD.

## 3. Observabilidade com Logs Estruturados (LGPD-compliant)

A estratégia de observabilidade adota logs estruturados em JSON com rastreabilidade por requisição e conformidade com a LGPD, viabilizando tanto o monitoramento operacional quanto a auditoria de ações sensíveis.

---

### 3.1 Configuração do pipeline (`logger.py`)

O módulo `configure_logging()` inicializa o `structlog` com uma cadeia de processadores ordenada:

- `merge_contextvars` — injeta campos vinculados ao contexto da requisição corrente (ex: `request_id`, `user_id`)
- `add_log_level` e `add_logger_name` — adicionam metadados de origem e severidade
- `TimeStamper(fmt="iso")` — registra o timestamp em ISO 8601
- `JSONRenderer()` — serializa toda a entrada como JSON, tornando cada linha machine-readable e ingerível por ferramentas como Loki, Datadog ou ELK

A saída é roteada para um `TimedRotatingFileHandler` com rotação `when="midnight"` e `backupCount=30`. Ao rotacionar, um `rotator` customizado (`gz_rotator`) comprime o arquivo gerado em `.gz` com `gzip`, removendo o original e reduzindo o volume de armazenamento. A retenção de 30 arquivos equivale a um histórico de 30 dias de logs comprimidos.

```python
structlog.configure(
    processors=[
        structlog.contextvars.merge_contextvars,
        structlog.stdlib.add_log_level,
        structlog.stdlib.add_logger_name,
        structlog.processors.TimeStamper(fmt="iso"),
        structlog.processors.JSONRenderer(),
    ],
    ...
)
```

---

### 3.2 Middleware de rastreamento (`LoggingMiddleware`)

O `LoggingMiddleware`, injetado como Starlette middleware via `setup_middleware()`, instrumenta cada requisição HTTP de forma transparente:

1. **Limpeza de contexto** — `clear_contextvars()` é chamado no início do dispatch para evitar vazamento de dados entre requisições (especialmente relevante em servidores assíncronos com reúso de workers).
2. **Injeção de contexto** — `bind_contextvars()` injeta no contexto compartilhado:
   - `request_id`: UUID v4 gerado em tempo de execução, único por requisição
   - `method` e `path`: identificam a operação HTTP
   - `user_id`: extraído do campo `sub` do JWT via `_extract_user_id()`, sem propagar exceções caso o header `Authorization` esteja ausente ou o token seja inválido (retorna `None` silenciosamente)
3. **Evento de entrada** — `request_started` é emitido antes de chamar o próximo handler
4. **Evento de saída** — `request_finished` é emitido com `status_code` e `duration_ms`, calculado via `time.perf_counter()` (clock de alta resolução). O nível do log é automaticamente escalado para `error` em respostas 5xx, permitindo alertas baseados em severidade sem configuração adicional.

```python
bind_contextvars(
    request_id=str(uuid.uuid4()),
    method=request.method,
    path=request.url.path,
    user_id=_extract_user_id(request),  # None se token ausente/inválido
)

log.info("request_started")
# ... execução do handler ...
level = "error" if response.status_code >= 500 else "info"
getattr(log, level)(
    "request_finished",
    status_code=response.status_code,
    duration_ms=duration_ms,
)
```

Exemplo de saída JSON gerada por requisição:

```json
{"event": "request_started", "request_id": "a3f1...", "method": "POST", "path": "/auth/login", "user_id": null, "level": "info", "timestamp": "2025-06-01T14:32:01.123Z"}
{"event": "request_finished", "request_id": "a3f1...", "status_code": 200, "duration_ms": 42.7, "level": "info", "timestamp": "2025-06-01T14:32:01.165Z"}
```

---

### 3.3 Catálogo de eventos tipados (`log_events.py`)

Todos os eventos de auditoria são definidos como constantes nomeadas, organizados por domínio de negócio:

| Domínio     | Eventos                                                                 |
|-------------|-------------------------------------------------------------------------|
| Usuário     | `user.created`, `user.updated`, `user.deactivated`, `user.deleted`      |
| Política    | `policy.version.created`, `policy.update.notification.scheduled`        |
| Consentimento | `consent.registered`, `consent.revoked`, `data_export.requested`      |
| Sessão      | `session.revoked`, `session.invalidated.all`                            |
| Incidente   | `incident.notification.sent`                                            |

Essa abordagem elimina strings mágicas espalhadas pela codebase, padroniza os eventos emitidos e facilita filtragem precisa por tipo em ferramentas de observabilidade.

Na camada de serviços, os eventos são emitidos com campos contextuais relevantes, porém **sem dados pessoais**:

```python
# auth_service.py — revogação de sessão
log.info(
    SESSION_REVOKED,
    acting_user_id=acting_user_id,
    target_session_uuid=session_uuid,
    reason="USER_REVOCATION",
)

# consent_service.py — registro de consentimento
log.info(CONSENT_REGISTERED, user_id=user_id, clause_id=clause_uuid, channel="WEB")

# user_service.py — falha de integração com Keycloak
_log.error(
    "keycloak.user.role_update_failed",
    keycloak_sub=keycloak_sub,
    old_role=keycloak_current_role,
    new_role=new_profile_name,
    error=str(exc),
)
```

Nenhum evento registra email, CPF, nome, senha ou qualquer outro dado pessoal — apenas identificadores opacos (`user_id`, `session_uuid`) e metadados operacionais.

---

### 3.4 Testes automatizados de conformidade (`test_logging.py`)

A conformidade com a LGPD e a consistência estrutural dos logs são verificadas por testes automatizados com `structlog.testing.capture_logs`:

| Teste | O que verifica |
|-------|---------------|
| `test_log_entry_contains_required_fields` | Presença dos campos `event`, `user_id` e campos de domínio |
| `test_log_entry_does_not_contain_forbidden_fields` | Ausência de `email`, `cpf`, `password`, `name`, `nome`, `senha` |
| `test_log_levels_are_correct` | Correspondência entre chamada (`info`, `warning`, `error`) e campo `log_level` |
| `test_log_entry_is_json_serializable` | Serializabilidade completa da entrada com `json.dumps` |

```python
def test_log_entry_does_not_contain_forbidden_fields():
    forbidden = {"email", "cpf", "password", "name", "nome", "senha"}
    with capture_logs() as logs:
        log.info("user.created", user_id="abc-123", profile_id="xyz-456")
    found = forbidden & set(logs[0].keys())
    assert not found, f"Forbidden fields found in log entry: {found}"
```

Essa bateria de testes garante que nenhuma refatoração futura introduza inadvertidamente dados pessoais nos logs, tornando a conformidade com a LGPD parte do pipeline de CI.

## 4. Documentação e Gestão
   - Organização do backlog, manutenção do burndown e alinhamento das entregas com o parceiro Tecsys ao longo das sprints

### Hard Skills

- Desenvolvimento de pipelines ETL em Python com FastAPI e MongoDB: Sei fazer com autonomia;
- Autenticação e autorização com Keycloak e OAuth 2.0 / PKCE: Sei fazer com autonomia;
- Logging estruturado com conformidade LGPD: Sei fazer com autonomia;
- Modelagem de dados em bancos relacionais e orientados a documentos: Sei fazer com autonomia;
- Orquestração de containers com Docker Compose: Sei fazer com autonomia;
- Metodologia Ágil SCRUM: Sei fazer com autonomia.

### Soft Skills

- **Visão sistêmica:** Capacidade de coordenar módulos interdependentes (ETL, autenticação, frontend) garantindo coerência técnica e funcional na entrega final para o parceiro.
- **Responsabilidade técnica:** Condução de decisões arquiteturais com impacto direto na segurança e conformidade legal do produto, equilibrando prazo e qualidade.
- **Liderança:** Gestão das sprints e alinhamento contínuo com o parceiro Tecsys, mantendo o foco nas prioridades estratégicas do produto mesmo diante das complexidades técnicas do semestre.

---

## Meus Principais Conhecimentos

- **Java** e **Spring Boot**, no desenvolvimento de APIs REST robustas e backends escaláveis;
- **Python**, com foco em scripts de ETL, manipulação e análise de dados;
- **JavaScript / TypeScript**, com experiência em Vue.js e React para desenvolvimento frontend;
- **PostgreSQL** e **PostGIS**, para armazenamento relacional e operações geoespaciais avançadas;
- **Docker** e **Docker Compose**, na construção e orquestração de containers isolados;
- **AWS**, para configuração de servidores e deploy em nuvem;
- **GitHub Actions**, para automação de pipelines CI/CD;
- **Swagger / OpenAPI**, na documentação de APIs;
- **Metodologia Ágil SCRUM**, com atuação como Scrum Master em múltiplos projetos.

## Contatos
* [GitHub](https://github.com/cesarpelogia)
* [LinkedIn](https://www.linkedin.com/in/cesar-augusto-anselmo-pelogia-truyts-94a08a268/)
