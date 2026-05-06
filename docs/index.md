# MonitoraEA

Bem-vindo à documentação oficial do sistema **MonitoraEA**.

Este espaço foi criado para centralizar o conhecimento do sistema, facilitando manutenção, evolução e onboarding de novos membros da equipe.

---

## 📌 Apresentação do Sistema

O Sistema MonitoraEA é uma plataforma integrada de dados e visualização em desenvolvimento continuado, voltada ao monitoramento e fortalecimento da Política Nacional de Educação Ambiental (PNEA), contemplando múltiplas escalas temporais, espaciais e institucionais. Seu objetivo é disponibilizar uma infraestrutura digital capaz de reunir, organizar e interpretar informações provenientes de múltiplas fontes e escalas, apoiando a gestão, o acompanhamento e a avaliação das ações e redes de educação ambiental no país.

A proposta parte do reconhecimento de que a efetividade da PNEA depende de processos contínuos de monitoramento participativo, geração sistemática de dados, articulação interinstitucional e aprendizado social. Nesse contexto, o MonitoraEA busca propor e consolidar um sistema público e colaborativo de gestão da informação, que favoreça a integração entre programas, instituições e territórios, fortalecendo as práticas de governança ambiental em rede.

Na etapa atual, o sistema opera a partir de cinco perspectivas de monitoramento e avaliação de componentes do campo da Educação Ambiental. Ainda, se dedica ao desenvolvimento de quatro novas frentes: i) arquitetura de dados voltada à análise de riscos climáticos sob a perspectiva da educação ambiental, com foco na construção de referenciais e indicadores que permitam compreender como as ações educativas contribuem para o incremento das capacidades adaptativas nos territórios[^1]; ii) ferramentas endógenas de análise e modelagem de redes, a partir de dados de conexões e parcerias informados pelos usuários do sistema; iii) um protocolo de gamificação, voltado a ampliar o engajamento dos usuários e promover processos contínuos de aprendizagem; iv) um protocolo de pesquisas cíclicas, destinado à coleta e atualização participativa de dados; v) um programa de formação de heavy-users, denominados articuladores locais do MonitoraEA, responsáveis por apoiar a validação dos instrumentos e o fortalecimento das comunidades de prática nos territórios[^2] e, vi) o desenvolvimento da rede social distribuída do MonitoraEA, com base no protocolo ActivityPub (protocolo aberto que permite redes sociais diferentes se comunicarem entre si de forma descentralizada), que permitirá integrar o MonitoraEA ao Fediverso[^3].

[^1]: Desenvolvimentos realizados dentro do escopo do projeto “Capacidade adaptativa em perspectiva policêntrica: monitoramento, avaliação e impactos sinérgicos de Políticas Públicas de Educação Ambiental para o enfrentamento das Mudanças Climáticas, em múltiplas escalas”, realizado a partir do INPE, com fomento do CNPQ (Processo CNPQ n.º 406595/2022-4) e do DEA/MMA.

[^2]: Desenvolvimentos realizados dentro do escopo do projeto “Desenvolvimento de estudos, protocolos, planos para o incremento do Programa MonitoraEA”, realizado a partir do INPE, com fomento do DEA/MMA, executado via encomenda ao CNPQ (Processo CNPQ n.º 422851/2025-6).

[^3]: O Fediverso é um ecossistema de plataformas sociais descentralizadas, interconectadas por protocolos abertos como ActivityPub, permitindo interoperabilidade entre serviços distintos sem dependência de um provedor central. Ele engloba implementações variadas que adotam modelos de interação federada, como Mastodon (microblog), Pixelfed (compartilhamento de imagens), PeerTube (vídeo distribuído), Friendica (rede social geral) e Lemmy (agregador de links e fóruns), formando uma rede ampla e heterogênea de comunicação distribuída.

