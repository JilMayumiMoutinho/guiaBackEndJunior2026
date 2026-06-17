Projeto que explore o uso da Inteligência Artificial como ferramenta de aprendizagem ativa. Este projeto prático, alinha pensamento crítico, curadoria de fontes e organização do conhecimento para criar um Caderno Temático no NotebookLM.

**Contexto e Objetivos:**
O caderno temático foi desenvolvido com o objetivo de auxiliar pessoas que desejam ingressar na área de Tecnologia da Informação (TI), com foco na carreira de desenvolvedor backend. A proposta é reunir os principais conceitos, fundamentos e práticas essenciais que um iniciante precisa dominar ao longo da sua jornada até se tornar uma qualificação profissional.

**Curadoria de Fontes:**
É recomendável que realize uma curadoria de fontes confiáveis e que tenham ligação com o mesmo ponto de vista do que acredito que seja melhor seguir (por exemplo, se já há uma linguagem de programação que se tem conhecimento ou mais afinidade). Foi utilizado as mesmas 17 fontes de outro projeto e adicionado mais 10.
Engenharia de Prompts e "Cicatrizes": A ideia do projeto é realizar um caderno de estudos, resumos ou apenas entender como é conversar com um expecialista de acordo com as fontes informadas. Se adicionarmos todos os livros de Shelock Homes, poderiamos falar com ele. Se adicionarmos os livros e estudos de Beijamin Graham podemos pedir conselhos a ele. Meu estudo quis entender se, sendo uma IA, se eu fornecesse as mesmas fontes que outra pessoa, se ele faria perguntas para melhor personalizar o resultado para mim, ou se não faria perguntas e daria resultados iguais ou diferentes. No fim, tanto para 17 quanto para 27 fontes o resultado foi muito parecido, no roteiro, na foram de apresentar, inclusive 2 imagens foram iguais. 
O glossário e os prompts para uso futuro, também são bastante similares, entretanto entendo que são itens que de fato, fato que independente da pessoa, sendo iniciante, os itens seriam os mesmos.
O que foi bastante diferente foi o cronograma por semanas sugerido para os estudos. Que em ambos os casos foi sugerido para mim, e não tem sugerido no caderno do meu colega.

**Resumo estruturado: **
A apresentação "O guia definitivo do desenvolvedor backend 2026" resume os pilares necessários para quem deseja iniciar ou se especializar nesta carreira. Abaixo, o conteúdo está condensado em quatro parágrafos principais:
O desenvolvimento backend é definido como o "motor" ou a "cozinha" de um sistema, operando no lado do servidor (server-side) para gerenciar a lógica de negócio, o processamento de dados e a segurança que o usuário não vê. Enquanto o frontend foca na interface e na interatividade, o backend é o "coração" que processa requisições complexas e garante que as regras de negócio sejam seguidas, servindo como a espinha dorsal de qualquer aplicação web ou móvel.
Para o mercado de 2026, o guia identifica linguagens que dominam nichos específicos: o Python lidera em projetos de Inteligência Artificial e dados, enquanto o Node.js (com TypeScript) é a escolha padrão para aplicações web escaláveis e seguras. O ecossistema também valoriza o Java para sistemas corporativos robustos, além de linguagens como Go e Rust, voltadas para alta performance e segurança crítica de memória.
Os fundamentos técnicos essenciais envolvem o domínio da lógica de programação e de bancos de dados, sendo o SQL (PostgreSQL) considerado um requisito obrigatório e não negociável para profissionais da área. Outro pilar fundamental é o design de APIs REST, que estabelecem contratos de comunicação padronizados entre sistemas, permitindo a troca de informações de forma rápida, segura e escalável através do protocolo HTTP.
Por fim, o roteiro de estudos avança para a infraestrutura e práticas de portfólio, introduzindo a containerização com Docker e a implantação em nuvem através de provedores como AWS ou Azure. O guia encoraja a criação de projetos práticos, como encurtadores de URL, rastreadores de tarefas CLI e APIs de e-commerce, que servem para validar as competências técnicas diante de recrutadores e consolidar o aprendizado do nível iniciante ao avançado.

