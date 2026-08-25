# *Engenharia de Prompts*

Durante o projeto, foram testadas diferentes formas de fazer perguntas ao NotebookLM. O objetivo foi observar como alterações na estrutura do prompt influenciavam a qualidade, profundidade e organização das respostas.

- Prompt 1 — abordagem simples

O que é teste de usabilidade?

Resultado

O NotebookLM apresentou uma definição e, posteriormente, ampliou a resposta para elementos fundamentais, objetivos, métricas e diferenças entre testes de usabilidade e experimentos científicos.

Problema identificado

O prompt era muito amplo e não especificava a profundidade ou a estrutura desejada. Como consequência, a resposta apresentou informações além do necessário para uma primeira definição do conceito.

- Prompt 2 — abordagem específica

Explique o que é teste de usabilidade, seu objetivo, principais etapas e exemplos de aplicação. Baseie-se apenas nas fontes disponibilizadas.

Resultado

A resposta ficou mais estruturada, apresentando:

Definição;
Elementos fundamentais;
Objetivos;
Etapas;
Exemplos de aplicação.

Problema identificado

O prompt melhorou o direcionamento, mas ainda não solicitava que as informações fossem relacionadas individualmente às fontes, o que dificultava a verificação de cada afirmação.

- Prompt 3 — abordagem elaborada

Atue como um professor de UX Design. Com base exclusivamente nas fontes disponibilizadas, explique o conceito de teste de usabilidade para um estudante iniciante. Apresente: definição, objetivos, preparação, execução, análise dos resultados e um exemplo prático. Sempre indique a fonte utilizada para cada informação relevante e sinalize quando as fontes não apresentarem determinada informação.

Resultado

A resposta apresentou uma estrutura mais completa e adequada para estudo, contemplando definição, objetivos, preparação, execução, análise e exemplo prático. Também houve maior preocupação com a utilização das fontes e com a identificação de lacunas.

Problema identificado

O excesso de instruções e o nível de detalhamento solicitado fizeram com que a resposta se tornasse mais extensa. Algumas explicações poderiam ser reduzidas para facilitar uma revisão rápida.

# Aprendizados com os testes

A comparação mostrou que a qualidade da resposta não depende apenas da ferramenta utilizada, mas também da forma como a pergunta é construída.

O primeiro prompt apresentou uma resposta ampla, mas pouco direcionada. O segundo trouxe maior organização ao definir os tópicos esperados. O terceiro permitiu um maior controle sobre a resposta, mas também demonstrou que prompts muito detalhados podem gerar respostas extensas.

Assim, o principal aprendizado foi buscar um equilíbrio entre:
Contexto + objetivo + estrutura + fontes + nível de profundidade.
