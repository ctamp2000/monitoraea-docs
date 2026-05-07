# Módulos

## 📌 MÓDULOS E FUNCIONALIDADES

### 👉 Diretrizes de desenvolvimento e organização da arquitetura do sistema

O desenvolvimento do Sistema MonitoraEA pauta-se por princípios técnicos que asseguram coerência com sua missão pública e com as diretrizes estratégicas da Política Nacional de Educação Ambiental (PNEA). Assim, a plataforma adota uma arquitetura modular, aberta e interoperável, estruturada para garantir escalabilidade, transparência e colaboração distribuída entre diferentes instituições e territórios.

Essa concepção permite a integração progressiva de novos módulos e serviços, favorecendo tanto a atualização tecnológica contínua quanto a expansão de suas funcionalidades analíticas e participativas. Cada módulo é projetado para operar de forma autônoma, mas integrada, assegurando flexibilidade operacional e robustez sistêmica.

Na seção seguinte são apresentados os principais componentes da arquitetura, incluindo os módulos de coleta, integração, visualização e interação social, bem como suas inter-relações e diretrizes de desenvolvimento.

### 👉 Estrutura Modular e Componentes do Sistema

A partir da lógica de comunidades descrita na seção 2, o Sistema MonitoraEA organiza-se em uma arquitetura modular e interoperável, que sustenta o ciclo completo de produção, integração, visualização e uso colaborativo dos dados. Cada módulo técnico responde a um conjunto específico de funções, mas opera de modo articulado aos demais, compondo uma infraestrutura digital coesa, expansível e orientada à colaboração entre múltiplos atores institucionais e territoriais.

Os módulos foram projetados para garantir interoperabilidade, escalabilidade e transparência, adotando padrões abertos de comunicação e integração com bases institucionais externas. Essa estrutura assegura a continuidade evolutiva do sistema, permitindo incorporar novas funcionalidades, ferramentas e protocolos sem comprometer a coerência arquitetônica.

Os quatro módulos principais que compõem a plataforma são apresentados a seguir.

#### 👉 Módulo de geração descentralizada e colaborativa de dados e informações

O módulo de cadastro e atualização de informações do MonitoraEA é responsável pela entrada, atualização e validação colaborativa dos dados, concebido para operar em ambientes participativos e distribuídos. Seu desenho busca privilegiar a acessibilidade, a usabilidade e a diversidade territorial, assegurando a representatividade dos registros e a coprodução de conhecimento em escala nacional. Inclui ferramentas de auto-registro e autoavaliação de iniciativas e espaços.

Este módulo integra ferramentas para operação das funcionalidades típicas aos membros das comunidades finalísticas de M&A do Sistema MonitoraEA. A seguir, apresenta-se, no quadro 7, uma visão consolidada dos componentes principais e suas funcionalidades.

**Quadro 7 – Matriz de funcionalidades do módulo de geração descentralizada e colaborativa de dados e informações.**

| Componente                                                                         | Função / Objetivo                                                | Principais Funcionalidades                                                                                              |
| ---------------------------------------------------------------------------------- | ---------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- |
| Sistema de Cadastro de Iniciativas                                                 | Registrar, atualizar e validar iniciativas de forma colaborativa | Formulários dinâmicos; Campos contextuais; Validação em tempo real; Salvamento automático; Upload de documentos         |
| Ferramenta WebGIS para a definição da área de abrangência geográfica da iniciativa | Suporte à análise territorial e visualização espacial            | Mapas interativos; Delimitação de áreas; Sobreposição de camadas; Geocodificação; Exportação de mapas                   |
| Sistema de Autoavaliação                                                           | Monitorar e avaliar iniciativas e ações em M&A                   | Indicadores contextuais; Escalas de avaliação múltiplas; Feedback imediato; Comparação temporal; Relatórios automáticos |
| Declaração de Conexões e Parcerias                                                 | Organizar e acompanhar relações institucionais                   | Cadastro de atores; Tipologia de colaborações; Mapa de rede; Histórico de colaborações                                  |
| Marcos e eventos relevantes para a iniciativa (Linha do Tempo)                     | Registrar eventos e marcos do ciclo de vida das iniciativas      | Registro de eventos; Categorização temporal; Upload de evidências; Visualização cronológica interativa                  |

Cada componente foi projetado para assegurar consistência, rastreabilidade e integridade dos dados, permitindo a operação do MonitoraEA em ambientes distribuídos e colaborativos. A integração do cadastro estruturado, da definição da área de abrangência geográfica, da autoavaliação e da declaração de conexões e parcerias garante que as informações sejam precisas, atualizadas e auditáveis, oferecendo suporte confiável para monitoramento, avaliação e tomada de decisão nas políticas e iniciativas de Educação Ambiental em âmbito nacional.

