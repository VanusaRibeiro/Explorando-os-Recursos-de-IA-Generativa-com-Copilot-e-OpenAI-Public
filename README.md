# Explorando-os-Recursos-de-IA-Generativa-com-Copilot-e-OpenAI-Public
O que é IA generativa?<br>
IA generativa: cria conteúdo original, como IA gerativa que foi incorporada a aplicativos de chat. Os aplicativos de IA gerativa usam entrada em linguagem natural e retornam respostas apropriadas em uma variedade de formatos:

* Geração de linguagem natural (onde se pode trazer uma instrução, como melhorar ou criar um texto no chat GPT)

* Geração de cógido (ajuda na automação e processo de aprendizado)

* Geração de imagem (impagens pixar ou de persona através de instruções passadas para a IA)</br>

<h1>Modelos de linguagem grandes</h1>
<br>Os aplicativos de IA gerativa são alimentados por LLMs (modelo de linguagem grandes), que são um tipo especializado de modelo de machine learning que você pode usar para executar tarefas de PLN (processamento de linguagem natural), incluindo:<br>


* Determinar sentimento ou classimar de outra forma o texto em idioma natural.</br>
* Resumir um texto.</br>
* Comparar várias fontes de texto quanto à similaridade semântica.</br>
* Geração de nova linguagem natural.</br>

<h1>Modelos de linguagem grandes - transformador</h1>
Grandes modelos de linguagem (LLM) são sistemas de IA que compreendem e geram linguagem humana através do processamento de grandes quantidades de dados.<br>
Os Transformer LLMs são capazes de treinamento não supervisionado, embora uma explicação mais precisa seja que os transformadores realizam autoaprendizagem. É por meio desse processo que os transformadores aprendem a entender a gramática, os idiomas e o conhecimento básicos.<br><br>
Por que grandes modelos de linguagem são importantes?<br><br>
Os LLMs são grandes, muito grandes. Eles podem considerar bilhões de parâmetros e têm muitos usos possíveis. Veja alguns exemplos:

O modelo GPT-3 da Open AI tem 175 bilhões de parâmetros. Seu primo, o ChatGPT, pode identificar padrões a partir de dados e gerar resultados naturais e legíveis. Embora não saibamos o tamanho do Claude 2, ele pode inserir até 100 mil tokens em cada prompt, o que significa que ele pode funcionar em centenas de páginas de documentação técnica ou até mesmo em um livro inteiro.
O modelo Jurassic-1 da AI21 Labs tem 178 bilhões de parâmetros e um vocabulário simbólico de partes de 250.000 palavras e recursos de conversação semelhantes.
O modelo Command da Cohere tem recursos semelhantes e pode funcionar em mais de 100 idiomas diferentes.
O Paradigm da LightOn oferece modelos de base com recursos declarados que excedem os do GPT-3. Todos esses LLMs vêm com APIs que permitem aos desenvolvedores criar aplicações exclusivos de IA generativa.
Grandes modelos de linguagem são incrivelmente flexíveis. Um modelo pode realizar tarefas completamente diferentes, como responder perguntas, resumir documentos, traduzir idiomas e completar frases. Os LLMs têm o potencial de interromper a criação de conteúdo e a forma como as pessoas usam mecanismos de pesquisa e assistentes virtuais.<br><br>
Como os grandes modelos de linguagem são treinados?<br><br>

As redes neurais baseadas em transformadores são muito grandes. Essas redes contêm vários nós e camadas. Cada nó em uma camada tem conexões com todos os nós na camada subsequente, cada um com um peso e um viés. Os pesos e vieses, juntamente com as incorporações, são conhecidos como parâmetros do modelo. Grandes redes neurais baseadas em transformadores podem ter bilhões de parâmetros. O tamanho do modelo geralmente é determinado por uma relação empírica entre o tamanho do modelo, o número de parâmetros e o tamanho dos dados de treinamento.

O treinamento é realizado usando um grande corpus de dados de alta qualidade. Durante o treinamento, o modelo ajusta iterativamente os valores dos parâmetros até que o modelo preveja corretamente o próximo token e a sequência anterior de tokens de entrada. Isso é feito por meio de técnicas de autoaprendizagem que ensinam o modelo a ajustar parâmetros para maximizar a probabilidade dos próximos tokens nos exemplos de treinamento.

Uma vez treinados, os LLMs podem ser facilmente adaptados para realizar várias tarefas usando conjuntos relativamente pequenos de dados supervisionados, um processo conhecido como ajuste fino.

Existem três modelos comuns de aprendizado:

Zero-shot learning: os LLMs básicos podem responder a uma grande variedade de solicitações sem treinamento explícito, geralmente por meio de prompts, embora a precisão das respostas varie.
Few-shot learning: ao fornecer alguns exemplos de treinamento relevantes, o desempenho do modelo de base melhora significativamente na área específica.
Ajuste fino: essa é uma extensão do few-shot learning, pois cientistas de dados treinam um modelo de base para ajustar seus parâmetros com dados adicionais relevantes para a aplicação específica.



A arquitetura do modelo do transformador consiste em dois componentes principais, ou blocos:<br>

Um bloco codificador que cria representações semânticas do vocabulários de treinamento.<br>
Um bloco decodificador que gera novas sequências de linguagem.<br>
O texto é tokenizado para que cada palabra ou frase seja representada por um token numérico exclusivo.<br>
Inserções (valores de vetor com várias dimensões) são atribuídas aos tokens.<br>
As camadas de atenção examinam cada token por vez e determinam valores incorporados que refletem os relacionamentos semânticos entre os tokens.<br>
No decodificador, essas relações são usadas para prever a sequência mais provável de tokens.<br>




<h1>Modelos de linguagem grandes - tokenização</h1>

Etapa 1: tokenização
A primeira etapa no treinamento de um modelo de transformador é decompor o texto de treinamento de tokens.

Etapa 2: inserções ou incorporações

As inserções entre tokens são capturadas como vetores, conhecidos como inserções.



Modelos de linguagem grandes - atenção

Etapa 3: - Captura a força das relações entre tokens usando a técnica de atenção.

Copilotos

Os copilotos são frequentemente integrados a outros aplicativos e fornecem uma maneira para os usuários obterem ajuda com tarefas comuns a partir de um modelo generativo de IA.

Os desenvolvedores podem criar copilotos que enviam prompts para grandes modelos de linguagem e geram conteúdo para uso em aplicativos.


Aprimorar as respostas de IA generativa com a engenharia de prompts
O termo engenharia de prompt descreve o processo de aprimoramento de prompts.

Os desenvolvedores que projetam aplicativos e consumidores que usam aplicativos podem aprimoar a qualidade das respostas da IA gerativa usando linguagem direta, mensagem do sistema, exemplos e/ou dados de fundamentação.

Fundamentos do Serviço Azure OpenAI
O que é o OpenAI do Azure?

O Serviço OpenAI do Azure é a solução de nuvem da Microsoft para implantar, personalizar e hospedar modelos de linguagens grandes.

Os serviços OpenAI do Azure consiste em:
Modelos de IA gerativa predinidos.
Funcionalidades de personalização.
Ferramentas integradas para detectar e mitigar casos de uso prejudiciais para que os usuários possam implementar a IA com responsabilidade.
Segurança corporativa com RBAC (controle de acesso baseado em função) e redes privadas.

É possível usar vários métodos para desenvolver soluções do Azure OpenAI:
Estúdio de IA do Azure;
API REST;
SDKs com suporte de CLI do Azure.
Como usar o OpenAI do Azure
Estúdio Azure OpenAI:

Criar e implantar modelos de IA para aplicativos de software.

Alimentado por modelos de IA gerativa otimizados para tarefas diversas.

Modelos Azure OpenAI incluem: modelos GPT-4, GPT-3.5, Embeddings e DALL-E


Playgrounds:
Experimente modelos Azure OpenAI sem codificação

Use a configuração do assistente para instruir o modelo sobre como ele deve se comportar


Funcionalidade de linguagem natural do OpenAI do Azure
Os modelos de GPT (transformadores pré-treinados generativos) são excelentes para entender e criar linguagem natural.
Os modelos GPT traduzem linguagem natural ou trechos de código em código.
A geração de código vai além de apenas escrever código a partir de prompts em linguagem natural.
Os modelos de IA gerativa podem editar e criar imagens. O modelo que funciona com imagens é chamado DELL-E, que dá suporte à criação de imagem, edição de imagem e criação de variações de imagem.

Geração de imagens: Com o DALL-E é possível até solicitar uma imagem em um determinado estilo. Os estilos também podem ser usados para edições e variações.

Editando uma imagem: DALL-E pode editar a imagem conforme solicitado, alterando seu estilo, adicionando ou removendo itens ou gerando novo conteúdo para adicionar.

Variações de imagem: Variação de imagem podem ser criadas fornecendo uma imagem especificando quantas variações da imagem você deseja.

IA generativa responsável
Planejar uma solução de IA generativa responsável

As quatros fases do processo para desenvolver e implementar um plano de IA responsável são:

   Identificar, Medida, Mitigar e Operar



Links:
https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/12-generative-ai.html


https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/13-azure-openai.html


https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/14-azure-openai-content-filters.html