Estes desenvolvimentos e integrações ampliarão significativamente o potencial de mobilização, engajamento e comunicação entre os diferentes atores do campo da Educação Ambiental, possibilitando a criação de um espaço digital descentralizado, público e interativo. Com isso, o MonitoraEA tende a se consolidar como o lócus virtual da Educação Ambiental no Brasil, articulando instituições, educadores, gestores e comunidades em torno de práticas compartilhadas de monitoramento e aprendizagem.

Essa dimensão social e comunicativa é também estratégica para o avanço de uma cultura interna ao campo da Educação Ambiental orientada a processos de monitoramento e avaliação (M&A), contribuindo para uma visão mais integrada e sistêmica da EA como política pública de caráter estruturante, e não apenas como um conjunto de iniciativas pontuais.

Do ponto de vista técnico, o sistema adota uma arquitetura modular, com módulos de coleta, integração e visualização de dados, projetados para operar com protocolos abertos e interoperáveis, assegurando a integração com bases institucionais existentes e o acesso público às informações produzidas.

Entre os avanços alcançados até o momento, destacam-se a construção participativa de indicadores e o consequente desenho da arquitetura de dados do sistema, alinhada a esses referenciais. Avançou-se também na definição de protocolos de interação com os usuários, estruturados segundo a lógica de comunidades, e na implementação de ferramentas para a geração colaborativa de dados e conteúdos, voltadas à ampliação da qualidade e da diversidade das informações coletadas.

Já entre os resultados esperados, situam-se a consolidação do MonitoraEA como uma infraestrutura nacional de dados e informações sobre Educação Ambiental, a integração plena da plataforma ao Fediverso e o fortalecimento das capacidades adaptativas locais por meio de processos colaborativos e participativos de produção de conhecimento.

Com uma concepção orientada à integração entre ciência, tecnologia e políticas socioambientais, o Sistema MonitoraEA representa um passo decisivo rumo à criação de instrumentos de governança adaptativa e de infraestruturas digitais abertas, capazes de ampliar a transparência, a eficiência e a capacidade de resposta das políticas públicas voltadas à sustentabilidade e à justiça socioambiental.

Por fim, é importante destacar que este relatório se limita à apresentação da dimensão tecnológica de sustentação do Sistema MonitoraEA, com foco em sua arquitetura de dados, protocolos e processos de desenvolvimento. O sistema, contudo, atua de forma integrada em outras dimensões — político-institucionais e pedagógicas — que, embora fundamentais para sua efetividade, extrapolam o escopo deste documento e serão tratadas em relatórios complementares.

---

### 👉 Contexto Institucional e Desafios Estruturantes

O Sistema MonitoraEA, em desenvolvimento desde 2016, foi criado para suprir uma lacuna histórica na implementação da Política Nacional de Educação Ambiental (PNEA), estabelecida pela Lei nº 9.795/1999 e regulamentada pelo Decreto nº 4.281/2002. A plataforma surge como resposta à necessidade de consolidar uma infraestrutura nacional capaz de integrar informações, iniciativas e atores distribuídos em múltiplas escalas — temporais, espaciais e institucionais — de modo a apoiar o monitoramento, a avaliação e o fortalecimento das ações de Educação Ambiental no país. Seu desenvolvimento insere-se no esforço de aprimorar os instrumentos de gestão da PNEA, reconhecendo o caráter transversal e federativo da política e a importância crescente da Educação Ambiental como componente estratégico da governança socioambiental brasileira.

Ao longo das últimas décadas, a PNEA tem se apoiado em uma rede ampla de instituições públicas, movimentos sociais, coletivos educadores e universidades, articulados em torno de espaços de governança compartilhada, como a Comissão Interinstitucional de Educação Ambiental (CIEA) nos estados e o Órgão Gestor da PNEA, composto pelo Ministério do Meio Ambiente (MMA) e pelo Ministério da Educação (MEC). Apesar dessa trajetória consolidada, o campo enfrenta desafios significativos quanto à integração sistêmica de informações, monitoramento de políticas e avaliação dos impactos educacionais e territoriais de suas ações.

