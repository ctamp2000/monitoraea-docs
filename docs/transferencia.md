# Transferência

## 📌 PLANO DE TRANSFERÊNCIA TECNOLÓGICA E EXTENSÃO

O Sistema MonitoraEA, enquanto infraestrutura digital pública e aberta, adota um modelo de transferência tecnológica baseado no uso compartilhado e na capacitação institucional, visando maximizar seu alcance, impacto e sustentabilidade como ferramenta de suporte à Política Nacional de Educação Ambiental (PNEA). Este plano estrutura-se em três eixos principais: i) Disponibilização da Plataforma como Serviço; ii) Fomento a Spin-offs Institucionais Interoperáveis; e iii) Programa Estruturado de Capacitação e Apropriação Tecnológica. O objetivo central é garantir que a tecnologia desenvolvida seja plenamente acessível e operável por diferentes atores do Sistema Nacional de Meio Ambiente (SISNAMA) e do Sistema Educacional, sem prejuízo da governança e da integridade do banco de dados nacional.

### 👉 Modelo de Disponibilização: Plataforma como Serviço (PaaS) e Acesso Federado

A principal via de transferência é a disponibilização do MonitoraEA como uma plataforma centralizada, porém de acesso universal e federado. Este modelo assegura a consolidação de um banco de dados nacional robusto e coerente, evitando a fragmentação de informações.

- Acesso Público ao Portal, por meio da área pública do portal, com seus painéis, mapas interativos e funcionalidades de consulta, permanece acessível a qualquer cidadão, fortalecendo a transparência e o controle social;
- Acesso Autenticado para Produção de Dados, por meio de instituições parceiras (secretarias estaduais e municipais de meio ambiente e educação, CIEAs, CECSAs, ONGs), com acesso integral à área colaborativa para cadastro, autoavaliação e gestão de suas comunidades, utilizando a mesma instância da plataforma;
- APIs para consumo de dados estruturados, como detalhado na Seção 4.2.2, o Módulo de Integração e Interoperabilidade, que deverá disponibilizar APIs RESTful documentadas (OpenAPI/Swagger). Isso permitirá que sistemas institucionais parceiros (ex.: portais de estados e municípios) consumam dados específicos do MonitoraEA (metadados, indicadores sintéticos, geosserviços) para visualização em seus próprios portais, painéis e aplicativos, promovendo a integração sem a necessidade de replicação da infraestrutura.
- Credenciamento de Instâncias Gestoras, buscando mobilizar instituições de grande porte (como Ministérios, Secretarias Estaduais ou Universidades) para serem credenciadas como "Gestoras de Perspectiva", recebendo permissões elevadas para administrar comunidades específicas dentro de suas áreas de competência, atuando como nós especializados da rede.

### 👉 Fomento a Spin-offs Institucionais com Interoperabilidade Garantida

Reconhecendo necessidades específicas de determinadas instituições ou redes, o plano prevê a geração controlada de spin-offs do MonitoraEA. Trata-se da implantação de instâncias customizadas da plataforma para uso interno ou temático, que, no entanto, mantêm obrigatoriamente a interoperabilidade bidirecional com a instância nacional principal.

Compreende-se que este modelo possa ser relevante para:

- Grandes Universidades ou Redes de Pesquisa, que desejam utilizar a arquitetura do MonitoraEA para monitorar seus próprios programas de extensão ou pesquisa em sustentabilidade, adaptando formulários e indicadores ao seu contexto, mas alimentando e sendo alimentados pela base nacional;
- Projetos Temáticos de Grande Escala, como um programa federal para um bioma específico (ex.: Plano de Ação para a Caatinga) que necessita de uma instância dedicada, mas cujos dados devem integrar a visão nacional da EA;
- Órgãos Federais com Amplo Portfólio de EA como, por exemplo, o Instituto Brasileiro do Meio Ambiente e dos Recursos Naturais Renováveis (IBAMA), visando permitir ao órgão gerenciar, de forma integrada e padronizada, o vasto conjunto de programas e projetos de Educação Ambiental vinculados a condicionantes de licenças e termos de compromisso. Esta instância atuaria por meio de formulários e fluxos específicos do licenciamento federal, otimizando a gestão e o acompanhamento das ações. Via interoperabilidade, dados anonimizados e agregados seriam sincronizados com a instância nacional, enriquecendo a base do MonitoraEA com informações estratégicas sobre a efetividade da EA em territórios impactados por grandes empreendimentos;
- Instâncias Regionais Fortalecidas, como, por exemplo, uma CIEA que queira operar uma plataforma própria, mas mantendo a coerência com o sistema nacional.

  O protocolo de interoperabilidade para os spin-offs deverá ser garantido por:

- Adoção do Core Tecnológico: Utilização dos mesmos repositórios de código-fonte (monitoraea-colab e monitoraea-portal), garantindo a compatibilidade tecnológica de base.
- Contrato de Interoperabilidade: Estabelecimento de um acordo técnico e de governança que defina os padrões de sincronização, os conjuntos de dados obrigatoriamente compartilhados e a frequência de atualização.
- APIs de Sincronização Bidirecional: Implementação de endpoints específicos para a sincronização seletiva e segura de dados entre a instância spin-off e a instância nacional, utilizando os mesmos protocolos de autenticação e validação cruzada descritos no Módulo de Integração (Seção 4.2.2).
- Metadados e Vocabulários Controlados: Adoção obrigatória dos mesmos esquemas de metadados (ex.: JSON-LD, Dublin Core) e vocabulários controlados para garantir a consistência semântica dos dados trafegados.

### 👉 Programa Estruturado de Capacitação e Apropriação Tecnológica

A transferência efetiva da tecnologia depende da capacitação dos usuários finais e gestores. O plano prevê um programa de extensão tecnológica, que deverá contemplar:

- Cursos Autoinstrutivos Online (MOOC): Desenvolvimento de cursos na modalidade EaD, hospedados em plataformas abertas, cobrindo desde o uso básico do sistema (cadastro de iniciativas) até tópicos avançados (análise de dados, interpretação de indicadores de risco climático)[^1];
  [^1]:Foi desenvolvido e está disponível o curso “Monitoramento e Avaliação de Políticas Públicas de Educação Ambiental”, por meio de uma parceria com o MMA, acessível no sistema da Escola Virtual de Governo da ENAP (Escola Nacional de Administração Pública). O curso pode ser acessado neste [link](https://www.escolavirtual.gov.br/curso/617).

- Formação continuada de Articuladores Locais e Multiplicadores: Intensificação do programa já existente, com a realização de oficinas presenciais e webinars regulares para a Rede de Articuladores, focando na resolução de problemas práticos e na difusão das melhores práticas de M&A;

- Documentação Técnica e de Usuário Ampliada: Manutenção e expansão da documentação do sistema, incluindo manuais de usuário, tutoriais em vídeo, e documentação técnica robusta das APIs para desenvolvedores de instituições parceiras que queiram consumir dados ou desenvolver spin-offs;

- Suporte Técnico Especializado por Níveis: Estabelecimento de uma estrutura de suporte em camadas: i) suporte primário via comunidades e articuladores; ii) suporte técnico-operacional centralizado para gestores de comunidades e spin-offs; e iii) suporte desenvolvedor-to-desenvolvedor para questões de integração via APIs.

### 👉 Cronograma de Implementação da Transferência (2026-2028)

- 2026: Finalização e documentação pública das APIs de consulta; Lançamento do primeiro curso MOOC; Estruturação do marco legal e técnico para os spin-offs; Realização de 2 workshops nacionais para divulgação do modelo de transferência.
- 2027: Implementação das APIs de sincronização para spin-offs; Lançamento de mais 2 cursos MOOC; Capacitação de 5 instituições piloto para desenvolvimento de spin-offs; Estabelecimento formal da estrutura de suporte em camadas.
- 2028: Consolidação do programa de capacitação; Acompanhamento e auditoria dos primeiros spin-offs implantados; Publicação de casos de sucesso de uso compartilhado e integração.

  Este plano de transferência tecnológica e extensão posiciona o MonitoraEA não apenas como um produto de software, mas como um ecossistema de inovação aberta em M&A para a Educação Ambiental. Ao promover o uso compartilhado e controlado de sua infraestrutura, o sistema garante sua escalabilidade, fortalece a governança de dados da PNEA e potencializa seu impacto na formulação de políticas públicas mais efetivas e baseadas em evidências.
