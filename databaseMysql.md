#########################################################################
 ____        _          ____                   __  __                 _ 
|  _ \  __ _| |_ __ _  | __ )  __ _ ___  ___  |  \/  |_   _ ___  __ _| |
| | | |/ _` | __/ _` | |  _ \ / _` / __|/ _ \ | |\/| | | | / __|/ _` | |
| |_| | (_| | || (_| | | |_) | (_| \__ \  __/ | |  | | |_| \__ \ (_| | |
|____/ \__,_|\__\__,_| |____/ \__,_|___/\___| |_|  |_|\__, |___/\__, | |
                                                      |___/        |_|_|
#########################################################################
Fontes: 
https://www.oracle.com/br/database/what-is-database/
https://www.oracle.com/br/database/what-is-a-cloud-database/
https://www.oracle.com/br/autonomous-database/what-is-autonomous-database/

Autor: Leopoldino Paulo Chalambua
---------------------------------

O que é um Banco de Dados?

**Banco de dados definido**
Um banco de dados é uma coleção organizada de informações - ou dados - estruturadas, normalmente armazenadas eletronicamente em um sistema de computador. Um banco de dados é geralmente controlado por um sistema de gerenciamento de banco de dados (DBMS). Os dados e o DBMS, juntamente com os aplicativos associados a eles, são chamados de sistema de banco de dados, geralmente abreviados para apenas banco de dados.

Os dados nos tipos mais comuns de bancos de dados em operação atualmente são modelados em linhas e colunas em uma série de tabelas para tornar o processamento e a consulta de dados eficientes. Os dados podem ser facilmente acessados, gerenciados, modificados, atualizados, controlados e organizados. A maioria dos bancos de dados usa a linguagem de consulta estruturada (SQL) para escrever e consultar dados.

**O que é SQL (Structured Query Language)**
Linguagem de consulta estruturada
SQL é uma linguagem de programação usada por quase todos os bancos de dados relacionais para consultar, manipular e definir dados e fornecer controle de acesso. O SQL foi desenvolvido pela primeira vez na IBM nos anos 1970, com a Oracle como principal contribuinte, o que levou à implementação do padrão SQL ANSI; o SQL estimulou muitas extensões de empresas como IBM, Oracle e Microsoft. Embora o SQL ainda seja amplamente usado hoje em dia, novas linguagens de programação estão a aparecer.

**Evolução do banco de dados**
Os bancos de dados evoluíram muito desde a sua criação no início dos anos 1960. Bancos de dados de navegação, como o banco de dados hierárquico (que se baseava em um modelo de árvore e permitia apenas um relacionamento um-para-muitos), e o banco de dados de rede (um modelo mais flexível que permitia múltiplos relacionamentos) eram os sistemas originais usados para armazenar e manipular dados. Embora simples, esses primeiros sistemas eram inflexíveis. Nos anos 1980, bancos de dados relacionais tornaram-se populares, seguidos por bancos de dados orientados a objetos na década de 1990. Mais recentemente, bancos de dados NoSQL surgiram como uma resposta ao crescimento da internet e à necessidade de maior velocidade e processamento de dados não estruturados. Hoje, bancos de dados na nuvem e bancos de dados autônomos estão abrindo novos caminhos quando se trata de como os dados são coletados, armazenados, gerenciados e utilizados.

**Qual é a diferença entre um banco de dados e uma planilha?**
Bancos de dados e planilhas (como o Microsoft Excel) são modos convenientes de armazenar informações. 

As principais diferenças entre os dois são:
	* - Como os dados são armazenados e manipulados
	* - Quem pode acessar os dados
	* - Quantos dados podem ser armazenados
	
As planilhas foram originalmente projetadas para um usuário e suas características refletem isso. São ótimos para um único usuário ou um pequeno número de usuários que não precisam fazer manipulação de dados muito complicada. 

Bancos de dados, por outro lado, são projetados para conter coleções  maiores de informações organizadas - quantidades enormes, às vezes. Os bancos de dados permitem que vários usuários, ao mesmo tempo, acessem e consultem com rapidez e segurança os dados usando lógica e linguagem altamente complexas.

**Tipos de bancos de dados**
Existem muitos tipos diferentes de bancos de dados. O melhor banco de dados para uma organização específica depende de como a organização pretende usar os dados.

**Bancos de dados relacionais** Os bancos de dados relacionais se tornaram dominantes na década de 1980. Os itens em um banco de dados relacional são organizados como um conjunto de tabelas com colunas e linhas. A tecnologia de banco de dados relacional fornece a maneira mais eficiente e flexível de acessar informações estruturadas.

**Bancos de dados orientados a objetos** As informações em um banco de dados orientado a objetos são representadas na forma de objetos, como na programação orientada a objetos.

**Bancos de dados distribuídos** Um banco de dados distribuído consiste em dois ou mais arquivos localizados em sites diferentes. O banco de dados pode ser armazenado em vários computadores, localizados no mesmo local físico ou espalhados por diferentes redes.

**Data warehouses** Um repositório central de dados, um data warehouse é um tipo de banco de dados projetado especificamente para consultas e análises rápidas.

**Bancos de dados NoSQL** Um NoSQL, ou banco de dados não relacional, permite que dados não estruturados e semiestruturados sejam armazenados e manipulados (em contraste com um banco de dados relacional, que define como todos os dados inseridos no banco de dados devem ser compostos). Os bancos de dados NoSQL se tornaram populares à medida que os aplicativos web se tornaram mais comuns e mais complexos.

**Bancos de dados gráficos** Um banco de dados gráfico armazena dados em termos de entidades e os relacionamentos entre entidades.

**Bancos de dados OLTP** Um banco de dados OLTP é um banco de dados rápido e analítico projetado para um grande número de transações realizadas por vários usuários.

Esses são apenas alguns dos vários tipos de bancos de dados em uso atualmente. Outros bancos de dados menos comuns são adaptados para funções científicas, financeiras ou outras muito específicas. Além dos diferentes tipos de banco de dados, as mudanças nas abordagens de desenvolvimento de tecnologia e os avanços dramáticos, como a nuvem e a automação, estão impulsionando os bancos de dados em direções totalmente novas. Alguns dos mais recentes bancos de dados incluem:

**Bancos de dados de código aberto** Um sistema de banco de dados de código aberto é aquele cujo código-fonte é código aberto; esses bancos de dados podem ser bancos de dados SQL ou NoSQL.

**Bancos de dados em nuvem** Um banco de dados em nuvem é uma coleção de dados, estruturados ou não estruturados, que residem em uma plataforma de computação em nuvem privada, pública ou híbrida. Existem dois tipos de modelos de banco de dados em nuvem: tradicional e banco de dados como serviço (DBaaS). Com o DBaaS, as tarefas administrativas e a manutenção são executadas por um provedor de serviços.

**Banco de dados multimodelo** Bancos de dados multimodelo combinam diferentes tipos de modelos de banco de dados em um back-end único e integrado. Isso significa que eles podem acomodar vários tipos de dados.

**Banco de dados de documentos/JSON** Projetado para armazenamento, recuperação e gerenciamento de informações orientadas a documentos, os bancos de dados de documentos são uma maneira moderna de armazenar dados no formato JSON, em vez de linhas e colunas.

**Bancos de dados autônomos** Os bancos de dados independentes mais novos e inovadores (também conhecidos como bancos de dados autônomos) são baseados em nuvem e usam machine learning para automatizar o ajuste de banco de dados, segurança, backups, atualizações e outras tarefas de gerenciamento de rotina tradicionalmente executadas por administradores de banco de dados.

**Software de banco de dados?**
O software de banco de dados é usado para criar, editar e manter arquivos e registros de banco de dados, facilitando a criação de arquivos e registros, entrada de dados, edição, atualização e relatórios de dados. O software também processa armazenamento de dados, backup e relatórios, controle multiacesso e segurança. A segurança forte do banco de dados é especialmente importante hoje, porque o roubo de dados se torna mais frequente. O software de banco de dados às vezes também é conhecido como "sistema de gerenciamento de banco de dados" (DBMS - Data Base Manager System).

O software de banco de dados simplifica o gerenciamento de dados, permitindo que os usuários armazenem dados em um formulário estruturado e depois os acessem. Ele normalmente tem uma interface gráfica para ajudar a criar e gerenciar os dados e, em alguns casos, os usuários podem construir os próprios bancos de dados usando o software do banco de dados.

**O que é um sistema de gerenciamento de banco de dados (DBMS)?**
Um banco de dados normalmente requer um programa abrangente de banco de dados, conhecido como sistema de gerenciamento de banco de dados (DBMS). Um DBMS serve como uma interface entre o banco de dados e seus usuários finais ou programas, permitindo que os usuários recuperem, atualizem e gerenciem como as informações são organizadas e otimizadas. Um DBMS também facilita a supervisão e o controle de bancos de dados, permitindo uma variedade de operações administrativas, como monitoramento de desempenho, ajuste backup e recuperação.

Alguns exemplos de softwares de bancos de dados populares ou DBMSs incluem:
	* - MySQL
	* - Microsoft Access
	* - Microsoft SQL Server
	* - FileMaker Pro
	* - Oracle Database
	* - dBASE
	
**MySQL Database**
MySQL é um sistema de gerenciamento de banco de dados relacional de código aberto baseado em SQL. Ele foi projetado e otimizado para aplicativos da web e pode ser executado em qualquer plataforma. Como surgiram requisitos novos e diferentes com a internet, o MySQL tornou-se a plataforma preferida para desenvolvedores da web e aplicativos baseados na web. Como foi projetado para processar milhões de consultas e milhares de transações, o MySQL é uma escolha popular para empresas de comércio eletrônico que precisam gerenciar várias transferências de dinheiro. A flexibilidade sob demanda é o principal recurso do MySQL.

O MySQL é o DBMS por trás de alguns dos principais sites e aplicativos baseados na web do mundo, incluindo:
	* - Airbnb
	* - Uber
	* - LinkedIn
	* - Facebook
	* - Twitter
	* - YouTube

**Uso de bancos de dados para aprimorar o desempenho e a tomada de decisões nos negócios**

Com a coleta maciça de dados da Internet das Coisas, transformando a vida e o setor em todo o mundo, as empresas hoje têm acesso a mais dados do que nunca. Organizações inovadoras agora podem usar bancos de dados que vão além do armazenamento de dados e de transações básicas para analisar grandes quantidades de dados de vários sistemas. Ao usar bancos de dados e outras ferramentas de business intelligence e computação, as organizações aproveitam dados que coletam para executar funções com mais eficiência, possibilitar melhor tomada de decisões e serem mais rápidas e escalonáveis. A otimização do acesso e do throughput aos dados é fundamental para as empresas de hoje, pois há mais volume de dados a ser rastreado. É fundamental ter uma plataforma que possa oferecer o desempenho, a escala e a agilidade necessários às empresas à medida que crescem com o tempo.

O banco de dados autônomo está pronto para fornecer um impulso significativo a esses recursos. Como os bancos de dados autônomos automatizam processos manuais caros e demorados, eles liberam utilizadores de negócios para se tornarem mais proativos com seus dados. Por ter controle direto sobre a capacidade de criar e usar bancos de dados, os usuários ganham controle e autonomia enquanto mantêm importantes padrões de segurança.

**Desafios do banco de dados**
Os grandes bancos de dados empresariais atuais geralmente suportam consultas muito complexas e devem fornecer respostas quase instantâneas a essas consultas. Como resultado, os administradores de bancos de dados são constantemente chamados para empregar uma ampla variedade de métodos que ajudam a melhorar o desempenho. Alguns desafios comuns que eles enfrentam incluem:

**Absorção de aumentos significativos no volume de dados**. A explosão de dados provenientes de sensores, máquinas conectadas e dezenas de outras fontes mantém os administradores de bancos de dados lutando para gerenciar e organizar os dados de suas empresas com eficiência.

**Garantia da segurança de dados**. Violações de dados estão acontecendo em todos os lugares nos dias de hoje, e os hackers estão ficando mais inventivos. É mais importante do que nunca garantir que os dados estejam seguros, mas também acessíveis aos usuários.

**Acompanhando a demanda**. No atual ambiente de negócios de rápido movimento, as empresas precisam de acesso em tempo real aos seus dados para apoiar a tomada de decisões em tempo hábil e aproveitar novas oportunidades.

**Gerenciamento e manutenção do banco de dados e da infraestrutura.** Os administradores de banco de dados devem observar continuamente o banco de dados em busca de problemas e executar a manutenção preventiva, bem como aplicar atualizações e correções de software. À medida que os bancos de dados se tornam mais complexos e o volume de dados aumenta, as empresas enfrentam a despesa de contratar mais talentos para monitorar e ajustar seus bancos de dados.

**Remoção de limites na escalabilidade**. Uma empresa precisa crescer se quiser sobreviver, e seu gerenciamento de dados deve crescer junto com ela. Mas é muito difícil para os administradores de banco de dados prever a capacidade que a empresa precisará, principalmente com bancos de dados on-premise.

**Garantir residência, soberania de dados ou requisitos de latência**. Algumas organizações têm casos de uso mais adequados para sua execução on-premises. Nesses casos, os sistemas projetados pré-configurados e pré-otimizados para a execução do banco de dados são ideais.

Resolver todos esses desafios pode consumir muito tempo e impedir que os administradores de banco de dados executem mais funções estratégicas.

**Como a tecnologia autônoma está aprimorando o gerenciamento de banco de dados**
Os bancos de dados autônomos são a onda do futuro - e oferecem uma possibilidade intrigante para as organizações que desejam usar a melhor tecnologia de banco de dados disponível sem as dores de cabeça da execução e da operação dessa tecnologia.

Os bancos de dados autônomos usam tecnologia baseada em nuvem e machine learning para automatizar muitas das tarefas de rotina necessárias para gerenciar bancos de dados, como ajuste, segurança, backups, atualizações e outras tarefas de gerenciamento de rotina. Com essas tarefas tediosas automatizadas, os administradores de banco de dados ficam livres para fazer um trabalho mais estratégico. Os recursos autônomos de autocondução, autoproteção e autorreparo dos bancos de dados independentes estão prestes a revolucionar a forma como as empresas gerenciam e protegem seus dados, possibilitando vantagens de desempenho, custos mais baixos e segurança aprimorada.

-----------------------------------
O Que é um Banco de Dados Autônomo?

**Definição do Autonomous Database**
Um banco de dados autônomo é um banco de dados em nuvem que usa machine learning para automatizar o ajuste de banco de dados, a segurança, os backups, as atualizações e outras tarefas rotineiras de gerenciamento que tradicionalmente eram executadas por DBAs. Ao contrário de um banco de dados convencional, um banco de dados autônomo executa todas essas tarefas e muito mais sem intervenção humana.

**Por Que Usar um Banco de Dados Autônomo**
Os bancos de dados armazenam informações comerciais importantes e são essenciais para a operação eficiente de organizações modernas. Os DBAs geralmente ficam sobrecarregados com as tarefas manuais demoradas de gerenciamento e manutenção de bancos de dados. As demandas das cargas de trabalho atuais podem levar a erros de DBAs, que podem causar graves consequências no tempo de atividade, no desempenho e na segurança.

Por exemplo, deixar de aplicar um patch ou uma atualização de segurança pode criar vulnerabilidades. A falha ao aplicar um patch corretamente pode enfraquecer ou eliminar completamente as proteções de segurança. Se o banco de dados não for seguro, a empresa poderá correr o risco de violações de dados que podem ter sérias repercussões financeiras e prejudicar a sua reputação.

Os aplicativos de negócios adicionam novos registros aos bancos de dados já existentes ou usam informações do banco de dados para criar relatórios, analisar tendências ou procurar anomalias. Isso pode fazer com que os bancos de dados cresçam para ter muitos terabytes e se tornem altamente complexos, tornando-os ainda mais difíceis de serem gerenciados, protegidos e ajustados pelos DBAs para obter máximo desempenho. Bancos de dados com execução lenta ou indisponíveis devido ao tempo de inatividade podem prejudicar a produtividade dos funcionários e frustrar os clientes.

A quantidade e a velocidade dos dados disponíveis para a empresa estão ficando mais rápidas. Isso amplia a necessidade de gerenciamento de banco de dados eficiente e seguro, que aprimora a segurança dos dados, reduz o tempo de inatividade, melhora o desempenho e não é vulnerável a erros humanos. Um banco de dados autônomo pode alcançar esses objetivos.

**Tipos de Dados Armazenados em Bancos de Dados**
As informações armazenadas em um sistema de gerenciamento de banco de dados podem ser altamente estruturadas (como registros contábeis ou informações do cliente) ou não estruturadas (como planilhas ou imagens digitais). Os dados podem ser acessados diretamente por clientes e funcionários ou acessados indiretamente por meio de outros softwares, sites ou aplicativos móveis corporativos. Além disso, muitos tipos de software (como business intelligence, gerenciamento de relacionamento com clientes e aplicativos da cadeia de suprimentos) usam as informações armazenadas nos bancos de dados.

Componentes de um Banco de Dados Autônomo
Um banco de dados autônomo consiste em dois elementos principais que se alinham aos tipos de carga de trabalho.

Um data warehouse executa várias funções relacionadas às atividades de business intelligence e usa dados previamente preparados para análise. O ambiente do data warehouse também gerencia todas as operações do ciclo de vida do banco de dados, pode executar verificações de consulta em milhões de linhas, se adequa às necessidades da empresa e pode ser implantado em questão de segundos.
O processamento de transações permite processos transacionais baseados em tempo, como análise em tempo real, personalização e detecção de fraudes. Geralmente, o processamento de transações envolve um número muito pequeno de registros, baseia-se em operações predefinidas e traz simplicidade no desenvolvimento e na implementação de aplicativos.
Como o Banco de Dados Autônomo Funciona
Um banco de dados autônomo aproveita a IA e o machine learning para fornecer automação completa de ponta a ponta para provisionamento, segurança, atualizações, disponibilidade, desempenho, gerenciamento de alterações e prevenção de erros.

Nesse sentido, um banco de dados autônomo tem características específicas:

**São independente**
Todos os processos de gerenciamento, monitoramento e ajuste de banco de dados e infraestrutura são automatizados. Os DBAs agora podem se concentrar em tarefas mais importantes, inclusive agregação de dados, modelagem, processamento, estratégias de governança, além de ajudar os desenvolvedores a usar recursos e funções no banco de dados com alterações mínimas feitas no código do aplicativo.

**Seguro**
Os recursos integrados protegem contra ataques externos e usuários internos maliciosos. Isso ajuda a eliminar as preocupações com ataques cibernéticos em bancos de dados sem patch ou sem criptografia.

**Autorreparável**
Isso pode impedir o tempo de inatividade, incluindo manutenção não planejada. Um banco de dados autônomo pode exigir menos de 2,5 minutos de tempo de inatividade por mês, incluindo aplicação de patches.

Benefícios de um Banco de Dados Autônomo
O banco de dados autônomo traz vários benefícios.

Máximo em tempo de atividade, desempenho e segurança, incluindo patches e correções automáticas
Eliminação de tarefas de gerenciamento manuais e propensas a erros por meio da automação
Custos reduzidos e produtividade aprimorada ao automatizar tarefas do dia-a-dia

Um banco de dados autônomo também permite que uma organização redirecione a equipe de gerenciamento de banco de dados para trabalhos de nível superior que criem maior valor comercial, como modelagem de dados, auxílio de programadores na arquitetura de dados e planejamento da capacidade futura. Em alguns casos, um banco de dados autônomo pode ajudar uma empresa a economizar reduzindo o número de DBAs necessários para gerenciar seus bancos de dados ou redistribuí-los em tarefas mais estratégicas.

Tecnologias Inteligentes Compatíveis com Bancos de Dados Autônomos
Várias tecnologias inteligentes básicas são compatíveis com bancos de dados autônomos, permitindo a automação de tarefas comuns porém importantes, como manutenção, dimensionamento, segurança e ajuste de banco de dados. Por exemplo, os algoritmos de inteligência artificial e machine learning de um banco de dados autônomo incluem otimização da consulta, gerenciamento automático de memória e gerenciamento automático de armazenamento, para fornecer um banco de dados completamente autoajustável.

Os algoritmos de machine learning podem ajudar empresas a melhorar a segurança do banco de dados ao analisar resmas de dados registrados e sinalizando discrepâncias e anomalias em padrões antes que os invasores causem danos. O machine learning também pode corrigir, ajustar, fazer backup e atualizar o sistema automaticamente, sem intervenção manual, enquanto o sistema está em execução. Essa automação minimiza a possibilidade de que um erro humano ou um comportamento mal-intencionado afete as operações ou a segurança do banco de dados.

Além disso, bancos de dados autônomos têm alguns recursos específicos:

Escalabilidade fácil
Um servidor de banco de dados baseado em nuvem pode expandir ou reduzir seus recursos de computação e memória instantaneamente, conforme necessário. Por exemplo, uma empresa poderia aumentar de 8 para 16 núcleos de processamento de banco de dados para ampliar o processamento no final do trimestre e, depois, voltar para os 8 núcleos menos caros. Na verdade, todos os recursos de processamento poderiam ser desligados durante o fim de semana para reduzir os custos e iniciados novamente na manhã de segunda-feira.

Patches contínuos do banco de dados
Muitos vazamentos de dados são ativados por vulnerabilidades do sistema para as quais um patch de segurança ou vulnerabilidade já está disponível, mas ainda não foi aplicado. Um banco de dados autônomo evita esse problema ao executar patches automaticamente nos servidores em nuvem em uma sequência projetada para eliminar o tempo de inatividade dos negócios.

Inteligência integrada
Um banco de dados autônomo integra recursos de monitoramento, gerenciamento e análise avançada que aproveitam as técnicas de machine learning e IA. O objetivo é automatizar o ajuste do banco de dados, evitar interrupções de aplicativos e fortalecer a segurança em todo o aplicativo do banco de dados.
A Vantagem do Desenvolvedor
Com um banco de dados autônomo, os desenvolvedores podem criar rapidamente aplicativos comerciais dimensionáveis e seguros a partir de dados armazenados em um ambiente pré-configurado, totalmente gerenciado e seguro.

Escolha de um Banco de Dados Autônomo
Bancos de dados autônomos oferecem vários benefícios. Quando você estiver pronto para avaliar as ofertas disponíveis para sua organização, procure os recursos principais a seguir.

Provisionamento automático
Implemente automaticamente bancos de dados essenciais que sejam tolerantes a falhas e altamente disponíveis. Ativa o escalonamento perfeito, a proteção em caso de falha no servidor e permite que as atualizações sejam aplicadas continuamente enquanto os aplicativos continuam em execução.

Configuração automática
Configura automaticamente o banco de dados para otimização de cargas de trabalho específicas. Tudo, desde a configuração da memória, os formatos de dados até as estruturas de acesso, é otimizado automaticamente para melhorar o desempenho. Os clientes podem simplesmente carregar os dados e seguir.

Indexação automática
Monitora automaticamente a carga de trabalho e detecta os índices ausentes que podem acelerar os aplicativos. Isso valida cada índice para garantir o benefício antes de implementá-lo e usa o machine learning para aprender com os próprios equívocos.

Dimensionamento automático
Dimensiona automaticamente os recursos de computação quando necessário por carga de trabalho. Todo o escalonamento ocorre online enquanto o aplicativo é executado continuamente. Permite verdadeiro pagamento por uso.

Proteção automática de dados
Protege automaticamente dados confidenciais e regulamentados no banco de dados, tudo por meio de uma console de gerenciamento unificada. Avalia a segurança de configuração, usuários, dados confidenciais e atividades incomuns do banco de dados.

Segurança automatizada
Criptografia automática para todo o banco de dados, backups e todas as conexões de rede. Ausência de acesso ao sistema operacional ou privilégios de administrador evitam ataques de phishing. Protege o sistema de operações em nuvem e de qualquer usuário interno mal-intencionado.

Backups automáticos
Backup diário automático do banco de dados ou sob demanda. Restaura ou recupera um banco de dados em qualquer momento especificado nos últimos 60 dias.

Aplicação de patches automática
Aplica patches ou atualizações automaticamente sem tempo de inatividade. Os aplicativos continuam sendo executados à medida que ocorre a aplicação de patches alternadamente em nós de cluster ou servidores.

Detecção e resolução automatizadas
Usando reconhecimento de padrões, as falhas de hardware são automaticamente previstas sem longos períodos de tempo limite. Os IOs são redirecionados imediatamente para dispositivos não íntegros a fim de evitar travamentos do banco de dados. O monitoramento contínuo de cada banco de dados gera automaticamente solicitações de serviço para qualquer desvio.

Failover automático
Failover automático com perda de dados zero para stand-by. É totalmente transparente para aplicativos do usuário final. Oferece SLA de 99,995%.

O Futuro dos Bancos de Dados Autônomos
Atualmente, os dados estão sendo gerados a uma taxa que ultrapassa a rapidez com que podem ser gerenciados e processados manualmente para fornecer, de maneira eficiente e segura, insights importantes para os negócios. Devido aos recursos inteligentes de automação, os bancos de dados autônomos oferecem às empresas muitas vantagens sobre os bancos de dados tradicionais. A expectativa é que as empresas migrem cada vez mais para esse modelo de banco de dados para aproveitar essas vantagens, manter uma vantagem competitiva e obter a capacidade de reorientar os esforços de TI na inovação, e não no gerenciamento de banco de dados.

-----------------
O que é um banco de dados relacional (RDBMS)?
Um banco de dados relacional é um tipo de banco de dados que armazena e fornece acesso a pontos de dados relacionados entre si. Bancos de dados relacionais são baseados no modelo relacional, uma maneira intuitiva e direta de representar dados em tabelas. Em um banco de dados relacional, cada linha na tabela é um registro com uma ID exclusiva chamada chave. As colunas da tabela contêm atributos dos dados e cada registro geralmente tem um valor para cada atributo, facilitando o estabelecimento das relações entre os pontos de dados.

Um exemplo de banco de dados relacional
Este é um exemplo simples de duas tabelas que uma pequena empresa pode usar para processar pedidos de seus produtos. A primeira tabela é de informações do cliente, de forma que cada registro inclui o nome, o endereço, as informações de envio e faturamento, o número de telefone e outras informações de contato de um cliente. Cada bit de informação (cada atributo) está em sua própria coluna, e o banco de dados atribui uma ID única (uma chave) a cada linha. Na segunda tabela - uma tabela de pedidos do cliente - cada registro inclui o ID do cliente que fez o pedido, o produto solicitado, a quantidade, o tamanho e a cor selecionados e assim por diante - mas não o nome ou as informações de contato.

Essas duas tabelas têm apenas uma coisa em comum: a coluna ID (a chave). Mas por causa dessa coluna comum, o banco de dados relacional pode criar uma relação entre as duas tabelas. Assim, quando o aplicativo de processamento de pedidos da empresa envia um pedido ao banco de dados, o banco de dados pode ir à tabela de pedidos do cliente, obter as informações corretas sobre o pedido do produto e usar o ID do cliente dessa tabela para procurar as informações de faturamento e envio do cliente na tabela de informações do cliente. O warehouse poderá obter o produto correto, o cliente receberá a entrega do pedido oportunamente e a empresa receberá o pagamento.

Como os bancos de dados relacionais são estruturados
O modelo relacional significa que as estruturas de dados lógicas: tabelas de dados, exibições e índices - são separadas das estruturas de armazenamento físico. Essa separação significa que os administradores de banco de dados podem gerenciar o armazenamento de dados físicos sem afetar o acesso a esses dados como uma estrutura lógica. Por exemplo, a renomeação de um arquivo de banco de dados não renomeia as tabelas armazenadas nele.

A distinção entre lógico e físico também se aplica às operações do banco de dados, que são ações claramente definidas que permitem aos aplicativos manipular os dados e as estruturas do banco de dados. As operações lógicas permitem que um aplicativo especifique o conteúdo necessário e as operações físicas determinam como esses dados devem ser acessados e, em seguida, executa a tarefa.

Para garantir que os dados sejam sempre precisos e acessíveis, os bancos de dados relacionais seguem determinadas regras de integridade. Por exemplo, uma regra de integridade pode especificar que linhas duplicadas não são permitidas em uma tabela para eliminar o potencial de informações errôneas que entram no banco de dados.

O modelo relacional
Nos primeiros anos de bancos de dados, todos os aplicativos armazenavam dados em sua própria estrutura única. Quando os desenvolvedores queriam criar aplicativos para usar esses dados, precisavam conhecer muito a estrutura de dados específica para encontrar os dados de que precisavam. Essas estruturas de dados eram ineficientes, difíceis de manter e difíceis de otimizar para oferecer um bom desempenho de aplicativos. O modelo de banco de dados relacional foi projetado para resolver o problema de várias estruturas de dados arbitrárias.

O modelo relacional forneceu uma maneira padrão de representar e consultar dados que poderiam ser usados por qualquer aplicativo. Desde o início, os desenvolvedores reconheceram que a principal força do modelo de banco de dados relacional estava no uso de tabelas, que era uma maneira intuitiva, eficiente e flexível de armazenar e acessar informações estruturadas.

Com o tempo, outra força do modelo relacional surgiu quando os desenvolvedores começaram a usar a linguagem de consulta estruturada (SQL) para criar e consultar dados em um banco de dados. Por muitos anos, a SQL tem sido amplamente utilizada como a linguagem para consultas de banco de dados. Com base na álgebra relacional, a SQL fornece uma linguagem matemática internamente consistente que facilita a melhoria do desempenho de todas as consultas ao banco de dados. Em comparação, outras abordagens devem definir consultas individuais.

Benefícios do sistema de gerenciamento de bancos de dados relacionais
O modelo relacional simples, mas eficiente, é usado por organizações de todos os tipos e tamanhos para uma ampla variedade de necessidades de informações. Os bancos de dados relacionais são usados para rastrear inventários, processar transações de comércio eletrônico, gerenciar grandes quantidades de informações essenciais sobre o cliente e muito mais. Um banco de dados relacional pode ser considerado para qualquer necessidade de informações na qual os pontos de dados se relacionam entre si e devem ser gerenciados de maneira segura e consistente, com base em regras.

Bancos de dados relacionais existem desde os anos de 1970. Atualmente, as vantagens do modelo relacional continuam a torná-lo o modelo mais amplamente aceito para bancos de dados.

Modelo relacional e consistência de dados
O modelo relacional é o melhor em manter a consistência de dados entre aplicativos e cópias de banco de dados (chamadas de instâncias). Por exemplo, quando um cliente deposita dinheiro em um caixa eletrônico e analisa o saldo da conta em um celular, o cliente espera ver esse depósito refletido imediatamente em um saldo atualizado da conta. Os bancos de dados relacionais se destacam nesse tipo de consistência de dados, garantindo que várias instâncias de um banco de dados tenham os mesmos dados o tempo todo.

É difícil para outros tipos de bancos de dados manter esse nível de consistência oportuna com grandes quantidades de dados. Alguns bancos de dados recentes, como o NoSQL, podem fornecer somente consistência “eventual.” Sob este princípio, quando o banco de dados é dimensionado ou quando vários usuários acessam os mesmos dados ao mesmo tempo, os dados precisam de algum tempo para "serem atualizados". A consistência eventual é aceitável para alguns usos, como manter listagens em um catálogo de produtos, mas para operações comerciais essenciais, como transações de carrinho de compras, o banco de dados relacional ainda é o padrão ouro.

Compromisso e atomicidade
Os bancos de dados relacionais lidam com regras e políticas de negócios em um nível muito granular, com políticas rígidas sobre compromisso (isto é, fazer uma alteração no banco de dados permanente). Por exemplo, considere um banco de dados de inventário que rastreie três peças que são sempre usadas juntas. Quando uma peça é retirada do inventário, as outras duas também devem ser retiradas. Se uma das três peças não estiver disponível, nenhuma das peças deve ser retirada - todas as três peças devem estar disponíveis antes que o banco de dados confirme. Um banco de dados relacional não confirmará uma peça até que saiba que pode confirmar todas as três. Essa capacidade de compromisso multifacetada é chamada atomicidade. A atomicidade é a chave para manter os dados precisos no banco de dados e garantir que eles estejam em conformidade com regras, regulamentos e políticas da empresa.

Propriedades ACID e RDBMS
Quatro propriedades cruciais definem transações de banco de dados relacional: atomicidade, consistência, isolamento e durabilidade; em geral, denominadas ACID.

A atomicidade define todos os elementos que compõem uma transação completa do banco de dados.
A consistência define as regras para manter os pontos de dados em um estado correto após uma transação.
O isolamento mantém o efeito de uma transação invisível para outras pessoas até ser confirmada, para evitar confusão.
A durabilidade garante que as alterações de dados se tornem permanentes quando a transação for confirmada.
Procedimentos armazenados e bancos de dados relacionais
O acesso a dados envolve muitas ações repetitivas. Por exemplo, uma consulta simples para obter informações de uma tabela de dados pode precisar ser repetida centenas ou milhares de vezes para produzir o resultado desejado. Essas funções de acesso a dados requerem algum tipo de código para acessar o banco de dados. Os desenvolvedores de aplicativos não querem criar um novo código para essas funções a cada aplicativo novo. Felizmente, os bancos de dados relacionais permitem procedimentos armazenados, que são blocos de código que podem ser acessados com uma simples chamada de aplicativo. Por exemplo, um único procedimento armazenado pode fornecer identificação de registro consistente para usuários de vários aplicativos. Os procedimentos armazenados também podem ajudar os desenvolvedores a garantir que determinadas funções de dados no aplicativo sejam implementadas de uma maneira específica.

Bloqueio e simultaneidade de banco de dados
Os conflitos podem surgir em um banco de dados quando vários usuários ou aplicativos tentam alterar os mesmos dados ao mesmo tempo. Técnicas de bloqueio e simultaneidade reduzem o potencial de conflitos, mantendo a integridade dos dados.

O bloqueio impede que outros usuários e aplicativos acessem dados enquanto estão sendo atualizados. Em alguns bancos de dados, o bloqueio se aplica à tabela inteira, o que cria um impacto negativo no desempenho do aplicativo. Outros bancos de dados, como bancos de dados relacionais da Oracle, aplicam bloqueios no nível de registro, deixando os outros registros dentro da tabela disponíveis, ajudando a garantir um melhor desempenho do aplicativo.

A simultaneidade gerencia a atividade quando vários usuários ou aplicativos fazem consultas ao mesmo tempo no mesmo banco de dados. Esse recurso fornece o acesso correto a usuários e aplicativos de acordo com as políticas definidas para o controle de dados.

O que procurar ao selecionar um banco de dados relacional
O software usado para armazenar, gerenciar, consultar e recuperar dados armazenados em um banco de dados relacional é chamado de sistema de gerenciamento de bancos de dados relacionais (RDBMS). O RDBMS fornece uma interface entre usuários e aplicativos e o banco de dados, além de funções administrativas para gerenciar armazenamento, acesso e desempenho de dados.

Vários fatores podem orientar sua decisão ao escolher entre tipos de banco de dados e produtos de banco de dados relacional. O RDBMS escolhido dependerá das suas necessidades de negócios. Pergunte a você mesmo as seguintes questões:

Quais são os nossos requisitos de precisão de dados? O armazenamento e a precisão de dados dependem da lógica de negócios? Nossos dados têm requisitos rigorosos de precisão (por exemplo, dados financeiros e relatórios do governo)?
Precisamos de escalabilidade? Qual é a escala dos dados a serem gerenciados e qual é o crescimento previsto? O modelo de banco de dados precisará oferecer suporte a cópias de banco de dados espelhadas (como instâncias separadas) para escalabilidade? Em caso afirmativo, é possível manter a consistência de dados nessas instâncias?
O quanto a simultaneidade é importante? Vários usuários e aplicativos precisarão de acesso simultâneo a dados? O software de banco de dados oferece suporte à simultaneidade ao mesmo tempo que protege os dados?
Quais são as nossas necessidades de desempenho e confiabilidade? Precisamos de um produto de alto desempenho e alta confiabilidade? Quais são os requisitos para o desempenho de resposta à consulta? Quais são os compromissos do fornecedor com os acordos de nível de serviço (SLAs) ou tempo de inatividade não planejado?
O banco de dados relacional do futuro: o banco de dados autônomo
Ao longo dos anos, os bancos de dados relacionais ficaram melhores, mais rápidos, mais fortes e mais fáceis de se trabalhar. Mas também se tornaram mais complexos e administrar o banco de dados tem sido um job de tempo integral. Em vez de usarem seus conhecimentos para se concentrar no desenvolvimento de aplicativos inovadores que agreguem valor ao negócio, os desenvolvedores passaram a maior parte do tempo na atividade de gerenciamento necessária para otimizar o desempenho do banco de dados.

Atualmente, a tecnologia autônoma está aproveitando os pontos fortes do modelo relacional, da tecnologia de banco de dados em nuvem e de machine learning para fornecer um novo tipo de banco de dados relacional. O banco de dados independente (também conhecido como banco de dados autônomo) mantém a eficiência e as vantagens do modelo relacional, mas usa inteligência artificial (IA), o machine learning e a automação para monitorar e melhorar o desempenho das consultas e as tarefas de gerenciamento. Por exemplo, para melhorar o desempenho da consulta, o banco de dados independente pode criar hipóteses e testar índices para tornar as consultas mais rápidas e enviar as melhores para a produção, tudo por conta própria. O banco de dados independente faz essas melhorias continuamente, sem a necessidade de envolvimento humano.

A tecnologia Autonomous libera os desenvolvedores das tarefas comuns do gerenciamento do banco de dados. Por exemplo, eles não precisam mais determinar os requisitos de infraestrutura com antecedência. Em vez disso, com um banco de dados independente, eles podem adicionar armazenamento e processar recursos conforme necessário para oferecer suporte ao crescimento do banco de dados. Com apenas algumas etapas, os desenvolvedores podem facilmente criar um banco de dados relacional autônomo, acelerando o tempo para o desenvolvimento de aplicativos.


