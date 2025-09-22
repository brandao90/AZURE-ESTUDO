# AZURE-ESTUDO
AZURE SPEECH STUDIO  E LANGUAGEM STUDIO:

### **Resumo do Desafio: Análise de Sentimentos com Language Studio**

Após assistir a todas as aulas e fazer os questionários, iniciei este projeto prático focado em análise de sentimentos e reconhecimento de linguagem natural usando o **Language Studio** e o **Speech Studio** no Azure AI. O objetivo principal foi aplicar o conhecimento teórico para extrair insights de textos e áudios, simulando um cenário real de análise de dados de clientes.

A experiência me permitiu entender como integrar essas ferramentas para automatizar a análise de feedback. Usei o **Azure Language Studio** para identificar se as opiniões eram positivas, negativas ou neutras, e o **Azure Speech Studio** para converter áudios em texto, que é o primeiro passo para a análise. Isso me mostrou o quão poderoso é o ecossistema do Azure para tarefas de IA.

Embora eu ainda esteja no início, consegui compreender a lógica por trás do fluxo de trabalho e como as diferentes ferramentas se conectam. Aprendi que um bom resultado depende não apenas da ferramenta, mas também da organização dos dados e da definição clara dos objetivos.

---

### **Passo a Passo do Projeto**

Aqui está um guia de como o projeto foi executado e as principais etapas para quem quiser seguir.

#### **1. Configuração do Ambiente**

* **Criação do Recurso no Azure:** Primeiro, criei um recurso de Language Service na minha conta do Azure. Isso é o que dá acesso às ferramentas que seriam usadas.
* **Acesso ao Language Studio:** Em seguida, acessei o Language Studio pelo portal do Azure, que é o ambiente visual para testar e usar as funcionalidades sem precisar de código.

#### **2. Análise de Texto (Language Studio)**

* **Identificação de Sentimentos:** Para a parte da análise de sentimentos, usei a funcionalidade do Language Studio para processar algumas frases de exemplo.
* **Teste Prático:** Insira textos como "Adorei a experiência!" e "O produto demorou muito para chegar." O resultado mostrou a pontuação de sentimento (positivo, negativo ou neutro) para cada um. Aprendi que a IA é bastante precisa, mas que o contexto é fundamental.
* **Extração de Entidades:** Aproveitei a oportunidade para explorar a extração de entidades. Usei textos sobre locais e datas para ver como a ferramenta identifica e classifica essas informações. Isso me mostrou o potencial para criar chatbots que entendem o que o usuário está buscando.

#### **3. Análise de Áudio (Speech Studio)**

* **Transcrição de Fala:** Para entender como seria a análise de voz, utilizei o **Speech Studio** para transcrever um pequeno áudio em português.
* **Conexão com Análise de Sentimentos:** A etapa de transcrição é o ponto de entrada para a análise de sentimentos em áudios. O texto gerado pode ser enviado para o Language Studio, completando o ciclo da análise. Foi impressionante ver a precisão da transcrição e a rapidez do processo.

---

### **Conclusão e Próximos Passos**

Concluir este desafio me deu uma base sólida em como a IA pode ser usada para entender a linguagem humana. O projeto reforçou a importância de documentar o processo, pois isso me ajudará a revisar e aprimorar minhas habilidades no futuro. Pretendo continuar explorando as outras funcionalidades do Language Studio e experimentar a integração com diferentes linguagens de programação.
