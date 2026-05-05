## Estratégias de Engenharia de Requisitos

### Atividades e Técnicas de ER

#### Elicitação e Descoberta

**Workshop de Requisitos:**  
Essa técnica aborda o escopo, os riscos e as características do produto final, além de acelerar o processo de elicitação e descoberta de requisitos. No projeto, foi implementada por meio de encontros entre a equipe e o cliente, com o objetivo de definir elementos como casos de uso, brainstorming, entre outros aspectos importantes. O workshop é realizado no início de cada nova sprint para garantir o alinhamento e a atualização dos requisitos.

**Brainstorming:**  
Essa técnica é utilizada para estimular a geração de ideias e a discussão de possíveis soluções para o produto de software. No projeto, será aplicada por meio de reuniões colaborativas com a equipe, incentivando a livre expressão de ideias e a criatividade. O objetivo é capturar o maior número possível de sugestões, que serão posteriormente organizadas e avaliadas para integração ao escopo do projeto.

**Entrevistas com stakeholders:**  
Técnica essencial para obter um entendimento claro e direto sobre o problema, as necessidades, as possíveis soluções e as expectativas em relação ao produto de software. No projeto, serão realizadas entrevistas quinzenais com o cliente, visando a elicitação eficaz de requisitos e garantindo a definição precisa e assertiva das funcionalidades do produto. Além disso, são realizadas entrevistas fechadas, ou seja, antes de ocorrer, o Product Owner da equipe pré-define as perguntas e assuntos a serem abordados.

**Lean Inception:**  
Esse método permite alinhar a equipe na definição do MVP (Produto Mínimo Viável). Durante a sprint 1, a equipe e os stakeholders colaboraram para definir e priorizar os recursos e funcionalidades do produto. Além disso, o MVP definido é flexível, podendo ser ajustado e atualizado ao longo do desenvolvimento.

---

#### Análise e Consenso

**Análise de risco:**  
É utilizada para identificar os requisitos que podem apresentar riscos ou inviabilizar o produto ou solução, e assim obter formas de reduzir o risco. Na proposta, a análise de risco é feita em cada sprint planning.

**Negociação:**  
O fundamental é analisar os objetivos de cada parte e alcançar um acordo mutuamente satisfatório. Em situações de conflito entre o cliente e a equipe sobre a solução de software, é realizada uma negociação amistosa para definir o que será efetivamente implementado, garantindo que ambas as partes estejam alinhadas.

**MoSCoW:**  
Esse método de priorização é utilizado para classificar as tarefas em um projeto, buscando um entendimento comum sobre a importância de cada requisito. No projeto, foi aplicado da seguinte forma: primeiramente, a equipe se reuniu para analisar a lista de funcionalidades e requisitos gerais levantados pelo cliente. Em seguida, por meio de consenso e votação, foram definidas as prioridades, riscos e importâncias de cada item. Por fim, as diretrizes foram alinhadas e validadas em uma nova reunião com os stakeholders.

---

#### Declaração de Requisitos

**Épicos e User Stories:**  
A declaração de requisitos é dividida em épicos, onde há uma coletânea de features que envolvem um objetivo amplo, e histórias de usuário que descrevem as funcionalidades presentes no projeto.

**Critérios de aceitação:**  
São definidos critérios de aceitação, ou seja, é acordado junto com os stakeholders do projeto e o Product Owner o que uma User Story precisa ter para ser aceita. Isso é feito para que ambas as partes, equipe de desenvolvimento e stakeholders, tenham compreensão do que determinada funcionalidade precisa ter para ser considerada concluída.

**Debates e incorporação de feedback:**  
A equipe de desenvolvimento apresenta o que foi desenvolvido. Ao receber o feedback do cliente acerca da funcionalidade desenvolvida, a equipe faz a incorporação desse feedback à funcionalidade.

---

#### Representação de Requisitos

