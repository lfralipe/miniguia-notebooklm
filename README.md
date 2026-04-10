📚 Miniguia de Estudos com NotebookLM

Tema: Engenharia de Prompt e Uso de IA para Aprendizagem Ativa


🎯 Contexto e Objetivos

Este projeto tem como objetivo explorar o uso da Inteligência Artificial, especialmente o NotebookLM, como ferramenta de aprendizagem ativa.

O tema escolhido foi Engenharia de Prompt, devido à sua crescente relevância no uso de modelos de linguagem como o ChatGPT.

Objetivos de estudo:
Compreender os principais tipos de prompts (Zero-shot, Few-shot, Chain of Thought, etc.)
Aprender a estruturar prompts mais eficazes
Desenvolver pensamento crítico ao interagir com IA
Criar um material reutilizável para revisões futuras


📖 Curadoria de Fontes

As seguintes fontes foram utilizadas e inseridas no NotebookLM:

https://www.promptingguide.ai/
https://platform.openai.com/docs/guides/prompt-engineering
https://arxiv.org/pdf/2201.11903.pdf (Chain-of-Thought Prompting)
https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/
https://cloud.google.com/blog/products/ai-machine-learning/prompt-engineering-best-practices


🧠 Engenharia de Prompts e "Cicatrizes"

Aqui estão os principais prompts utilizados, incluindo tentativas, erros e aprendizados.

🔹 Prompt 1 (Inicial - Simples)

Pergunta:
"O que é engenharia de prompt?"

Engenharia de prompt é uma disciplina relativamente nova voltada para o desenvolvimento e a otimização de instruções (prompts) para utilizar modelos de linguagem de forma eficiente em uma ampla variedade de aplicações e tópicos de pesquisa
. Em termos práticos, é o processo de escrever instruções eficazes para que o modelo gere consistentemente conteúdos que atendam aos requisitos específicos do usuário
.
De acordo com as fontes, os principais aspectos dessa prática incluem:
Mistura de arte e ciência: Como o conteúdo gerado pelos modelos é não-determinístico, a engenharia de prompt exige tanto técnica quanto criatividade para obter os resultados desejados de forma consistente
.
Compreensão de capacidades e limitações: Essas habilidades ajudam a entender melhor o que os Grandes Modelos de Linguagem (LLMs) conseguem ou não fazer, permitindo o design de técnicas de interface robustas
.
Desenvolvimento de aplicações: Desenvolvedores utilizam a engenharia de prompt para construir capacidades que antes eram impossíveis ou excessivamente caras, como resumo de textos, extração de tópicos, tradução e escrita automática de e-mails
.
Melhoria do raciocínio e segurança: A disciplina não se limita apenas a projetar comandos; ela engloba técnicas para melhorar a segurança dos modelos e criar novas funcionalidades, como o uso de ferramentas externas e o fornecimento de conhecimento de domínio específico
.
Raciocínio em várias etapas: Uma técnica avançada, como o chain-of-thought prompting (prompt de cadeia de pensamento), permite que o modelo decomponha problemas complexos em etapas intermediárias de raciocínio, melhorando significativamente o desempenho em tarefas aritméticas, simbólicas e de senso comum
.
A engenharia de prompt é considerada uma habilidade essencial para interfacear, construir e entender o potencial dos LLMs modernos
. Como diferentes modelos (como os de raciocínio versus os modelos GPT padrão) podem responder melhor a diferentes tipos de instruções, a prática envolve o uso de estratégias, melhores práticas e iteração contínua para otimizar o desempenho
.

Problema:
Resposta muito genérica.


🔹 Prompt 2 (Melhorado)