Entre os principais desafios identificados estão a fragmentação dos dados e das iniciativas, a ausência de protocolos unificados de coleta e análise, a dispersão institucional entre esferas de governo e a baixa capacidade de retroalimentação das informações produzidas nos diferentes níveis federativos. Essa realidade limita a efetividade da política pública, reduzindo a capacidade de planejar e avaliar de forma integrada os avanços da Educação Ambiental como eixo estruturante da transição socioecológica.

Nesse cenário, o MonitoraEA emerge como uma resposta estratégica à necessidade de construir uma infraestrutura nacional de dados e informações que apoie a gestão adaptativa da PNEA, fortalecendo sua base empírica e ampliando sua capacidade de aprendizado institucional. O sistema é concebido como parte de um esforço coordenado entre o Instituto Nacional de Pesquisas Espaciais (INPE) — no âmbito do Laboratório de Análise e Desenvolvimento de Indicadores para a Sustentabilidade (LADIS)[^4], a Articulação Nacional de Políticas Públicas de Educação Ambiental (ANPPEA), o Departamento de Educação Ambiental e Cidadania do Ministério do Meio Ambiente e Mudança do Clima (DEA/MMA), bem como de uma ampla rede de atores vinculados ao campo da Educação Ambiental no Brasil, em diálogo com órgãos gestores estaduais e municipais de EA.

[^4]: Neste arranjo institucional, o LADIS/INPE assume a função de coordenar os esforços para o desenvolvimento técnico-científico, especificamente em relação aos processos participativos de construção de indicadores, e tecnológico, no contexto da concepção e desenvolvimento da plataforma do Sistema MonitoraEA, bem como a gestão de seu banco de dados.

A proposta se insere no marco conceitual da governança adaptativa, que reconhece a necessidade de mecanismos flexíveis e participativos de gestão diante de cenários de incerteza, complexidade e mudanças climáticas. Nesse sentido, o MonitoraEA busca contribuir para a consolidação de uma cultura institucional orientada por dados, em que o monitoramento e a avaliação (M&A) se tornem componentes permanentes do ciclo de políticas públicas, articulando informação, participação e aprendizado social.

Em síntese, o sistema nasce da convergência entre demandas históricas da PNEA e novos desafios de governança ambiental, representando um avanço na direção de uma política mais integrada, transparente e responsiva aos contextos territoriais. Seu desenvolvimento constitui uma etapa essencial para a modernização da gestão da Educação Ambiental no Brasil e para a consolidação de mecanismos inovadores de monitoramento, avaliação e cooperação federativa.

O Quadro 1 apresenta a matriz de stakeholders do Sistema MonitoraEA, destacando os principais grupos envolvidos, seus papéis e tipos de contribuição no processo de desenvolvimento, operação e consolidação da plataforma.

**Quadro 1 – Matriz de Stakeholders do Sistema MonitoraEA**