#### 👉 Módulo de Integração e Interoperabilidade

O Módulo de Integração e Interoperabilidade[^1] constitui o núcleo técnico da arquitetura de dados do MonitoraEA, sendo responsável pela integração, padronização e sincronização das informações provenientes de múltiplas fontes. Sua função central é garantir a consistência, rastreabilidade e interoperabilidade entre os dados inseridos na plataforma e as bases externas, consolidando o MonitoraEA como uma infraestrutura nacional de informação pública.

[^1]: Módulo implementado, consumido pelos elementos da plataforma (portal e área de colaboração). A relação com outros sistemas externos está em fase de planejamento.

O módulo é projetado para operar com protocolos abertos de intercâmbio de dados, como APIs RESTful e serviços web, e utilizar padrões de metadados que possibilitem, futuramente, o diálogo com sistemas institucionais federais, estaduais e municipais, assim como com plataformas da sociedade civil. No estágio atual de desenvolvimento, estão sendo definidos os especificadores técnicos e fluxos de integração, que serão implementados nas próximas versões da plataforma.

#### 👉 Módulo de Visualização e consulta a dados

O Módulo de visualização e consulta a dados constitui o núcleo responsável pela exploração analítica, interpretação e comunicação das informações consolidadas no MonitoraEA. Seu desenho integra ferramentas interativas de análise, mecanismos de filtragem, visualizações temáticas e componentes geoespaciais, permitindo o exame estruturado das iniciativas cadastradas e a identificação de padrões, tendências e distribuições territoriais em múltiplas escalas. A integração entre painéis, dashboards e recursos cartográficos garante que usuários possam explorar o conjunto de dados de forma flexível e tecnicamente consistente.

O módulo suporta tanto o uso especializado por equipes técnicas quanto a consulta pública, visando assegurar inteligibilidade, rastreabilidade e transparência das informações disponibilizadas. Seus componentes permitem examinar indicadores de desempenho e resultados, analisar séries temporais, comparar tipos de iniciativas, avaliar padrões territoriais e exportar dados para análises externas, compondo um ambiente de interpretação robusto e alinhado às demandas de monitoramento e avaliação em Educação Ambiental.

A seguir, apresenta-se, no quadro 8, uma síntese dos principais elementos técnicos que estruturam esse módulo.

**Quadro 8 – Matriz de funcionalidades do módulo de visualização e consulta a dados.**

| Componente / Categoria     | Finalidade                                                           | Funcionalidades Técnicas                                                                             |
| -------------------------- | -------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| Dashboard Principal        | Consolidação de métricas gerais e visão sistêmica                    | Visão geral do sistema; KPIs de M&A; Gráficos interativos; Alertas e notificações                    |
| Painéis Temáticos          | Análises especializadas por dimensão, recorte territorial ou período | Visualizações por perspectiva de M&A; Análises regionais; Comparativos por tipo de iniciativa        |
| Ferramentas de Análise[^2] | Exploração detalhada e processamento dinâmico de informações         | Filtros múltiplos; Agregações dinâmicas; Comparativos side-by-side; Exportação de dados e relatórios |
| Mapas Interativos          | Visualização geoespacial e análise territorial                       | Camadas temáticas; Navegação multiescala; Tooltips informativos                                      |
| Análises Espaciais[^3]     | Interpretação de padrões territoriais e distribuição espacial        | Buffer analysis; Sobreposição de camadas; Heat maps; Análise de vazios estruturais.                  |

[^2]: Em etapa de projeto no momento da publicação deste relatório.

[^3]: Em etapa de projeto no momento da publicação deste relatório.

A matriz sistematiza os elementos operacionais, mas todos esses componentes funcionam de forma integrada. Os dashboards concentram indicadores consolidados e permitem análises rápidas de desempenho, enquanto os painéis temáticos aprofundam a interpretação por eixos específicos, regiões ou categorias de iniciativas. As ferramentas analíticas complementares, como filtros avançados, agregações dinâmicas e mecanismos comparativos, viabilizam operações exploratórias mais detalhadas, preservando a coerência metodológica do sistema.

A dimensão geoespacial amplia as possibilidades de interpretação, permitindo observar a distribuição territorial das iniciativas, identificar concentrações e vazios, sobrepor camadas de referência e realizar análises espaciais automatizadas. O uso combinado de mapas interativos, clusters, heat maps e ferramentas de recorte territorial oferece suporte a diagnósticos situados e análises comparativas entre municípios, regiões, biomas ou zonas costeiras e marinhas.

