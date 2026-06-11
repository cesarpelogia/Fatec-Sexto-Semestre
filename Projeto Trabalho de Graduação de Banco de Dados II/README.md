# Cesar Augusto Anselmo Pelogia Truyts

![perfil](https://github.com/cesarpelogia.png)

## Introdução

Este portfólio acadêmico foi construído com projetos realizados em minha formação em Tecnologia em Banco de Dados pela [Faculdade de Tecnologia de São José dos Campos - Prof. Jessen Vidal](https://fatecsjc-prd.azurewebsites.net/).

Iniciei o curso em 2023 após uma transição de carreira de 15 anos na indústria, onde atuei como técnico em mecânica pelo Instituto de Tecnologia de Jacareí. Ao longo dos seis semestres, construí uma formação que combina desenvolvimento backend, arquitetura de sistemas e gestão ágil, com atuação como Scrum Master em quatro dos seis semestres do curso.

A trajetória passou por fundamentos de desenvolvimento web, processamento de dados geoespaciais, pipelines ETL, autenticação e conformidade com a LGPD, até a entrega de sistemas distribuídos com arquitetura de banco de dados dual. Em paralelo ao desenvolvimento técnico, conduzi equipes em ambientes de alta pressão, lidando com conflitos interpessoais, recomposições de time e acúmulo de funções, experiências que moldaram minha visão sobre liderança e entrega de valor.

Me encontrei na interseção entre dados, arquitetura de sistemas e liderança técnica.

## Meus Projetos

## :heavy_check_mark: Em 2023-2

### Parceiro Acadêmico
[Faculdade de Tecnologia de São José dos Campos - Prof. Jessen Vidal](https://fatecsjc-prd.azurewebsites.net/)

<details>
<summary>Fatec São José dos Campos - Prof. Jessen Vidal</summary>
<img src="./images/fatec.png" alt="Fatec São José dos Campos - Prof. Jessen Vidal">
<b>Figura 1: Fachada da Fatec SJC</b>
</details>

Criada em 2 de março de 2006, a FATEC São José dos Campos - Prof. Jessen Vidal é uma Faculdade de Tecnologia do Estado de São Paulo que pertence ao Centro Estadual de Educação Tecnológica Paula Souza (CEETEPS) e oferece cursos gratuitos no formato Tecnólogo.

Sendo a empresa parceira no primeiro semestre, com a alcunha de PBLTex, a Fatec propôs um desafio relacionado à gestão educacional: a instituição utiliza ciclos de avaliação para cálculo do FEE (Fator de Ensino Evolutivo), porém não possuía um sistema para gerenciamento e acompanhamento desses dados. O problema central era a ausência de uma ferramenta que permitisse controle e rastreabilidade das avaliações realizadas em cada ciclo.

A [CoderHood](https://github.com/CoderHood-Fatec/ProjetoCoderHood) desenvolveu uma aplicação web para gerenciamento dos ciclos de avaliação, cobrindo desde o cadastro de turmas, alunos e professores até o lançamento de notas por ciclo e a exportação dos resultados em CSV. O backend, implementado com Flask, expõe endpoints REST que respondem tanto à renderização de páginas via Jinja quanto a requisições assíncronas do frontend.

<details>
<summary>Cadastro de notas e exibição de média em um ciclo</summary>
<img src="./images/sem1/sem1-1.gif">
<b>Figura 2: Cadastro de notas e exibição de média em um ciclo</b>
</details>

A persistência é feita em arquivos JSON, com carregamento em memória na inicialização e gravação a cada operação. O cálculo da média ponderada por aluno é realizado no servidor a partir das notas registradas em cada ciclo, e o resultado é exibido na tela de detalhes da turma.

<details>
<summary>Modelagem de Dados em JSON</summary>
<img src="./images/sem1/Modelagem de dados persistidos em JSON.jpg" alt="Modelagem de Dados em Json">
<b>Figura 3: Modelagem de Dados em formato Json</b>
</details>

### Tecnologias Utilizadas

- **HTML5 / CSS3:** Estruturação e estilização das páginas da aplicação, com estilos isolados por tela (login, área do professor, detalhe de turma, lançamento de notas).
- **JavaScript:** Responsável pela lógica do frontend, incluindo requisições assíncronas via `fetch` para os endpoints do backend e manipulação dinâmica do DOM.
- **Flask:** Microframework Python utilizado como backend monolítico, concentrando roteamento, regras de negócio, geração de ID e persistência em um único módulo.
- **JSON:** Formato utilizado para persistência dos dados de turmas, alunos e professores em arquivos no servidor, sem uso de banco de dados relacional.
- **Git / GitHub:** Ferramentas de versionamento e colaboração utilizadas para controle de versão e trabalho em equipe.

### Contribuições Pessoais

Foi o primeiro semestre, e o trabalho refletia exatamente isso. Atuei no front-end e no back-end, ainda aprendendo a conectar as duas pontas. Implementei a funcionalidade de edição de alunos, desde a interface integrada ao menu do professor até a rota de consulta por ID no back-end e a integração via fetch. Pequeno para quem já tem experiência, relevante para quem estava aprendendo o que significa fazer uma tela conversar com um servidor.

Também reorganizei a estrutura dos dados em JSON, criando vínculos consistentes entre alunos e turmas. Foi a primeira vez que precisei pensar em como os dados se relacionam antes de pensar em como exibi-los. A estilização das telas de login e gestão de alunos veio junto, consolidando uma identidade visual mínima para o projeto.

Na documentação, trabalhei na padronização dos requisitos funcionais e na reorganização do backlog seguindo diretrizes ágeis. Era o começo do contato com processo, antes mesmo de saber que isso um dia viraria o centro da minha atuação no projeto.

### Hard Skills

- Estruturação de páginas web com HTML5 e CSS3: Sei fazer com autonomia;
- Lógica de programação com JavaScript: Sei fazer com ajuda;
- Desenvolvimento de rotas com Flask: Sei fazer com ajuda;
- Manipulação de dados em formato JSON: Sei fazer com autonomia;
- Versionamento com Git e GitHub: Sei fazer com ajuda;
- Metodologia Ágil SCRUM: Sei fazer com ajuda.

### Soft Skills

Durante o primeiro semestre, a equipe enfrentou desafios significativos: compreender o funcionamento do sistema, estabelecer uma dinâmica de trabalho coletivo eficiente, dominar as ferramentas utilizadas e equilibrar a gestão do tempo entre o projeto de API e as demais disciplinas.

Conflitos surgiram, como era esperado em um grupo em formação. A equipe esteve, por vezes, desorientada e desmotivada, o que resultou em entregas aquém do esperado.

Esses desafios foram o ponto de partida do meu desenvolvimento interpessoal. A necessidade de manter o grupo funcionando exigiu **colaboração** e **gestão de conflitos** em um momento em que eu ainda não tinha maturidade para exercê-las com consistência. Estar em um ambiente completamente novo ativou minha disposição de **aprendizado contínuo**: absorver ferramentas, processos e dinâmicas de equipe sem esperar que o caminho estivesse traçado. Foi também o semestre em que comecei a construir **vínculos de confiança** dentro do time, base para tudo que viria depois.

Essa experiência não foi em vão: ela acendeu a fagulha que, nos semestres seguintes, se tornaria realidade na função de Scrum Master.

---

## :heavy_check_mark: Em 2024-1

### Parceiro Acadêmico
[Faculdade de Tecnologia de São José dos Campos - Prof. Jessen Vidal](https://fatecsjc-prd.azurewebsites.net/)

No segundo semestre de parceria com a FATEC, o desafio apresentado foi o desenvolvimento de uma ferramenta para consolidar e gerenciar dados climáticos de estações meteorológicas do estado de São Paulo.
A solução deveria ser capaz de processar múltiplos arquivos CSV provenientes de diferentes estações, organizar os dados de forma consistente e possibilitar sua análise por meio de relatórios.

Com o [Zeus](https://github.com/FatecCoderHood/Coderhood), a equipe desenvolveu uma aplicação desktop em Java com interface JavaFX para carga e gestão de dados climáticos.

<details>
<summary>Tela Inicial da Aplicação Zeus</summary>
<b>Figura 4: Tela Inicial da Aplicação Zeus</b>
<img src="./images/sem2/Zeus-02.png" alt="Tela inicial da aplicação Zeus">
</details>

O sistema processa arquivos CSV do INMET em dois formatos distintos, automático e manual, detectando o formato e extraindo metadados diretamente do nome do arquivo. Os dados ingeridos são normalizados, classificados como válidos ou suspeitos com base em limites configuráveis por variável climática, e persistidos em um banco PostgreSQL com garantia de idempotência nas inserções.

<details>
<summary>Diagrama de entidade e relacionamento</summary>
<img src="./images/sem2/DER Zeus.jpg" alt="Diagrama de entidade e relacionamento">
<b>Figura 5: Diagrama Conceito do Banco de Dados</b>
</details>

A aplicação oferece CRUD de cidades e estações, relatório de valor médio por período, relatório de situação com a última leitura válida por variável, dados para geração de gráfico BoxPlot e tratamento de registros suspeitos.

### Tecnologias Utilizadas

- **Java:** Linguagem principal do projeto, utilizada para toda a lógica de negócio, processamento de arquivos e acesso ao banco de dados via JDBC.
- **JavaFX:** Framework para construção da interface gráfica desktop, com telas definidas em FXML e controllers vinculados por injeção de dependência.
- **PostgreSQL:** Banco de dados relacional utilizado para armazenamento dos registros climáticos. O schema é criado automaticamente na inicialização da aplicação, incluindo constraints de unicidade que garantem a integridade das inserções.
- **Git / GitHub:** Controle de versão e colaboração entre os membros da equipe ao longo das quatro sprints do projeto.

### Contribuições Pessoais

Foi o semestre em que acumulei as duas funções ao mesmo tempo, Scrum Master e desenvolvedor, e aprendi na prática o custo disso.

No lado técnico, fui responsável pelo módulo de gerenciamento de estações em Java com JavaFX. Implementei o CRUD completo respeitando a separação entre Controller, Service e Repository, com validação de duplicidade de sigla e controle de integridade referencial na exclusão. Também estruturei a base do módulo de dados suspeitos, criando o serviço e a interface inicial que o time desenvolveria nas sprints seguintes.

Na gestão, mantive o burndown atualizado, organizei as histórias de usuário e documentei o projeto. Era a primeira vez exercendo o papel de Scrum Master, e a documentação era uma forma de manter o controle sobre um processo que eu ainda estava aprendendo a conduzir.

### Hard Skills

- Desenvolvimento de aplicação desktop com Java e JavaFX: Sei fazer com ajuda;
- Arquitetura em camadas (Controller → Service → Repository): Sei fazer com autonomia;
- Operações CRUD com banco de dados relacional (PostgreSQL): Sei fazer com autonomia;
- Testes unitários com cobertura superior a 80%: Sei fazer com autonomia;
- Metodologia Ágil SCRUM: Sei fazer com autonomia.

### Soft Skills

O segundo semestre trouxe desafios diferentes, pois foi o primeiro em que atuei como Scrum Master. Essa posição no grupo exigiu uma postura com maior **responsabilidade**, já que a equipe necessitava de **liderança** e **organização**. Foi a primeira vez em que tive que fazer a **delegação de tarefas**, traçar um **planejamento** e praticar uma **resiliência** que até então eu não tinha tão bem maturada, pois nem sempre o planejado se converte em realizado.

Paralelamente, pude aprimorar minha **comunicação oral**, pois fui o responsável pelas apresentações de resultados ao cliente.
Por vezes, precisei participar de reuniões no lugar do P.O., fato que elevou o nível de **responsabilidade** sobre mim e me fez desenvolver maior senso de **integridade**.

Por fim, a necessidade do primeiro semestre havia se transformado no diferencial do segundo.

O segundo semestre trouxe desafios diferentes, pois foi o primeiro em que atuei como Scrum Master. Assumir essa função exigiu uma postura de maior **responsabilidade**, já que a equipe necessitava de **liderança** e **organização**. Foi a primeira vez em que tive que organizar pessoas e tarefas para maximizar o resultado do time, traçar um **planejamento** e praticar uma **resiliência** que até então não tinha tão bem maturada, pois nem sempre o planejado se converte em realizado.

Mais do que **delegar**, percebi que meu papel era desenvolver o time: entender o que cada integrante precisava para entregar melhor, não apenas **distribuir tarefas**. Essa percepção marcou o início de uma postura de cuidado com o crescimento das pessoas ao meu redor.

Paralelamente, aprimorei minha **comunicação oral** ao assumir as apresentações de resultados ao cliente. Por vezes, precisei participar de reuniões no lugar do P.O., fato que elevou o nível de **responsabilidade** sobre mim e exigiu maior senso de **integridade** na forma como me posicionava perante o cliente.

Por fim, a necessidade do primeiro semestre havia se transformado no diferencial do segundo.

---

## :heavy_check_mark: Em 2024-2

### Parceiro Acadêmico
[GSW](http://www.gsw.com.br)

Atuando no mercado desde 1991, a GSW é uma empresa nacional especializada em gerar soluções para o gerenciamento e controle de processos e negócios.

Neste semestre, a GSW nos trouxe o desafio de desenvolver uma aplicação para captura e armazenamento automatizado de notícias e dados estratégicos. A ferramenta deveria permitir o mapeamento de fontes de informação, a coleta periódica de conteúdo e a construção de um histórico estruturado, com possibilidade futura de análises baseadas em inteligência artificial.

Com o [Morpheus](https://github.com/Morpheus-Fatec/morpheus), a equipe entregou uma plataforma web de monitoramento de informações construída com Spring Boot no backend e Vue.js no frontend. O sistema realiza web scraping configurável de portais de notícias, com seletores CSS definidos por fonte cadastrada, permitindo adicionar novos portais pela interface sem alteração de código.

A coleta é agendada via expressão cron ajustável em runtime, com scraping e consumo de APIs externas executados em paralelo. As notícias capturadas passam por filtragem baseada em tags com suporte a sinônimos e regionalismos: o sistema expande automaticamente cada termo para suas variações antes de verificar o conteúdo, tanto na coleta quanto na consulta.

<details>
<summary>Diagrama de entidade e relacionamento Morphues</summary>
<img src="./images/sem3/DER Morpheus.png" alt="Diagrama de entidade e relacionamento Morphues">
<b>Figura 6: Diagrama Conceito do Banco de Dados</b>
</details>

A busca pelo usuário utiliza filtros dinâmicos compostos por título, conteúdo, autor, portal de origem e período, com resultados paginados.

### Tecnologias Utilizadas

- **Java / Spring Boot:** Linguagem de programação e framework utilizados para desenvolvimento do backend, responsável pelas rotas, regras de negócio e integração com o banco de dados.
- **JavaScript / Vue.js:** Framework JavaScript utilizado para desenvolvimento da interface do usuário, com comunicação via Axios para integração com a API REST.
- **MySQL:** Sistema gerenciador de banco de dados relacional utilizado para persistência das notícias e informações coletadas pelas fontes cadastradas.
- **Git / GitHub:** Ferramentas de versionamento e colaboração em equipe, com gestão de tarefas via GitHub Projects.

### Contribuições Pessoais

Foi o semestre em que deixei de codar de forma central e assumi a gestão integral das sprints. A contribuição técnica existiu, mas foi pontual: ajustes na integração entre front-end e back-end no módulo de APIs, substituindo rotas inconsistentes por padrões definitivos via Vue.js e Axios, corrigindo payloads e organizando a camada de serviço no back-end. O tipo de tarefa que aparece quando alguém precisa destravar o time, não quando está no centro do desenvolvimento.

A maior parte da energia foi dedicada à gestão. Manter o burndown, atualizar a documentação e garantir que as sprints tivessem critérios de aceitação claros eram as responsabilidades que mais pesavam. Era o terceiro semestre no projeto e o primeiro em dedicação exclusiva à função. A diferença foi perceptível: com menos alternância de contexto, o acompanhamento do time ficou mais próximo e as entregas mais previsíveis.

<details>
<summary>Gráfico Burndown</summary>
<img src="./images/sem3/BurnDownChart.png" alt="Burndown Chart">
<b>Figura 7 - Gráfico Burndown</b>
</details>

### Hard Skills

- Integração Vue.js + Axios com APIs REST: Sei fazer com ajuda;
- Desenvolvimento backend com Spring Boot: Sei fazer com ajuda;
- Padronização de payloads e rotas REST: Sei fazer com autonomia;
- Gestão técnica via GitHub Projects com critérios e estimativas por tarefa: Sei fazer com autonomia;
- Metodologia Ágil SCRUM: Sei fazer com autonomia.

### Soft Skills

No terceiro semestre, devido à atuação exclusiva como Scrum Master exigida pelo professor, minhas noções de **planejamento**, **liderança** e **organização e gestão do tempo** tiveram que evoluir. Foi nesse semestre que iniciamos a mensuração de tempo por meio de gráfico Burndown, exigindo mais do meu **pensamento analítico** e **tomada de decisão** para avaliar se uma tarefa caberia ou não na sprint, se necessitaria ser quebrada ou se poderia ser solicitado ao P.O. que negociasse com o cliente uma alteração no escopo.

Outro desafio do período foi a recomposição do time: novos integrantes com quem ainda não havia trabalhado trouxeram a necessidade de desenvolver minha **gestão de pessoas** e **gestão de conflitos**. Cada integrante tinha um perfil diferente, e reconhecer essas diferenças para adaptar minha abordagem a cada um foi o que manteve o grupo coeso. Somado a isso, o Product Owner possuía experiência consideravelmente superior à do grupo, o que elevou o nível de exigência das entregas e exigiu maior rigor no alinhamento entre as expectativas do cliente e a capacidade técnica real da equipe, reforçando minha **tomada de decisão estratégica**.

Apesar das adversidades, o semestre foi concluído com resultados satisfatórios. Evolui como **líder** ao perceber que a melhor forma de manter a coesão era tratar cada pessoa pelo que ela precisava, não pelo que era mais fácil para mim. Aprimorei também minha **resolução de problemas** ao estruturar atividades de pesquisa para tecnologias que o time ainda não dominava, transformando incertezas técnicas em tarefas acionáveis dentro da sprint, o que exigiu **resiliência** para sustentar o ritmo mesmo com o nível de exigência elevado.

---

## :heavy_check_mark: Em 2025-1

### Parceiro Acadêmico
[Visiona Tecnologia Espacial](https://www.visionaespacial.com.br/)

Criada em 28 de maio de 2012, a Visiona Tecnologia Espacial é resultante de uma iniciativa do Governo nacional de estimular a criação de uma empresa integradora na indústria espacial. Ela corresponde a uma das ações selecionadas como prioritárias no Programa Nacional de Atividades Espaciais (PNAE) para atender aos objetivos e às diretrizes da Política Nacional de Desenvolvimento das Atividades Espaciais (PNDAE) e da Estratégia Nacional de Defesa (END).

A empresa nos trouxe o desafio de desenvolver um sistema web para edição e análise de dados geoespaciais no contexto agrícola. A solução deveria permitir a manipulação de polígonos, análise de dados e acompanhamento por meio de dashboards, visando contribuir para a melhoria de modelos de inteligência artificial aplicados à classificação de áreas.

Com o [Demeter](https://github.com/Morpheus-Fatec/API_4S_Visiona_PolygonEditor), desenvolvemos uma plataforma web para visualização e edição de polígonos geoespaciais agrícolas. O sistema recebe arquivos GeoJSON com classificações automáticas geradas por modelos de IA, converte as geometrias para o formato MultiPolygon com validação estrutural e persiste os dados em PostgreSQL com a extensão PostGIS utilizando SRID 4326.

<details>
<summary>Diagrama de Entidades e Relacionacionamentos</summary>
<img src="./images/sem4/DER Demeter.png" alt="Ciclo de validação Talhão.">
<b>Figura 8: Diagrama de Entidades e Relacionacionamentos</b>
</details>
<br>

O fluxo de trabalho envolve três perfis: o analista edita manualmente as classificações sobre o mapa, desenhando polígonos diretamente na interface; o consultor revisa o trabalho do analista, anotando regiões com comentários georreferenciados e aprovando ou rejeitando o talhão. O sistema identifica automaticamente falsos positivos e falsos negativos comparando as classificações automáticas e manuais via operações espaciais, expondo essas divergências como camadas GeoJSON separadas para apoiar o refinamento dos modelos.

<details>
<summary>Ciclo de validação Talhão</summary>
<img src="./images/sem4/Ciclo de validação Talhão.png" alt="Ciclo de validação Talhão.">
<b>Figura 9: Ciclo de validação Talhão</b>
</details>
<br>

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

Foi o semestre tecnicamente mais denso que eu havia enfrentado até então. Voltei a acumular desenvolvimento e gestão, mas o nível de complexidade do que estava sendo construído era diferente de tudo que tinha feito antes.

A maior parte do meu trabalho foi no processamento geoespacial. Implementei os conversores entre GeoJSON e os objetos de geometria da biblioteca JTS, incluindo a validação de fechamento de anéis antes da persistência, algo que parece um detalhe até o momento em que uma geometria inválida quebra o banco. Todo o fluxo, do recebimento via API até o armazenamento no PostGIS e o retorno ao frontend, passou pelas minhas mãos.

Também implementei os endpoints de false positives e false negatives, que comparavam as classificações automáticas da IA com as classificações manuais dos analistas usando interseção espacial via PostGIS. Era o coração analítico do sistema: sem essas consultas, a equipe da Visiona não conseguia identificar onde os modelos estavam errando.

O controle de edição por perfil e o bloqueio de edição concorrente vieram da necessidade real de evitar que dois usuários sobrescrevessem o trabalho um do outro. Não foi uma decisão de arquitetura abstrata, foi uma resposta a um problema concreto.

Na gestão, o semestre foi mais equilibrado. A documentação e o backlog refletiam o que estava sendo de fato entregue, o que nem sempre havia sido o caso nos semestres anteriores.

### Hard Skills

- Modelagem e manipulação de dados geoespaciais com PostGIS: Sei fazer com autonomia;
- Conversão entre formatos geoespaciais (GeoJSON ↔ geometrias JTS) com validação estrutural: Sei fazer com autonomia;
- Consultas espaciais avançadas para análise de divergências entre classificações: Sei fazer com autonomia;
- Desenvolvimento de APIs REST com Spring Boot e controle de acesso por perfil: Sei fazer com autonomia;
- Desenvolvimento frontend com Vue.js e Leaflet: Sei fazer com ajuda;
- Deploy em ambiente AWS: Sei fazer com ajuda;
- Metodologia Ágil SCRUM: Sei fazer com autonomia.

### Soft Skills

No quarto semestre, minha **gestão de conflitos** foi testada de forma inédita. Uma divergência entre o Product Owner e um desenvolvedor, iniciada como discordância técnica, evoluiu para um conflito interpessoal que fragmentou o time. A resposta exigiu mais do que mediar: foi preciso encontrar um caminho alternativo, momento em que tive que aprimorar minha **criatividade**, meu **pensamento estratégico** e minha **iniciativa** de transformar um problema interpessoal em uma solução prática e aceitáve, criando tarefas intermediárias que integravam o trabalho das duas partes sem exigir interação direta entre elas. Essa solução nasceu de uma postura de busca por harmonia funcional, priorizando o que permitia o trabalho fluir em vez de forçar uma reconciliação que não viria.

Acumular gestão e desenvolvimento nesse semestre também exigiu mais da minha **organização e gestão do tempo** e do meu **pensamento analítico**, já que cada decisão técnica precisava ser tomada com clareza mesmo sob pressão interpessoal constante. A capacidade de avaliar cada situação com cautela antes de agir, pesando riscos e consequências, foi o que sustentou a qualidade das entregas.

O aprendizado mais duradouro foi de natureza humana: o papel do Scrum Master não é o de terapeuta, mas o de arquiteto de condições. Nem todo conflito será resolvido, mas é possível criar estruturas que permitam que o trabalho aconteça mesmo quando as pessoas estão com dificuldade de se enxergar. Essa consciência aprofundou minha **resiliência** de forma definitiva.

---

## :heavy_check_mark: Em 2025-2

### Parceiro Acadêmico
[Necto Systems](https://www.necto.com.br/)

A empresa nos trouxe o desafio de desenvolver uma solução corporativa integrada, baseada em arquitetura de microserviços, voltada ao processamento eficiente, integração e visualização de dados para apoio à tomada de decisão empresarial. O projeto abrangeu automação de ETL, exposição de APIs RESTful seguras e construção de dashboards analíticos responsivos.

Com o [NeoHorizon](https://github.com/FatecNeoHorizon/API_5S), a equipe entregou uma plataforma de inteligência operacional estruturada em modelo dimensional, com pipeline ETL automatizado integrado ao Jira, API REST segura com controle de acesso granular por perfil e dashboards interativos para análise de produtividade, custos e apontamentos de horas.

O sistema extrai issues diretamente da API do Jira via JQL, transforma os dados em fatos e dimensões seguindo o modelo estrela, e os carrega no banco PostgreSQL por meio da própria API backend. O controle de acesso é implementado com JWT stateless e quatro perfis distintos: DEVELOPER, MANAGER, ADMIN e ETL, cada um com permissões mapeadas por rota e método HTTP diretamente na cadeia de filtros do Spring Security.

Pela primeira vez, tivemos a oportunidade de trabalhar com o modelo de banco de dados Data Warehouse, onde exploramos conceitos fundamentais como modelagem dimensional, tabelas fato e dimensão, e o processo de ETL (Extract, Transform, Load). 

<details>
<summary>Data Warehouse</summary>
<img src="./images/sem5/DER NeoHorizon.png" alt="Data Warehouse.">
<b>Figura 10: Diagrama de Entidade e Relacionamento Data Warehouse</b>
</details>
<br>

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

Foi o semestre em que a visão de processo e a visão técnica se encontraram. Atuar como integrador do ecossistema significava que nenhuma decisão era isolada: a modelagem do banco afetava o ETL, o ETL dependia da autenticação, a autenticação precisava fazer sentido para todos os perfis de acesso. Tudo estava conectado, e manter essa coerência foi o trabalho central do semestre.

A modelagem dimensional foi o ponto de partida. Definir as três tabelas de fato com constraints de unicidade por granularidade não foi apenas uma escolha técnica, foi o que tornou o reprocessamento dos dados do Jira seguro. Sem idempotência nas inserções, qualquer reexecução do ETL geraria duplicidade. Pensar nisso antes de escrever a primeira linha do pipeline poupou problemas que seriam difíceis de rastrear depois.

O pipeline ETL em si foi construído para refletir essa mesma lógica: extração, transformação e carga em ordem de dependência, com autenticação JWT gerada no início e rastreabilidade do que foi inserido. A autenticação com perfil ETL separado das demais roles foi uma decisão que veio da necessidade de dar ao pipeline acesso de escrita sem comprometer os perfis operacionais do sistema.

A implementação do JWT com controle granular por rota e perfil, quatro perfis com permissões distintas, exigiu clareza sobre o que cada tipo de usuário deveria ou não conseguir fazer. Esse tipo de decisão não pode ser corrigido facilmente depois que o sistema está em uso.

A arquitetura em monorepo com submódulos Git independentes e pipelines de CI/CD fechou o ciclo. Cada módulo podia evoluir de forma autônoma, mas o ambiente local subia junto com um único comando. Foi o semestre em que tudo que havia aprendido antes, gestão, integração, decisões arquiteturais, operou ao mesmo tempo.

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

No quinto semestre, a decisão de deixar o cargo de Scrum Master foi consciente: três semestres no papel eram suficientes para reconhecer que reter conhecimento não serve a ninguém. Ceder o espaço para outro integrante assumir a função foi um exercício de **liderança** e **autodesenvolvimento**, pois exigiu abrir mão de um papel consolidado para me fortalecer tecnicamente onde ainda havia lacunas. Reconhecer onde eu precisava crescer e agir sobre isso exigiu **autoconhecimento** e maturidade que os semestres anteriores foram construindo.

A transição, porém, não significou afastamento da gestão. Atuei como **mentor** do novo Scrum Master, orientando sobre cerimônias, construção do Burndown, definição e quebra de tarefas, controle de prazos e **gestão de pessoas**. Transferir esse conhecimento de forma estruturada exigiu **comunicação**, **organização** e a capacidade de enxergar o potencial do outro e criar condições para seu desenvolvimento, uma dimensão de **cuidado com o crescimento alheio** que até então não havia explorado de forma consciente.

No eixo técnico, assumi a responsabilidade pelo rastreio de requisitos, conectando sprints, commits e pull requests pelo GitHub Projects. Essa abordagem aprofundou meu **pensamento analítico** e meu entendimento de processos, aprendizado que logo encontrou aplicação profissional na Kersys, onde pude planejar e executar projetos com a mesma lógica de **rastreabilidade** e **controle**.

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

O sexto semestre foi o mais amplo em termos de responsabilidade arquitetural. Voltei ao cargo de Scrum Master, o que significava garantir qualidade técnica e andamento do time simultaneamente.

A decisão mais estratégica foi a separação entre PostgreSQL e MongoDB por natureza dos dados: sensíveis no PostgreSQL, protegidos por Row Level Security e Flyway; públicos no MongoDB. Essa arquitetura surgiu da leitura correta do que a LGPD exigia para cada tipo de dado, não de uma preferência técnica.

O Keycloak foi um desafio assumido voluntariamente. A proposta partiu do professor, mas a implementação completa, fluxo PKCE, integração com auth.js e separação de perfis, foi conduzida por mim. O structured logging com structlog complementou esse ciclo de compliance, registrando operações sem expor dados pessoais.

O pipeline ETL processou arquivos geoespaciais BDGD e CSVs de indicadores DEC/FEC com cerca de cinco milhões de linhas, resolvido com processamento em chunks para garantir rastreabilidade sem comprometer a memória.

As GitHub Actions de validação de commits, templates de PR e criação automática de branches, junto ao burndown automático que lia o GitHub via GraphQL e se atualizava diariamente sem intervenção manual, foram iniciativas de processo que liberaram o time para focar na entrega. Os containers de MongoDB Express e pgAdmin no ambiente local fecharam o ciclo, reduzindo o atrito no onboarding dos desenvolvedores.

### Hard Skills

- Desenvolvimento de pipelines ETL em Python com FastAPI e MongoDB: Sei fazer com autonomia;
- Autenticação e autorização com Keycloak e OAuth 2.0 / PKCE: Sei fazer com autonomia;
- Logging estruturado com conformidade LGPD: Sei fazer com autonomia;
- Modelagem de dados em bancos relacionais e orientados a documentos: Sei fazer com autonomia;
- Orquestração de containers com Docker Compose: Sei fazer com autonomia;
- Metodologia Ágil SCRUM: Sei fazer com autonomia.

### Soft Skills

No sexto semestre, a volta ao cargo de Scrum Master trouxe os desafios mais complexos da graduação.

A decisão de organizar o time no início do semestre, estabelecendo regras de convivência com consentimento de todos, foi um exercício de **liderança** preventiva, **coragem** e **gestão de pessoas**. Antecipar os riscos antes que se tornassem problemas exigiu uma postura **deliberativa**, avaliando cenários e estruturando salvaguardas com cuidado. Gerir integrantes com posturas distintas e aplicar as regras propostas sem exceções foi o momento em que minha **integridade**, **ética profissional** e **responsabilidade** foram mais testadas.

Acumular as funções de Scrum Master e Product Owner na primeira sprint, participando da reunião com o cliente no lugar do P.O. e definindo requisitos, arquitetura e user stories, exigiu **tomada de decisão** contínua, **organização e gestão do tempo** no limite e a **confiança** de assumir um papel para o qual não havia sido designado, mas que o momento exigia.

Trabalhar com três perfis distintos de Product Owner ao longo do semestre, incluindo um com postura de mínimo esforço oposta à minha exigência pessoal, desenvolveu minha **negociação**, **flexibilidade** e **adaptabilidade** de forma prática e inevitável. Respeitar uma visão diferente da minha sem abrir mão do que era essencial foi um dos equilíbrios mais difíceis do semestre.

Assumir entregas técnicas de integrantes que não cumpriram suas tarefas, acumulando desenvolvimento e gestão na sprint final, consolidou minha **resiliência** e reforçou que **liderança** real significa garantir a entrega independentemente das circunstâncias.

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