| Grupo / Nível                                          | Instituição ou Atores Principais                                                                                                       | Papel / Função no Sistema                                                                                                                                                                    | Tipo de Contribuição              | Grau de Engajamento[^5] |
| ------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------- | ----------------------- |
| Coordenação Técnica Nacional                           | Instituto Nacional de Pesquisas Espaciais (INPE) – Laboratório de Análise e Desenvolvimento de Indicadores de Sustentabilidade (LADIS) | Coordenação técnica e científica geral; desenvolvimento da infraestrutura tecnológica; gestão de repositórios e versionamento; manutenção da arquitetura e banco de dados                    | Técnica, científica e operacional | A                       |
| Gestão Social e Mobilização                            | Articulação Nacional de Políticas Públicas de Educação Ambiental (ANPPEA)                                                              | Gestão social da plataforma; coordenação da Rede Nacional de Articuladores Locais; validação colaborativa de dados; engajamento e suporte aos usuários; curadoria de conteúdos e comunidades | Social, institucional e formativa | A                       |
| Coordenação Interinstitucional e Governança da PNEA    | Departamento de Educação Ambiental e Cidadania (DEA/MMA)                                                                               | Articulação com políticas públicas federais e colegiados (ProNEA, PEEA, CIEA, CECSA, etc.); definição de diretrizes estratégicas                                                             | Política e institucional          | A                       |
| Articulação Educacional e Política Interministerial    | Ministério da Educação (MEC) – Coordenação-Geral de Educação Ambiental para a Diversidade e Sustentabilidade (CGAMS/SECADI)            | Integração entre políticas de EA e educação formal; apoio à institucionalização da plataforma no âmbito do MEC                                                                               | Política e técnica                | B                       |
| Rede de Articuladores Locais (Heavy Users)             | Educadores e representantes de instituições estaduais, municipais e da sociedade civil                                                 | Operação territorial; mobilização local; validação participativa de dados; apoio a novos usuários; multiplicação das práticas de M&A                                                         | Social, formativa e técnica       | A                       |
| Instituições Parceiras Estaduais e Municipais          | Secretarias Estaduais e Municipais de Meio Ambiente e Educação; CIEAs e CIMEAs                                                         | Uso institucional da plataforma; integração com bases locais; retroalimentação de dados territoriais                                                                                         | Institucional e operacional       | B                       |
| Universidades e Centros de Pesquisa                    | Universidades federais, estaduais (UFPA, UFRB, UFRJ,UNB, USP, etc.) e privadas (UNIVALI)                                               | Pesquisa aplicada, desenvolvimento metodológico de indicadores e apoio técnico à formação de articuladores                                                                                   | Científica e formativa            | B                       |
| Organizações da Sociedade Civil e Coletivos educadores | ONGs, movimentos socioambientais, redes de EA e coletivos regionais                                                                    | Produção descentralizada de dados; mobilização e disseminação; experimentação metodológica                                                                                                   | Social e participativa            | B                       |
| Comitês e Colegiados de Controle Social                | CIEA, CIMEA, CECSA, Conselhos Gestores, Comitês de Bacia Hidrográfica                                                                  | Uso dos dados para acompanhamento e avaliação de políticas públicas; validação e planejamento participativo                                                                                  | Institucional e deliberativo      | B                       |
| Provedores e Infraestrutura de Dados                   | AWS (Amazon Web Services), Microsoft Azure (programas Nonprofit)                                                                       | Hospedagem em nuvem, segurança e backups automatizados, monitoramento de desempenho                                                                                                          | Técnica e operacional             | C                       |
| Usuários Gerais e Visitantes do Portal                 | Educadores, gestores públicos, estudantes, sociedade civil                                                                             | Acesso a dados, painéis e dashboards; uso educativo e informacional                                                                                                                          | Educacional e comunicacional      | C                       |

[^5]: Grau A: Atuação central e contínua no desenvolvimento e operação do sistema; Grau B: Participação regular e articulada com projetos e políticas associadas; Grau C: Participação indireta, pontual ou baseada em integração tecnológica.

---

### 👉 Missão, Princípios e Diretrizes Estratégicas do Sistema MonitoraEA

#### 👉 Missão

Sistema MonitoraEA tem como missão consolidar-se como o sistema nacional de informações em Educação Ambiental no Brasil, promovendo o registro, o monitoramento e a avaliação colaborativa de iniciativas, políticas públicas e instâncias de Educação Ambiental em todo o território nacional. O portal do sistema é desenvolvido visando fortalecer redes, gerar dados confiáveis e apoiar a formulação e a avaliação de políticas públicas e a diversidade de iniciativas em educação ambiental, visando contribuir para a transformação socioambiental sustentável no país.

Seu papel é atuar como o lócus virtual de integração de informações sobre educadores ambientais, organizações educadoras, espaços formativos, iniciativas e políticas públicas, tornando-as acessíveis, de forma aberta, participativa e descentralizada. Ao oferecer instrumentos para a geração e análise de dados, e ao criar um espaço interativo de engajamento e comunicação, o sistema contribui para o fortalecimento de uma cultura colaborativa de monitoramento e avaliação (M&A) no campo da Educação Ambiental.

#### 👉 Visão Estratégica

