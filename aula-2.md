# Técnicas de prompt

- Clareza nas instruções
- Dividir tarefas complexas em tarefas menores.
- Pedir justificativas para a IA.

> **Alucinação**
> Perguntas não fazem sentido, gerarão respostas que não são reais.
## Zero-shot

Quando não é dado nenhum exemplo, referencia.
## Few-shot 

Quando o prompt possui alguns exemplos.
### Chain-of-Thought

Cadeia de pensamento.

Explicar o que você quer que a IA faça e fornecer exemplos

## Self consistence

Utilizada para coisas mais precisas.

Realizar vários prompts.

Ex: Enviar 10 vezes o mesmo prompt, e pedir para a IA analisar as respostas que ele mesmo enviou e qual foi a mais comum.
# Camadas do Gemini

- Engenharia de prompt
- Parâmetros de execução
- Configurações de segurança
- Redução intrinsíca do modelo para informações inventadas ou alucinadas
## Desafios

- Use a técnica de Few-shot Chain-of-Thought para um problema da sua vida real;

- Escolha 10 textos do seu site de notícias preferido. Apresente para o Google AI Studio o padrão dos títulos e das suas respectivas notícias e quando chegar no décimo primeiro texto, apresente somente a notícia e peça para ele gerar um título. Veja se existe alguma técnica ou padrão;
---
- Paper da OpenAI ["Language Models are Few-Shot Learners"](https://arxiv.org/abs/2005.14165)
- Paper do Google ["Chain-of-Thought Prompting Elicits Reasoning in Large Language Models"](https://arxiv.org/abs/2201.11903)
- Paper do Google ["Least-to-Most Prompting Enables Complex Reasoning in Large Language Models"](https://arxiv.org/abs/2205.10625)
- Paper do Google ["Self-Consistency Improves Chain of Thought Reasoning in Language Models"](https://arxiv.org/abs/2203.11171)
- [O que é Engenharia de Prompt e quais as suas principais técnicas?](https://www.alura.com.br/artigos/engenharia-prompt#principios-para-a-criacao-de-um-prompt)