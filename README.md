# lab-generative-ai
Laboratório de IA Generativa com Azure OpenAI - Desafio DIO
# Projeto de Laboratório: Explorando IA Generativa com Azure OpenAI e Microsoft Copilot

## 🎯 Descrição do Desafio

Este projeto, parte de um desafio de laboratório, tem como objetivo explorar as funcionalidades da Inteligência Artificial Generativa utilizando as ferramentas da Microsoft.O foco principal foi a utilização do Microsoft Copilot e dos serviços do Azure OpenAI, incluindo a criação de recursos, o deployment de modelos e a interação com agentes de IA para tarefas práticas. O entregável é este repositório, que documenta a experiência, os prompts utilizados e os aprendizados adquiridos. [cite: 315]

## 🛠️ Ferramentas Utilizadas

* **Microsoft Azure:** Plataforma de nuvem utilizada para provisionar os serviços de IA.
* **Azure OpenAI Service:** Serviço gerenciado que permite o acesso e a utilização de modelos de linguagem da OpenAI.
* **Azure AI Studio:** Ambiente de desenvolvimento para criar, gerenciar e implantar modelos de IA, incluindo um playground para testes.
* **Microsoft Copilot:** Assistente de IA da Microsoft para realizar tarefas e obter informações.

## 📄 Passo a Passo do Laboratório

A seguir, estão detalhadas as etapas realizadas para a conclusão deste estudo prático.

### 1. Criação do Recurso Azure OpenAI

O primeiro passo foi a criação de um recurso do Azure OpenAI na plataforma da Microsoft. As seguintes configurações foram aplicadas:

**Assinatura:** Azure subscription 1
**Grupo de Recursos:** openai 
**Região:** East US 
**Nome do Recurso:** cesargpe 
**Tipo de Preço:** Standard S0

A rede foi configurada para permitir que todos os serviços, incluindo a internet, pudessem acessar o recurso. 

### 2. Seleção e Implantação do Modelo

Dentro do Azure AI Studio, no "Playground de chat", foi selecionado um modelo para implantação.

**Modelo Escolhido:** `gpt-4o` 
**Justificativa:** O `gpt-4o` foi escolhido por sua eficiência, velocidade e performance aprimorada em múltiplas linguagens. Suas capacidades avançadas de lidar com consultas complexas e integrar diversos tipos de dados são ideais para aprimorar interações de suporte e análise de dados. 
**Versão do Modelo:** `gpt-4o (version: 2024-11-20)` 

### 3. Interação no Playground de Agentes do Azure AI

Com o modelo implantado, um novo agente de IA (`Agent633`) foi criado no Playground de Agentes para simular um assistente de planejamento de viagens. Uma série de prompts foi enviada para testar a capacidade de conversação e manutenção de contexto do agente:

1.  **Primeira Interação:** O diálogo foi iniciado com um pedido de ajuda para planejar uma viagem.
   **Prompt:** `I'm planning a trip to Paris in September Can you help me?` 
    **Resposta do Agente:** "Absolutely! Paris in September is a great idea-it's a beautiful time to visit with pleasant weather, fewer crowds compared to peak summer, and lots to do!" 
2.  **Aprofundando a Conversa:** Em seguida, a conversa focou em encontrar uma boa localização para estadia.
    **Prompt:** `Where's a good location in Paris to stay?`
   **Resposta do Agente:** "The best location to stay in Paris depends on your budget and travel preferences... Below are some excellent areas to consider: 1. Le Marais (3rd & 4th Arrondissements)" 

3.  **Testando a Recuperação de Informação Externa:** O agente foi desafiado a buscar informações em uma fonte externa (URL).
   **Prompt:** `Based on the information at https://en.wikipedia.org/wiki/History_of_Paris, what were the key events in the city's history?` 
4.  **Prompts Adicionais:** Outras perguntas foram feitas para explorar mais as capacidades do agente.
    `Can you give me some information about dining options near the first location?` 
      `what three places do you recommend I stay in Paris to be within walking distance to hist[orical sites]` 

### 4. Comparativo com Microsoft Copilot

Para efeito de comparação, o mesmo prompt inicial foi utilizado no Microsoft Copilot. A resposta do Copilot foi igualmente útil, porém mais estruturada visualmente, com seções claras sobre "Weather & What to Pack" e "Events & Festivals", incluindo eventos específicos como o "European Heritage Days (Sept 13-14)".

## 💡 Aprendizados e Observações

* **Facilidade de Provisionamento:** A criação e configuração de um recurso de IA generativa no Azure é um processo rápido e intuitivo.
* **Capacidade de Contexto:** O agente no Azure AI Studio demonstrou uma excelente capacidade de manter o contexto da conversa, lembrando das perguntas anteriores para formular novas respostas.
* **Flexibilidade do Agente vs. Produto Final:** O Playground de Agentes do Azure oferece um ambiente "cru" e altamente configurável para desenvolvedores. Em contraste, o Microsoft Copilot é um produto final polido, com uma interface e formatação de resposta otimizadas para o usuário final.
* **Potencial de Integração:** A capacidade do agente de processar informações de fontes externas, como um link da Wikipedia, abre um vasto leque de possibilidades para a criação de assistentes inteligentes e informativos.

## ✅ Conclusão

Este laboratório prático permitiu uma compreensão aprofundada e aplicada dos conceitos de IA Generativa. A experiência documentada aqui demonstra a capacidade de aplicar os conhecimentos teóricos em um ambiente real, estruturando e compartilhando os resultados de forma técnica e clara. 