O MonitoraEA projeta-se como uma infraestrutura pública de dados, comunicação e colaboração, orientada pelos princípios da governança adaptativa e da ciência cidadã. A visão de longo prazo é constituir um ecossistema federado de informação e engajamento, no qual diferentes atores — governos, instituições, coletivos e indivíduos — possam produzir, compartilhar e utilizar informações para qualificar decisões e fortalecer capacidades adaptativas em seus territórios.

Essa visão inclui a integração da plataforma ao Fediverso, por meio do protocolo ActivityPub, ampliando o potencial de mobilização e conectividade entre atores do campo da Educação Ambiental. Ao combinar funcionalidades de rede social, mecanismos de descoberta e ferramentas analíticas, o MonitoraEA tende a se consolidar como o ambiente digital central de articulação, aprendizado e inovação em Educação Ambiental no Brasil.

#### 👉 Princípios Orientadores

O desenvolvimento e a operação do MonitoraEA são guiados por um conjunto de princípios que refletem seu compromisso com a transparência, a participação e a sustentabilidade institucional. São eles:

- Interoperabilidade e abertura, visando a promoção da integração de diferentes bases e sistemas institucionais por meio de padrões abertos e protocolos interoperáveis.
- Participação e colaboração, orientada ao incentivo da coprodução de dados e conhecimentos em redes distribuídas de atores, apoiadas por processos estruturados e ferramentas compartilhadas
- Transparência e rastreabilidade, para garantir acesso público às informações e aos processos de validação e atualização, preservando a possibilidade de confidencialidade quando necessário.
- Ciência cidadã e aprendizado social, por meio da valorização da produção coletiva de conhecimento e fomenta processos reflexivos e dialógicos, assegurando aprendizado coletivo em consonância com os princípios da Educação Ambiental.
- Descentralização e governança adaptativa, para o fortalecimento da autonomia dos territórios e a capacidade de resposta a mudanças sociais e ambientais com base em dados e informações qualificadas.
- Inovação contínua, para a integração de tecnologias emergentes e metodologias participativas para ampliar o alcance e a efetividade do sistema.

#### 👉 Diretrizes para Consolidação

A consolidação do MonitoraEA como sistema nacional de informações sobre a EA depende da articulação entre dimensões tecnológicas, político-institucionais e pedagógicas. As diretrizes estratégicas incluem:

- Integração federativa e multiescalar, orientada à promoção da interoperabilidade entre dados e processos produzidos por entes federativos e organizações da sociedade civil, fortalecendo a cooperação interinstitucional e a articulação entre diferentes níveis e escalas de governança da Educação Ambiental;
- Engajamento e formação de usuários, com a estruturação de processos formativos voltados a diferentes perfis de atores, estimulando a apropriação dos instrumentos de monitoramento e avaliação e a consolidação de uma cultura colaborativa de uso dos dados;
- Sustentabilidade tecnológica e operacional, com a garantia de uma infraestrutura robusta, escalável e aderente aos princípios de software livre e dados abertos, assegurando a manutenção e evolução contínua da plataforma;
- Validação colaborativa e atualização contínua, com a incorporação de protocolos participativos de verificação, revisão e aprimoramento das informações e indicadores, fortalecendo a confiabilidade e legitimidade dos dados;
- Ampliação da visibilidade, do impacto público e da institucionalidade, com o fortalecimento do MonitoraEA como lócus virtual de informações da Educação Ambiental no Brasil. Sua consolidação depende de mecanismos institucionais de indução e adesão, promovidos pelo Órgão Gestor da PNEA, que garantam o uso sistemático e descentralizado do sistema em escala federativa;
- Avançar de um modelo baseado em projetos para mecanismos estruturais e permanentes de financiamento e gestão. Considera-se estratégica a criação de um Plano Orçamentário (PO) específico, apoiado por um arranjo institucional envolvendo MCTI, MMA e MEC, de forma a garantir a continuidade e o fortalecimento do MonitoraEA como infraestrutura pública nacional da Política Nacional de Educação Ambiental.

---
