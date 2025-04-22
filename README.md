# Servico-Cloud-de-Inteligencia-Artificial
Resumo Servico Cloud de Inteligencia Artificial Azure

O que é inteligência Artificial
•	Prever resultados e reconhecer padrões com base em dados históricos
•	Extrair informações de fontes para obter conhecimento
•	Compreender a linguagem e participar de conversas
•	Reconhecer eventos anormais e tomar decisões
•	Interpretando informações pessoais

Cargas de trabalho comuns de IA
•	Machine Learning: Modelos preditivos baseados em dados e estatísticas
•	Visão Computacional: Capacidades da IA parta interpretar o mundo visualmente por meio de câmeras, vídeos e imagens
•	Processamento de linguagem natural: Capacidades de IA para que um computador interprete a linguagem escrita ou falada e responda adequadamente
•	Inteligência de Documantos: Capaciadades de IA que lidam com o gerenciamento, processamento e uso de grandes volumes de dados encontrados em formulários e documentos
•	Mineração de conhecimento: Capacidades da IA para extrair informações de grandes volumes de dados muitas vezes não estruturados para criar um armazenamento de conhecimento pesquisável
•	Ingerir, enriquecer e explorar
•	IA Generativa: Recursos de Ia que criam conteúdo original em vários formatos, incluindo linguagem natural, imagem, código e muito mais

Princípios de IA responsável
•	Imparcialidade: Preconceito pode afetar os resultados. Ex.: preconceito para concedor empréstimo bancário
•	Confiabilidade e segurança: Erros podem causar danos. Ex.: Falha sistema de um veículo autônomo
•	Privacidade e segurança:  Dados privados podem ser expostos. Ex.: Dados confidenciais de um paciente de um banco armazenados de forma insegura
•	Inclusão: As soluções podem não funcionar para todos. Ex.: Aplicativo não fornece saída de áudio para usuários com deficiência visual
•	Transparência: Os usuários devem confiar em um sistema complexo. Ex.: Ferramenta financeira baseada em IA faz recomendações de investimento (em que se baseiam?)
•	Responsabilidade: Quem é responsável pelas decisões baseadas na IA. Ex.: Uma pessoa é condenada por um crime com base em provas de reconhecimento facial – quem é o responsável?

Conceitos de processamento de linguagem netural

Processamento de linguagem natural e IA conversation do Azure
•	Azure Language Studio
•	NER (Reconhecimento de Entidade Nomeada)
  •	Event, Location, DateTime
•	Detecção de PII e PHI
  •	URL, PhoneNumber, Email, Organization
•	Detecção de idioma
•	Análise de Sentimentos
  •	Sentence sentiment, Opinion
•	Respostas a perguntas
  •	ChatBot
•	Fala
  •	Texto para fala
  •	Conversão de fala para texto
  •	Tradução de fala
•	Tradução
  •	Tradução de texto
  •	Tradução de documentos
  •	Tradução personalizada

Capacidades de processamento de linguagem Natural no Azure AI

Analisando texto
•	Language Studio
  •	Repostas a perguntas: Dedfina uma base de conhecimento de pares de perguntas e respostas; Ao inserir perguntas e respostas; De um documento de perguntas frequentes existente; Usando bate-papo integrado

Serviço de bot do Azure
•	Plataforma baseada em nuvem para desenvolvimento e gerenciamento de bots
•	Integração com AI Language e outros serviços
•	Conectividade através de vários canais

Compreensão da linguagem coloquial
•	Linguagem do dia a dia

Reconhecimento e síntese da fala
•	Use os recursos de fala para texto do Serviço de Fala para transcrever fala audível em texto

Inteligência de Documentos de IA do Azure

Serviços de Inteligência de Documentos
•	Análise de Documentos
  •	Retorna representações de dados estruturados
  •	Regiões de interesse e relacionamentos
  •	Configurar opções de análise para análise gratuita e cobrada
•	Modelos pré-contruídos
  •	Faturas
  •	Recibos
  •	Identificador
  •	Reconhece e extrai pares de valores-chave
•	Modelos personalizados
  •	Treine modelos pelo menos cinco dados de amostra
  •	Identifique campos de interesse para sua organização