Desse modo, o módulo organiza um conjunto coerente de recursos analíticos e geográficos que viabilizam a consulta estruturada dos dados produzidos no MonitoraEA, garantindo consistência informacional, rastreabilidade e adequação às necessidades de monitoramento e avaliação em escala nacional.

#### 👉 Módulo de Interação Social e Engajamento

O Módulo de Interação Social e Engajamento[^4] expande o MonitoraEA para além de uma plataforma de consulta e gestão de informações, incorporando uma camada sociotécnica orientada à comunicação, colaboração e mobilização entre os participantes do campo da Educação Ambiental. Sua concepção apoia-se na adoção do protocolo ActivityPub, padrão aberto que viabiliza redes sociais federadas, permitindo que o sistema opere como parte do Fediverso, que pode ser descrito como um ecossistema distribuído de plataformas interoperáveis. Com essa integração, o MonitoraEA deixa de funcionar apenas como repositório e passa a constituir um espaço descentralizado de aprendizagem, articulação e circulação de práticas, fortalecendo comunidades e ampliando a capilaridade das ações de EA.

Para assegurar clareza e precisão na definição dos seus elementos mais técnicos, apresenta-se a seguir o quadro 9.

[^4]: Módulo em desenvolvimento no momento da publicação deste relatório técnico.

**Quadro 9 – Matriz de funcionalidades do Interação Social e Engajamento.**

| Componente Técnico           | Descrição                                                          | Funcionalidades-Chave                                                            | Resultados Esperados                                                           |
| ---------------------------- | ------------------------------------------------------------------ | -------------------------------------------------------------------------------- | ------------------------------------------------------------------------------ |
| Perfis de Usuário            | Estrutura de representação pública e semipública dos participantes | Informações básicas, biografia/interesses, histórico de contribuições, badges    | Identificação, reputação distribuída e estímulo ao engajamento                 |
| Sistema de Seguidores        | Mecanismo de criação de redes e conexões entre atores              | Seguimentos mútuos, feed, notificações, mensagens diretas                        | Ampliação da circulação de conteúdos e fortalecimento das redes de colaboração |
| Comunidades e Grupos         | Ambientes temáticos ou territoriais para interação estruturada     | Grupos temáticos, fóruns, comunidades territoriais, busca de grupos              | Organização de debates, articulação regional e troca especializada             |
| ActivityPub e Federabilidade | Protocolo aberto para troca distribuída de conteúdos               | Federated timeline, seguir/ser seguido, boost, menções                           | Integração com outras plataformas do Fediverso e ampliação do alcance social   |
| Interoperabilidade ampliada  | Conjunto de mecanismos técnicos que asseguram compatibilidade      | Integração com Mastodon, suporte a múltiplas instâncias, APIs abertas, Webfinger | Interconectividade total com o Fediverso e suporte a extensões externas        |

Com base nessa arquitetura, o módulo operacionaliza um conjunto de funcionalidades sociais que favorecem a criação de redes distribuídas de prática e aprendizagem. Perfis estruturados possibilitam a identificação e o acompanhamento das contribuições dos participantes, reforçando a formação de reputação coletiva. O sistema de seguidores cria fluxos contínuos de atualização, gerando uma dinâmica de timeline que mobiliza conteúdos produzidos no próprio MonitoraEA ou em instâncias externas federadas.

As comunidades e grupos temáticos ou territoriais ampliam o potencial de articulação, permitindo que debates, fóruns e iniciativas se organizem em torno de interesses comuns, de escalas locais a nacionais. Essas mesmas estruturas fortalecem o compartilhamento de experiências, a disseminação de metodologias e a construção colaborativa de diagnósticos e agendas.

A integração plena ao Fediverso, viabilizada pelo ActivityPub, posiciona a plataforma como parte de um ecossistema aberto, distribuído e interoperável, onde conteúdos podem circular entre diferentes instâncias sem depender de serviços centralizados. Esse arranjo evita enclausuramento tecnológico, assegura autonomia e fortalece a soberania digital do sistema, ao mesmo tempo em que amplia significativamente o alcance das ações e narrativas da Educação Ambiental.

A combinação entre funcionalidades sociais, espaços comunitários e infraestruturas federadas traduz-se em um módulo que não apenas complementa a base de dados do MonitoraEA, mas transforma seus usuários em sujeitos ativos na produção, circulação e análise de informações. O resultado é um ambiente digital que opera simultaneamente como plataforma informacional, rede social descentralizada e dispositivo de mobilização territorializada para o campo da EA.