**Prototipagem de Alta Fidelidade:**  
A prototipação é de alta fidelidade. Os protótipos das telas do projeto serão feitos na plataforma Figma. Esses protótipos serão então validados com os stakeholders para que a funcionalidade possa ser desenvolvida corretamente e, assim, evitar retrabalho.

---

#### Verificação e Validação de Requisitos

**Critérios de aceitação:**  
Conjunto de condições que devem ser atendidas para que a funcionalidade seja considerada aceitável pelo cliente. Eles definem como será validado que a entrega atende às expectativas.

**Feedback do cliente:**  
O cliente tem total abertura para avaliar e comentar sobre o que foi entregue. Esse feedback é essencial para ajustar ou corrigir funcionalidades antes da validação completa.

**DoR e DoD:**  
Esses critérios servem como guias para a verificação:
- **DoR (Definition of Ready):** Garante que a funcionalidade esteja pronta para desenvolvimento.  
- **DoD (Definition of Done):** Confirma que a funcionalidade foi finalizada, testada e está pronta para entrega.

**Reuniões de verificação interna:**  
Antes da validação com o cliente, a equipe realiza reuniões internas para revisar os requisitos e as funcionalidades entregues, certificando-se de que todos os critérios de aceitação e o DoD foram cumpridos.

---

#### Organização e Atualização de Requisitos

**Backlog de requisitos:**  
Os requisitos são organizados e atualizados por meio de uma lista detalhada com informações como: User Stories, critérios de aceitação e prazos de execução.

**Feedbacks acerca do backlog:**  
As opiniões dos stakeholders sobre a utilidade das funcionalidades e a visão de sua aplicação dentro do MVP podem gerar atualizações no backlog.

**User Stories:**  
Todos os requisitos funcionais passam pelo método de organização de User Stories para melhor entendimento das expectativas e comportamento da funcionalidade dentro do software.

---

### Engenharia de Requisitos e o Scrum/XP

| Fase do Processo | Atividades ER | Prática | Técnica | Resultado Esperado |
|-----------------|--------------|--------|---------|-------------------|
| Planejamento de Release | Elicitação e Descoberta | Elicitação de Requisitos | Workshop Lean Inception, Brainstorming, Reuniões com o cliente | Identificação de requisitos do projeto |
| Planejamento de Release | Análise e Consenso | Priorização dos Requisitos | Priorização via Workshop Lean Inception | Definição do valor técnico e impacto na experiência do usuário |
| Planejamento de Release | Declaração | Registro dos Requisitos | Épicos e User Stories | Funcionalidades descritas |
| Planejamento de Release | Verificação e Validação | Validação dos requisitos | Workshop Lean Inception com PBB | Requisitos validados |
| Planejamento de Release | Organização e Atualização | Organização dos requisitos | Product Backlog Building (PBB) | Backlog estruturado |
| Sprint Planning | Elicitação e Descoberta | Refinamento dos Requisitos | User Stories, Entrevistas | Detalhamento dos requisitos |
| Sprint Planning | Análise e Consenso | Viabilidade | Análise de Risco | Alinhamento da entrega |
| Sprint Planning | Declaração | Critérios de aceitação | DoR e DoD | Funcionalidades bem definidas |
| Sprint Planning | Verificação e Validação | Verificação | DoR | Pronto para desenvolvimento |
| Sprint Planning | Organização e Atualização | Organização da Sprint | Backlog, User Stories | Sprint organizada |
| Execução da Sprint | Representação | Prototipação | Alta fidelidade | Redução de retrabalho |
| Execução da Sprint | Verificação e Validação | Validação | Critérios, feedback, DoD | Requisitos validados |
| Execução da Sprint | Organização e Atualização | Revisão do Backlog | Acompanhamento | Backlog atualizado |
| Sprint Review | Declaração | Atualização | Feedback do cliente | Alinhamento do produto |
| Sprint Review | Verificação e Validação | Demonstração | Reuniões, feedbacks | Funcionalidades validadas |
| Sprint Review | Organização e Atualização | Atualização do backlog | Feedback | Backlog atualizado |