Analisando formulários com serviço Document Intelligence
•	Extraia informações de formulários digitalizados em formato de imagem ou PDF
•	Explore Form Recognition
•	Use modelos pré-treinados para tipos de documentos comuns, como faturas, recibos, IDs, etc
•	Treine um modelo personalizado usando seus próprios formulários
•	Os modelos realizam reconhecimento semântico de campos de formulário – não apenas extração de texto

Estúdio de Inteligência de Documentos
•	Usando uma abordagem sem código, você pode explorar a funcionalidade usando exemplos  e seus próprios documentos
•	Primeiro crie um recurso
  •	Recurso de Inteligência de Documentos
  •	Recurso de serviços de IA
•	Em seguida, habilite o recurso do Document Intelligence Studio
•	Página de primeiros passos: selecione um modelo para experimentar

Azure Cognitive Search: Utilizando AI Search para indexação e consulta de dados
Pesquisa Cognitiva do Azure

Mineração de Conhecimento
•	Os dados são bloqueados em documentos, PDFs, notas manuscritas, etc
•	A mineração de conhecimento encontra insights- em escala
•	Azure Cognitive Search é a plataforma de mineração de conhecimento alimentada por IA do Azure

Solução de Pesquisa Cognitiva do Azure
•	Ingestão de dados
  •	Azure Blob Storage containers
  •	Azure Data Lake Storage Gen2
  •	Azure Table Storage
•	Enriquecimento de índice de IA
  •	Permite uma compreensão mais profunda
  •	Visão, Processamento de Linguagem Natural, etc.
  •	A indexação torna o conteúdo pesquisável
•	Explorar
  •	Pesquisa realizada em índices
  •	Dentro dos aplicativos
  •	Crie visualizações de dados

Enriquecimento de IA
•	Pesquisa Cognitiva do Azure
  •	O enriquecimento de IA torna o conteúdo mais útil para fins de pesquisa
•	Conteúdo enriquecido é criado por conjuntos de habilidades como:
  •	Reconhecer entidades no texto
  •	Traduzir texto
  •	Avalie o sentimento
•	Um conjunto de habilidades produz documentos enriquecidos
  •	Consumido durante a indexação
  •	Os dados serializados são passados ao mecanismo de pesquisa para indexação

Fundamentos da IA Generativa

O que é IA Generativa
•	Imita o comportamento humano usando aprendizado de máquina para interagir com o ambiente e executar tarefas sem instruções explpicitas sobre o que gerar
•	Cria conteúdo original, como IA generativa foi incorporada a aplicativos de chat. Os aplicativos de IA generativa usam entrada em linguagem natural e retornam respostas apropriadas em uma variedade de formatos:
  •	Geração de linguagem natural
  •	Geração de código
  •	Geração de imagem
  
Modelos de linguagem grandes
•	Os aplicativos de IA gerativa são alimentados por LLMs (Modelos de Linguagem Grandes), que são um tipo especializado de modelo de machine learning que você pode usar para executar tarefas de PLN (Processamento de Linguagem Natural), incluindo:
  •	Determinar sentimento ou classificar de outra formao texto em idioma natural
  •	Resumir um texto
  •	Comparar várias fontes de texto quanto à similaridade semântica
  •	Geração de nova linguagem natural
  
Modelos de Linguagem Grandes – Transformador
•	Arquitetura do modelo do transformador consiste em dois componentes principais, ou blocos.
  •	Um bloco codificador que cria representações semânticas do vocabulário de treinamento
  •	Um bloco decodificador que gera novas sequências de linguagem
•	O texto é tokenizado para cada palavra dou frase representada por um token numérico exclusivo
•	Insersões (valores de vetor com várias dimensões) são atribuídas aos tokens
•	As camadas de atenção examinam cada token por veze determinam valores incorpotados que refletem os relacionamentos semânticos entre tokens
•	No decodificador, essas relações são usadas para prever a sequência provável de tokens.

Modelos de Linguagem Grandes – Tokenização
Tokenização (Etapa 1)
•	Treinamento de um modelo de transformador é decompor o texto de treinamento em tokens