**Glossário:**
    • API REST (Representational State Transfer): Um estilo de arquitetura que utiliza o protocolo HTTP para permitir a comunicação entre sistemas. Baseia-se em recursos identificados por URIs e verbos padrão (GET, POST, PUT, DELETE).
    • Backend: Refere-se ao "lado do servidor" (server-side). É responsável pela lógica de negócio, processamento de dados, APIs e integração com bancos de dados.
    • Banco de Dados Relacional (SQL): Armazena dados em tabelas com estruturas predefinidas (linhas e colunas). Exemplos dominantes incluem PostgreSQL e MySQL.
    • Banco de Dados Não Relacional (NoSQL): Oferece flexibilidade para dados não estruturados, utilizando modelos como documentos (MongoDB), chave-valor (Redis) ou grafos (Neo4j).
    • CI/CD (Continuous Integration / Continuous Deployment): Práticas de automação que permitem testar e implantar código de forma contínua e confiável, utilizando ferramentas como GitHub Actions.
    • Docker / Containerização: Tecnologia que permite empacotar uma aplicação e todas as suas dependências em um "container" isolado, garantindo que o software funcione da mesma forma em qualquer ambiente.
    • Git / GitHub: Git é o sistema de controle de versão distribuído usado para rastrear mudanças no código. GitHub é a plataforma de nuvem que hospeda esses repositórios e facilita a colaboração.
    • Idempotência: Conceito onde uma operação produz o mesmo resultado, não importa quantas vezes seja repetida (ex: métodos GET, PUT e DELETE).
    • JWT (JSON Web Token): Um padrão de segurança usado para compartilhar informações autenticadas entre o cliente e o servidor de forma segura e compacta.
    • Statelessness (Apatridia): Princípio da arquitetura REST onde o servidor não armazena o estado da sessão do cliente; cada requisição deve conter todas as informações necessárias para ser processada.
    • TypeScript: Um superconjunto do JavaScript que adiciona tipagem estática, tornando o código backend (Node.js) mais robusto, escalável e fácil de testar.

**Conjunto de prompts reutilizáveis que possam apoiar futuras revisões sobre o tema:**
    • Para Explicar Conceitos Complexos
"Explique o conceito de [Inserir Conceito, ex: Idempotência em APIs] como se eu fosse um iniciante na programação. Use uma analogia do mundo real e mostre um exemplo prático de código em [Linguagem, ex: Python]."
    • Para Planejamento de Carreira e Roadmaps
"Atuando como um arquiteto de sistemas sênior, crie um plano de estudos de 4 semanas para eu dominar [Tecnologia, ex: Docker e Kubernetes]. Foque no que é essencial para o mercado de trabalho em 2026 e sugira 2 mini-projetos práticos."
    • Para Criação de Portfólio
"Sugira 3 ideias de projetos de nível [Iniciante/Intermediário] para meu portfólio backend usando [Stack, ex: Node.js e PostgreSQL]. Para cada projeto, liste as principais funcionalidades (CRUD) e quais desafios técnicos ele demonstra que eu superei."
    • Para Preparação de Entrevistas Técnicas
"Com base nos padrões da indústria de 2026, liste as 5 perguntas de entrevista mais comuns sobre [Tema, ex: Segurança em APIs REST] e forneça respostas detalhadas que demonstrem conhecimento sênior em [Linguagem, ex: Java]."
    • Para Revisão de Segurança (Review de Código)
"Analise o seguinte trecho de código backend em busca de vulnerabilidades comuns do OWASP Top 10 (como SQL Injection ou falhas de autenticação). Sugira como corrigir cada problema identificado: [Colar seu código aqui]."
    • Para Atualização de Tendências
"Quais são as principais mudanças e tecnologias emergentes no desenvolvimento backend para o ano de 2026? Foque especificamente em IA integrada, arquitetura de microsserviços e computação em nuvem."