"Explique o que é engenharia de prompt, com exemplos práticos e aplicações no dia a dia."
A engenharia de prompt é uma disciplina voltada para o desenvolvimento e a otimização de instruções (prompts) para utilizar modelos de linguagem (LMs) de forma eficiente em diversas aplicações e pesquisas
. Ela consiste no processo de escrever comandos eficazes para que o modelo gere conteúdos que atendam consistentemente aos requisitos do usuário
. Como os modelos são não-determinísticos, essa prática é considerada uma mistura de arte e ciência, exigindo técnicas e melhores práticas para obter resultados robustos
.
Exemplos Práticos de Técnicas
Abaixo estão algumas das principais estratégias utilizadas na engenharia de prompt:
Papéis de Mensagem (Message Roles): É possível atribuir diferentes autoridades às instruções usando papéis como developer (regras do sistema e lógica de negócio), user (entrada do usuário final) e assistant (a resposta gerada pelo modelo)
.
Aprendizado com Poucos Exemplos (Few-shot Prompting): Consiste em incluir alguns exemplos de entrada e saída no próprio prompt para mostrar ao modelo o padrão desejado, evitando a necessidade de treinamento adicional
.
Cadeia de Pensamento (Chain-of-Thought - CoT): Esta técnica incentiva o modelo a gerar etapas intermediárias de raciocínio antes de fornecer a resposta final
. Isso melhora drasticamente o desempenho em tarefas complexas de aritmética, lógica e senso comum
.
Uso de Delimitadores: Utilizar formatação Markdown ou tags XML (como <contexto></contexto>) ajuda o modelo a entender os limites lógicos e a hierarquia das informações fornecidas
.
Aplicações no Dia a Dia
A engenharia de prompt permite construir rapidamente capacidades que antes eram caras ou impossíveis
. Entre as aplicações cotidianas destacam-se:
Resumo (Summarizing): Condensar textos longos, como avaliações de usuários ou artigos, para torná-los mais breves
.
Inferência (Inferring): Classificar o sentimento de um texto (positivo ou negativo) ou extrair tópicos automaticamente
.
Transformação de Texto (Transforming): Realizar traduções entre idiomas, além de correções ortográficas e gramaticais
.
Expansão (Expanding): Escrever automaticamente e-mails ou textos longos a partir de notas curtas
.
Programação e Dados: Gerar trechos de código, consultas SQL e realizar a extração de dados estruturados em formato JSON
.
Chatbots Customizados: Criar assistentes virtuais especializados em domínios de conhecimento específicos
.
O domínio dessas habilidades permite não apenas interagir melhor com as IAs, mas também aumentar a segurança dos modelos e expandir suas capacidades através do uso de ferramentas externas
.

Resultado:
Resposta mais completa e útil.


🔹 Prompt 3 (Few-shot)

"Explique os tipos de prompt:
Exemplo:
Zero-shot: quando não há exemplos
Few-shot: quando há exemplos
Agora explique os demais."

Com base nas fontes, além do Zero-shot (quando o modelo realiza uma tarefa sem exemplos prévios)
 e do Few-shot (onde são fornecidos alguns exemplos de entrada e saída para guiar o modelo)
, existem diversas outras técnicas avançadas de engenharia de prompt:
Cadeia de Pensamento (Chain-of-Thought - CoT): Esta técnica consiste em incluir triplas de <entrada, cadeia de pensamento, saída> no prompt
. A "cadeia de pensamento" é uma série de etapas intermediárias de raciocínio em linguagem natural que levam à resposta final, permitindo que o modelo decomponha problemas complexos em passos menores
.
Auto-consistência (Self-Consistency): É uma técnica que melhora o raciocínio da Cadeia de Pensamento ao gerar múltiplos caminhos de raciocínio e, em seguida, selecionar a resposta final mais frequente (voto majoritário) entre todas as gerações amostradas
.
Encadeamento de Prompts (Prompt Chaining): Envolve a decomposição de uma tarefa complexa em subtarefas sequenciais
. A saída de um prompt torna-se a entrada do próximo, permitindo que o usuário tenha mais controle e transparência sobre o fluxo de interação
.
Geração Aumentada por Recuperação (RAG): Consiste em fornecer ao modelo informações de contexto relevantes e externas (como dados proprietários ou documentos de uma base de dados) dentro do próprio prompt
. Isso ajuda a fundamentar a resposta em fatos específicos que não estavam nos dados de treinamento originais do modelo
.
Árvore de Pensamentos (Tree of Thoughts): É uma estrutura onde o modelo explora múltiplos ramos de raciocínio de forma simultânea, permitindo uma busca mais profunda e a avaliação de diferentes soluções antes de decidir pelo caminho final
.
ReAct (Reasoning and Acting): Combina a geração de raciocínio verbal com a execução de ações (como usar ferramentas externas)
. O modelo gera um pensamento sobre a tarefa, executa uma ação (como uma busca na web) e observa o resultado para continuar o raciocínio
.
Prompt de Estímulo Direcional (Directional Stimulus Prompting): Utiliza um modelo menor para gerar "pistas" ou palavras-chave que guiam o modelo principal a gerar uma resposta mais precisa e focada
.
Meta Prompting: Envolve a criação de prompts que instruem o modelo sobre como ele deve criar ou otimizar outros prompts
.
Essas técnicas visam superar limitações dos modelos em tarefas que exigem raciocínio aritmético, simbólico, de senso comum ou o uso de ferramentas externas