Modelos de Linguagem Grandes – Insersões
Inserções (Etapa 2)
•	As relações entre tokens são capturadas como vetores, conhecidos como inserções
•	“Encaixar as palavras de uma forma que elas façam sentido”

Modelos de Linguagem Grandes – Atenção
Atenção (Etapa 3)
•	Capture a força das relações entre tokens usando a técnica de atenção

Copilotos
•	Os copilotos são frequentemente integrados a outros aplicativos e fornecem uma maneira para os usuários obterem ajuda com tarefas comuns a partir de um modelo generativo de IA
•	Os desenvolvedores podem criar copilotos que enviam prompts para grandes modelos de linguagem e geram conteúdo para uso em aplicativos
•	Os usuários empresariais podem usar copilotos para aumentar sua produtividade e criatividade com conteúdo gerado por IA

Engenharia de prompts
•	O termo engenharia de prompt descreve o processo de aprimoramento de prompts
•	Aprimorar respostas de IA generativa
•	Os desenvolvedores que projetam aplicativos e consumidores que usam aplicativos podem aprimorar a qualidade das respostas da IA generativa  usando linguagem direta, mensagens do sistema, exemplos e/ou dados de fundamentação
•	Linguagem direta: você pode obter conclusões mais úteis sendo explícito sobre o tipo de resposta que deseja. Ex.: “Crie uma lista de 10 coisas para fazer em Endimburgo durante o mês de agosto”
•	Mensagens do sistema: descreva como o chat deve funcionar. Ex.: “Você é um assistente útil que responde de maneira alegre amigável”.
•	Fornecer exemplos: As LLMs geralmente dão suporte ao aprendizado zero-shot no qual as respostas podem ser geradas sem exemplos anteriores. No entanto, vpc}e também pode fornecer algumas respostas de exemplo, conhecidas como aprendizado de poucas capturas. Ex.: “Visite o castelo pela manhã, antes que as multidões cheguem”
•	Dados Básicos: Os prompts podem incluir dados de fundamentação para fornecer contexto. Ex.: Incluindo o texto de email com a mensagem “Resumir meu email”.
•	

Trabalhando com Serviços Azure OpenAI
OpenAI
•	Serviço OpenAI do Azure é a solução de nuvem da Microsoft para implantar, personalizar e hospedar modelos de linguagem grandes
•	Os serviços OpenAI do Azure consistem em 
  •	Modelos de IA generativa predefinidos
  •	Funcionalidades de personalização
  •	Ferramentas integradas paradetectar e mitigar casos deuso prejudiciais para que os usuários possam implementar a IA com responsabilidade
  •	Segurança corporativa com RBAC(Controle de acesso baseado em função) e redes privadas
•	Métodos para desenvolver soluções do Azure OpenAI:
  •	Estúdio de IA do Azure
  •	API REST
  •	SDKs com suporte e CLI do Azure
  
A quais modelos o OpenAI da Azure dá suporte?
•	GPT-4
•	GPT-3.5
•	Incorporações
•	DALL-E (visualização)

Como usar o OpenAI do Azure
•	Estúdio Azure OpenAI
  •	Crie e implante modelos de IA para aplicativos de software
  •	Alimentado por modelos generativos de IA otimizados para diversas tarefas
  •	Modelos Azure OpenAI incluem: modelos GPT-4, GPT-3.5, Embeddings e DALL-E
  •	Playgrounds
    	Experimente modelos Azure OpenAI sem codificação
    	Use a configuração do assistente para instruir o modelo sobre como ele deve se comportar
    
Funcionalidades de linguagem natural do OpenAI do Azure
•	Os modelos de GPT (transformadores pré-treinados generativos) são excelentes para entender e criar linguagem natural

Explorando os Recursos de IA Generativa com Copilot e OpenAI
Planejar uma solução de IA generativa responsável
•	As quatro fases do processo para desenvolver e implementar um plano de IA responsável são:
  •	Identificar: possíveis danos relevantes para a solução planejada
  •	 Medida: a presença desses danos das saídas geradas pela solução
  •	 Mitigar: os danos em várias camadas em sua solução para minimizar a presença e impacto deles
  •	Operar: a solução com responsabilidade definindo e seguindo um plano de implantação e de preparação operacional