Resultado:
Resposta mais estruturada.


🔹 Prompt 4 (Chain of Thought)

"Explique passo a passo como criar um bom prompt para resolver problemas complexos."
Para resolver problemas complexos usando engenharia de prompt, as fontes sugerem um processo estruturado que combina clareza técnica com estratégias de raciocínio. Abaixo, apresento um passo a passo baseado nas melhores práticas documentadas:
1. Defina a Identidade e o Objetivo (Persona)
O primeiro passo é estabelecer o papel do modelo. Descrever o propósito e o estilo de comunicação ajuda a guiar a geração da resposta
.
Dica: Para tarefas técnicas, enquadre o modelo como um "agente de engenharia de software" ou um "colega de trabalho sênior" para tarefas que exigem autonomia na resolução de problemas
.
2. Estruture o Prompt com Delimitadores
Use uma combinação de formatação Markdown (como cabeçalhos e listas) e tags XML (como <instruções></instruções> ou <contexto></contexto>)
. Isso ajuda o modelo a entender as fronteiras lógicas do seu comando e a hierarquia das informações fornecidas, tornando o prompt mais legível e eficaz
.
3. Forneça Instruções Claras e Regras de Negócio
Seja explícito sobre o que o modelo deve fazer e, igualmente importante, o que não deve fazer
.
Regras de Saída: Se precisar de um formato específico (como JSON), utilize a funcionalidade de Structured Outputs para garantir a conformidade
.
Priorização: Lembre-se que instruções enviadas via parâmetros de desenvolvedor (developer messages) têm prioridade sobre as mensagens do usuário
.
4. Implemente a "Cadeia de Pensamento" (Chain-of-Thought)
Esta é a técnica mais eficaz para problemas que exigem raciocínio aritmético, simbólico ou de senso comum
. Em vez de pedir apenas o resultado final, instrua o modelo a decompor o problema em etapas intermediárias antes de responder
.
Exemplos de "Few-Shot": Inclua no prompt alguns exemplos de triplas: <entrada, cadeia de pensamento, saída>
. Mostrar ao modelo como resolver um problema passo a passo faz com que ele "aprenda" o padrão de raciocínio desejado
.
5. Adicione Contexto Relevante (RAG)
Para problemas que dependem de informações que o modelo não conhece (dados privados ou atualizações recentes), inclua esse conteúdo diretamente no prompt
. Posicione os dados de apoio/contexto geralmente no final do prompt para que as instruções principais já tenham sido estabelecidas
.
6. Dê "Tempo para Pensar" ao Modelo
Um dos princípios fundamentais é não apressar o modelo para uma conclusão
. Instrua-o explicitamente a verificar sua própria lógica ou a realizar testes (como testes unitários em código) antes de fornecer a solução final
. Modelos de raciocínio específicos tendem a performar melhor quando recebem apenas orientações de alto nível e têm liberdade para trabalhar nos detalhes
.
7. Itere e Avalie (Processo Evolutivo)
A engenharia de prompt é um processo iterativo
. As fontes recomendam:
Testes e Evals: Crie sistemas de avaliação (evals) para medir o comportamento do seu prompt e monitorar a performance conforme você faz ajustes
.
Refinamento: Se a resposta não for satisfatória, verifique se houve erro de mapeamento de símbolos, falta de uma etapa de raciocínio ou erro de compreensão semântica e ajuste os exemplos fornecidos
.
Seguir esses passos permite que modelos de larga escala (acima de 100 bilhões de parâmetros) desbloqueiem capacidades de raciocínio que não seriam possíveis com comandos simples e diretos
.


Resultado:
Melhor organização e raciocínio.



⚠️ Dificuldades Encontradas:
Quando eu fiz uma pergunta mais vaga recebi uma resposta mais genérica.

✅ Aprendizados:
Ser mais específico na hora de perguntar para receber resposta melhorse
