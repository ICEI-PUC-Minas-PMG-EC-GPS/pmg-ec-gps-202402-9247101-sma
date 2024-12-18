# Planejamento

# Estrutura do Documento

- [Fase de Planejamento](#planejamento)
- [Escopo do Projeto](#escopo-do-projeto)
- [Estrutura Analítica do Projeto](#estrutura-analítica-do-projeto)
- [Matriz de Responsabilidades](#matriz-de-responsabilidades)
- [Cronograma do Projeto](#cronograma-do-projeto)
- [Orçamento do Projeto](#orçamento-do-projeto)
- [Planos de Gerenciamento](#planos-de-gerenciamento)
  - [Plano de Qualidade](#plano-de-qualidade)
  - [Plano de Aquisição](#plano-de-aquisição)
  - [Plano de Comunicação](#plano-de-comunicação)
  - [Plano de Riscos](#plano-de-riscos)

# Escopo do Projeto

O projeto **Sistema de Monitoramento Avançado para Frotas de Locadoras de Carros** tem como objetivo desenvolver uma solução tecnológica que permita o acompanhamento em tempo real de veículos pertencentes à frota de locadoras, como a Localiza. Esse monitoramento incluirá aspectos cruciais como temperatura, umidade, pressão dos pneus, nível de combustível e eficiência do motor. O objetivo central do sistema é proporcionar uma ferramenta que auxilie na manutenção preditiva, redução de custos operacionais, aumento da segurança e otimização do desempenho da frota. 

O escopo do projeto está limitado à integração de sensores com a plataforma Xilinx Zynq-7000 SoC, além do desenvolvimento de um software que processará os dados coletados e os disponibilizará em uma interface central para análise. O sistema também incluirá funcionalidades de rastreamento por GPS e monitoramento visual por câmeras. Contudo, o projeto não abordará aspectos relacionados à reparação física dos veículos ou questões legais, focando apenas na coleta e análise de dados. Além disso, será respeitado o limite de tempo e recursos disponíveis dentro do semestre acadêmico.

As principais premissas incluem a disponibilidade dos sensores e da infraestrutura necessária para implementação, além da capacidade da plataforma utilizada para suportar o processamento de dados em tempo real. As restrições do projeto envolvem o orçamento limitado, o prazo de execução e as limitações técnicas da plataforma. Qualquer mudança no escopo será analisada cuidadosamente para avaliar seu impacto no cronograma e nos recursos, garantindo que os ajustes necessários sejam devidamente aprovados e implementados de maneira controlada.

# Estrutura Analítica do Projeto

![estrutura drawio](https://github.com/user-attachments/assets/24ff12fe-61b8-4bfb-9ba6-c95b193babd5)

### Documento Editável

- [Estrutura Analítica do Projeto - Editável](https://drive.google.com/file/d/1yG2TLAPFsRL61zsbpPlQb86z47ZYJFpG/view?usp=sharing)

# Matriz de Responsabilidades

![Matriz RACI](images/Matriz_Raci.png)


### Documento Editável

- [Matriz de Responsabilidades (RACI) - Editável](artefatos/matriz_raci_entrega.pdf)

# Cronograma do Projeto
[Cronograma do Projeto](https://github.com/ICEI-PUC-Minas-PMG-EC-GPS/pmg-ec-gps-202402-9247101-sma/blob/master/docs/02-planejamento/artefatos/Projeto%202%20(1).mpp)

# Orçamento do Projeto

![image](https://github.com/user-attachments/assets/55162399-d05e-43a1-a417-a99e5a512e9a)
![image](https://github.com/user-attachments/assets/c015326a-a215-4372-a9f9-34cf5d48cd20)


# Planos de Gerenciamento

## Plano de Qualidade

### Objetivo do Plano de Qualidade
O objetivo do Plano de Qualidade é garantir que as entregas do projeto **Sistema de Monitoramento Avançado para Frotas de Locadoras de Carros (SMA)** atendam aos padrões definidos, assegurando confiabilidade, segurança e funcionalidade. O plano abrange monitoramento contínuo dos processos, testes rigorosos e verificações para garantir conformidade com os requisitos.

---

### Normas e Padrões Adotados
1. **ISO 26262** - Segurança funcional para sistemas automotivos.
2. **ISO 9001** - Gestão de qualidade para garantir consistência nos processos.
3. **ISO/IEC 25010** - Qualidade de software, focando em usabilidade, confiabilidade e eficiência.

---

### Processos de Garantia da Qualidade
Os processos de garantia da qualidade serão baseados em metodologias ágeis (Scrum) e testes iterativos:
- **Testes de Unidade**: Avaliar cada componente individualmente (e.g., sensores, módulos GPS).
- **Testes de Integração**: Verificar a comunicação entre sensores e plataforma.
- **Testes Funcionais**: Avaliar se os requisitos definidos (e.g., monitoramento de temperatura) estão sendo atendidos.
- **Testes de Usabilidade**: Garantir que a interface do usuário seja intuitiva e funcional.

---

### Responsabilidades da Qualidade

| Nome       | Cargo                  | Responsabilidade                                   |
|------------|------------------------|---------------------------------------------------|
| Lucas      | Engenheiro de Software | Garantir a funcionalidade e integração do backend|
| Julia      | Engenheira de Dados    | Garantir a segurança e integridade dos dados     |
| Samira     | Engenheira de Software | Garantir a usabilidade e qualidade do frontend   |
| Fernanda   | Engenheira de Hardware | Testar e validar os sensores e integração física |

---

### Critérios de Aceitação
1. **Conformidade**: Todas as funcionalidades devem estar alinhadas aos requisitos funcionais e não funcionais definidos.
2. **Eficiência**: O sistema deve processar os dados em tempo real com um mínimo de 95% de precisão.
3. **Usabilidade**: O sistema deve atingir um índice de satisfação superior a 90% em testes de usuário.
4. **Segurança**: Os dados devem ser criptografados, e qualquer falha de segurança deve ser corrigida antes da entrega.

---

### Métricas de Qualidade

| Métrica                     | Descrição                              | Meta Alvo         |
|-----------------------------|----------------------------------------|-------------------|
| Taxa de Defeitos            | Número médio de defeitos detectados    | Máximo de 3/mês   |
| Cobertura de Código         | Percentual de código coberto por testes| Mínimo de 85%     |
| Taxa de Aprovação           | Entregas aprovadas na primeira avaliação| Mínimo de 95%     |
| Satisfação do Cliente       | Avaliação dos stakeholders             | Superior a 90%    |

---

### Cronograma de Qualidade

| Atividade                   | Frequência      | Responsável             |
|-----------------------------|-----------------|-------------------------|
| Revisões de Código          | Semanal         | Lucas                   |
| Auditorias de Qualidade     | Mensal          | Gerente de Qualidade    |
| Testes Funcionais           | Conforme Sprint | Equipe de Desenvolvimento |
| Feedback de Usuários        | Após Testes     | Gerente de Projeto      |

---

### Riscos de Qualidade

| Risco                      | Impacto       | Mitigação                                      |
|----------------------------|---------------|-----------------------------------------------|
| Inconsistências nos Dados  | Alto          | Revisão frequente e validação dos sensores    |
| Falhas na Integração       | Médio         | Realização de testes integrados contínuos     |
| Atrasos na Correção        | Alto          | Priorização de bugs críticos na sprint atual  |

---

### Ferramentas de Qualidade
1. **SonarQube**: Para análise de código.
2. **Selenium**: Para testes de automação.
3. **Jira**: Para rastreamento de tarefas e bugs.

---

Esse Plano de Qualidade será revisado periodicamente, garantindo que as práticas e métricas sejam ajustadas conforme o progresso do projeto e o feedback recebido.


### Artefatos a serem verificados

| Artefato   | Tipo Verif. | Data        | Responsável | Métrica     | Data Correção | Ação Não Conform. | Resp. Avaliação | Resp. Correção |
|------------|-------------|-------------|-------------|-------------|---------------|-------------------|-----------------|----------------|
|  Codigo-fonte do software          | Revisão de Código     |   10/09/2024          |   Lucas         |   Conformidade com padrões de codificação          |  25/09/2024             |   Corrigir o código e realizar nova revisão          |  Julia                |   Samira             |
|  Relatórios de monitoramento          |  inspeção           |  05/11/2024           |  Julia           |  Precisão dos dados gerados            |  20/11/2024           |  Análise e ajuste de incosistências          |   Samira              |  Lucas              |
|  Sistema de sensores           |   Teste funcional          |    15/01/2025         |   Samira          |  Funcionamento conforme especificações           |  30/01/2025             |   Substituição ou ajuste dos sensores          |  Lucas                |    Julia            |
|   Interface de usuário         |    Teste de usabilidade          |    15/06/2025         |   Lucas          |   Satisfação do usuário          |   30/06/2025            |     Ajustes conforme feedback do usuário              |     Julia            |    Samira            |


### Padrões e Normas Utilizadas

| Nome       | Descrição   | 
|------------|-------------|
| ISSO 26262 | Segurança funcional para sistemas eletrônicos automotivos            |
| ISSO 9001  | Sistema de gestão da qualidade para garantir a consistência e eficiência            |
| CAN (Controller Area Network)           |  Padrão de comunicação para integração dos sensores         |

### Ambiente das Atividades de Qualidade

| Ambiente   | Descrição   | 
|------------|-------------|
|Planejamento|Definição de requisitos e especificações do sistema de monitoramento, incluindo escolha dos sensores e módulos (temperatura, umidade, batidas, oxigênio, combustível, TPMS, GPS e câmeras digitais) e compatibilidade com a plataforma Xilinx Zynq-7000 SoC.|
|Desenvolvimento| Integração dos sensores com a plataforma SoC, desenvolvimento de software para coleta e processamento de dados, e criação de interface central para visualização e análise das informações dos veículos.            |
|Testes e Validação|   Testes de funcionamento dos sensores e do sistema completo, verificando a precisão e confiabilidade dos dados coletados (como níveis de pressão, temperatura, umidade) e resposta adequada aos eventos monitorados (por exemplo, impactos e alertas de baixa pressão nos pneus).          |
|Monitoramento e Manutenção|  Verificação constante do desempenho do sistema em veículos da frota, garantindo que os dados estejam sendo enviados corretamente e que não haja falhas nos sensores ou no software.           |
|Melhoria Contínua|  Avaliação dos dados e feedback da implementação para aprimorar o sistema, incluindo possíveis ajustes em sensores, parâmetros de análise e algoritmos de predição para melhorar a eficiência e segurança da frota.           |

### Equipe de Qualidade

| Nome       | Responsabilidade | 
|------------|------------------|
|   Lucas         |    Verificação de qualidade dos sensores e coleta de dados              |
|    Julia        |    Inspeção de funcionalidade e revisão de código              |
|    Samira        |    Avaliação de relatórios de desempenho e feedback de usabilidade              |


### Processos (Metodologias) de Qualidade Utilizadas

| Nome       | Descrição   | 
|------------|-------------|
| Teste de Unidade            |  Testes realizados em componentes individuais do sistema, como cada sensor.           |
|  Teste Integrado           |  Verificação da comunicação entre sensores e plataforma central.        |
| Revisão de Código           |  Avaliação das praticas de desenvolvimento para garantir qualidade e padronização.           |
| Análise de Dados           |   Verificação dos dados colectados e análise de precisão e consistência.          |

## Plano de Aquisição


O Plano de Aquisição para o projeto de Sistema de Monitoramento Avançado para Frotas de Locadoras de Carros abrange a obtenção de bens e serviços essenciais, como sensores variados, módulos GPS, câmeras digitais e a plataforma de desenvolvimento Xilinx Zynq-7000 SoC. Inicia-se pela identificação das necessidades específicas, seguida pela seleção de fornecedores confiáveis que garantam qualidade e compatibilidade com o sistema. Em seguida, são elaborados contratos que detalham prazos, condições de pagamento, garantias e cláusulas de SLA para suporte e manutenção. A gestão do relacionamento com fornecedores é fundamental para acompanhar as entregas e resolver eventuais problemas. Além disso, são implementadas estratégias de gestão de riscos para mitigar atrasos e falhas nos componentes, e assegurar a conformidade dos produtos com os padrões de qualidade, realizando testes para validar o funcionamento adequado. Esse plano visa garantir uma aquisição eficiente e transparente, reduzindo riscos e custos, e assegurando conformidade com prazos e padrões de qualidade.

[Sensor de proximidade](https://github.com/ICEI-PUC-Minas-PMG-EC-GPS/pmg-ec-gps-202402-9247101-sma/blob/master/docs/02-planejamento/artefatos/Aquisicao_produtos.docx%20(1).pdf)
# Plano de Comunicação

O Plano de Comunicação estabelece estratégias e diretrizes para facilitar a troca de informações entre os membros da equipe e as partes interessadas. Este plano abrange:

- **Meios de comunicação**: Definição das ferramentas e canais utilizados.
- **Frequência das atualizações**: Determinação da periodicidade para compartilhar informações.
- **Canais de distribuição de informações**: Identificação de quem recebe, consulta ou aprova cada tipo de informação.
- **Responsáveis pela comunicação**: Designação de papéis e responsabilidades no fluxo de informações.

Uma comunicação eficiente previne mal-entendidos e conflitos, fortalecendo o engajamento da equipe e o apoio das partes interessadas.

> Referência: [Plano de Gerenciamento de Comunicação - Editável](artefatos/plano_comunicacao.docx)

---

## Plano de Comunicação do Projeto

| **Entregável**                   | **Público Alvo**             | **Método de Comunicação**     | **Frequência**    | **Responsável**      |
|----------------------------------|-----------------------------|-------------------------------|-------------------|----------------------|
| Ata de reunião                   | Equipe do projeto           | Reunião presencial/virtual    | Semanal           | Gerente de projeto   |
| Declaração de escopo             | Equipe do projeto, cliente  | E-mail                        | Inicial           | Gerente de projeto   |
| WBS                              | Equipe do projeto           | Reunião virtual               | Inicial           | Gerente de projeto   |
| Dicionário da WBS                | Equipe do projeto           | Documento compartilhado       | Inicial           | Gerente de projeto   |
| Cronograma                       | Equipe do projeto, cliente  | Reunião virtual, e-mail       | Mensal            | Gerente de projeto   |
| Lista de Riscos                  | Equipe do projeto           | Reunião virtual               | Semanal           | Gerente de riscos    |
| Plano de qualidade               | Equipe do projeto, cliente  | Documento compartilhado       | Inicial           | Gerente de qualidade |
| Plano de projeto                 | Equipe do projeto, cliente  | E-mail, documento compartilhado | Inicial         | Gerente de projeto   |
| Relatório de Progresso           | Equipe do projeto, cliente  | Reunião virtual, e-mail       | Quinzenal         | Gerente de projeto   |
| Relatório de Aderência ao Processo| Equipe de qualidade         | Documento compartilhado       | Mensal            | Gerente de qualidade |
| Checklists de Inspeção           | Equipe de qualidade         | Documento compartilhado       | Conforme necessário| Gerente de qualidade |

---

## Gerência de Comunicação

### **Objetivo**
Garantir que informações cruciais sejam transmitidas de maneira clara, eficiente e no tempo adequado para todos os envolvidos no projeto. 

### **Ferramentas Utilizadas**
1. **Microsoft Teams**: Para reuniões virtuais, chats e videoconferências.
2. **Trello**: Para gestão de tarefas e acompanhamento do progresso do projeto.
3. **Microsoft SharePoint**: Para armazenamento centralizado e controle de versões de documentos.
4. **E-mail (Outlook)**: Para comunicações formais e envio de atualizações importantes.

---

### **Papéis na Comunicação**
- **Gerente de Projeto**: Supervisiona toda a comunicação, garantindo a disseminação das informações relevantes.
- **Gerente de Riscos**: Comunica riscos identificados, planos de mitigação e mudanças no status.
- **Gerente de Qualidade**: Fornece atualizações sobre padrões de qualidade, revisões e relatórios.
- **Equipe Técnica**: Atualiza sobre o progresso técnico e participa de discussões e revisões.

---

### **Princípios Gerais**
1. **Clareza e Objetividade**: Mensagens devem ser diretas e compreensíveis.
2. **Transparência**: Compartilhar informações relevantes de forma honesta e imparcial.
3. **Cordialidade e Profissionalismo**: Garantir um ambiente colaborativo e respeitoso.
4. **Pontualidade**: Cumprir prazos para troca de informações, facilitando decisões baseadas em dados atualizados.

---

## Plano de Gerência de Configuração

A gerência de configuração do projeto será centralizada no **SharePoint** e no **Trello**:

- **SharePoint**: Repositório principal para documentos, relatórios e atas, com controle de versões.
- **Trello**: Usado para rastreamento do progresso das atividades e tarefas, garantindo atualizações em tempo real.

Essas ferramentas permitem maior transparência no controle de entregas e documentação.

---
```diff
+ Tarefa 12:
+ Riscos do Projeto
```

## Plano de Riscos

O plano de riscos busca antecipar, avaliar e mitigar os desafios potenciais que podem surgir ao longo do projeto. Este documento estratégico oferece uma visão global dos riscos, categorizando-os e delineando estratégias para lidar com cada uma das possíveis adversidades. Inicialmente, é realizada a identificação detalhada dos riscos, abrangendo desde ameaças inesperadas até oportunidades que podem ser exploradas. 

Uma vez catalogados, os riscos são avaliados quanto à sua probabilidade de ocorrência e impacto, permitindo priorização e foco em áreas críticas. O plano de riscos não apenas destaca os perigos em potencial, mas também estabelece respostas e estratégias de contingência. Isso inclui a definição de ações preventivas para mitigar riscos antes que se materializem, bem como estratégias de mitigação para minimizar seu impacto caso ocorram. 

Além disso, a identificação de pontos de monitoramento contínuo ao longo do projeto permite uma resposta ágil às mudanças nas condições do ambiente



| **Categoria do Risco** | **Descrição do Risco**                                | **Probabilidade** | **Impacto** | **Risco** | **Medidas de Prevenção (Contramedidas)**                          | **Medidas de Contingência (Mitigação)**                          |
|-------------------------|-------------------------------------------------------|-------------------|-------------|-----------|------------------------------------------------------------------|-----------------------------------------------------------------|
| Cliente                | Falta de envolvimento do cliente no desenvolvimento.  | Médio             | Médio       | Médio     | Realizar reuniões regulares e obter feedback em cada etapa.     | Ajustar cronograma e priorizar entregas mínimas viáveis.        |
| Cronograma             | Atraso na entrega de componentes essenciais.          | Alto              | Alto        | Alto      | Identificar fornecedores confiáveis e planejar prazos de backup.| Negociar prazos adicionais e redistribuir tarefas críticas.      |
| Orçamento              | Superação do orçamento inicial estimado.              | Médio             | Alto        | Alto      | Revisar orçamento periodicamente e monitorar gastos detalhados. | Buscar fontes adicionais de financiamento ou reduzir escopo.    |
| Aquisição de Produtos  | Atraso na chegada de sensores e componentes críticos. | Alto              | Médio       | Alto      | Contatar fornecedores com antecedência e prever estoque extra.  | Identificar fornecedores alternativos e redefinir entregas.      |
| Tecnologia             | Falha na integração dos sensores ao sistema.          | Baixo             | Alto        | Médio     | Realizar testes unitários durante a integração.                 | Revisar arquitetura do sistema e reforçar suporte técnico.      |
| Equipe                 | Perda de um membro essencial do time.                 | Médio             | Alto        | Alto      | Criar documentação detalhada e compartilhar conhecimento.       | Reorganizar funções e contratar substituto rapidamente.         |


**Legenda**:

- **Categoria do Risco**: ex.: Cliente, Cronograma, Orçamento, Aquisição de produtos, etc.
- **Descrição do Risco**: ex.: O cliente não aparece interessado no projeto.
- **Impacto**: Baixo / Médio / Alto
- **Risco**: Baixo / Médio / Alto
- **Medidas de Prevenção (Contramedidas)**: Medidas que devem ser adotadas para evitar que o risco se concretize.
- **Medidas de Contingência (Mitigação)**: Medidas que devem ser adotadas caso o risco se concretize.

###Análise Qualitativa dos Riscos
Os riscos foram avaliados quanto à probabilidade de ocorrência e impacto em uma escala qualitativa (Baixo, Médio, Alto). Para priorização, foi utilizada a Matriz de Probabilidade x Impacto:

| Probabilidade | Impacto       | Risco         |
|---------------|---------------|---------------|
| Baixo         | Baixo         | Baixo         |
| Médio         | Médio         | Médio         |
| Alto          | Alto          | Alto          |
| Baixo         | Médio         | Médio         |
| Médio         | Baixo         | Médio         |
| Baixo         | Alto          | Médio         |
| Alto          | Baixo         | Médio         |
| Médio         | Alto          | Alto          |
| Alto          | Médio         | Alto          |

### Análise Quantitativa dos Riscos
Para riscos críticos, foram aplicadas as seguintes técnicas:
1. **Simulação Monte Carlo**: Estimativa de atrasos e impacto financeiro devido à falta de componentes.
2. **Árvores de Decisão**: Avaliação de custos para mitigação versus aceitação do risco.

---

### Estratégias de Resposta aos Riscos

#### Técnicas de Resposta
- **Evitar**: Eliminar a causa do risco ajustando o escopo ou cronograma.
- **Mitigar**: Reduzir a probabilidade ou impacto (ex.: testes iterativos, validação contínua).
- **Transferir**: Delegar o risco a terceiros (ex.: contratos com cláusulas de SLA).
- **Aceitar**: Planejar ações reativas caso o risco se materialize.

---

### Monitoramento e Controle dos Riscos
O monitoramento será realizado durante as reuniões quinzenais, com revisões contínuas do **Registro de Riscos**. Indicadores de desempenho serão utilizados para medir a eficácia das respostas aos riscos:

| **Indicador**               | **Descrição**                                                | **Meta**           |
|-----------------------------|------------------------------------------------------------|--------------------|
| Número de riscos ativos     | Quantidade de riscos não resolvidos                         | < 5               |
| Desvios no orçamento        | Impacto financeiro dos riscos ocorridos                    | < 10% do orçamento|
| Desvios no cronograma       | Dias de atraso devido a riscos materializados              | < 5% do prazo     |
| Eficiência das respostas    | Percentual de ações preventivas que evitaram materialização| > 90%             |

---

### Registro de Riscos

#### Exemplo de Registro de Riscos

| **ID** | **Risco**                              | **Probabilidade** | **Impacto** | **Nível de Risco** | **Ação Preventiva**             | **Responsável** |
|--------|----------------------------------------|-------------------|-------------|--------------------|---------------------------------|------------------|
| R001   | Atraso na entrega de sensores          | Alto              | Médio       | Alto               | Contratar fornecedores alternativos| Gerente de Aquisições|
| R002   | Falha na integração dos sensores       | Baixo             | Alto        | Médio              | Realizar testes de unidade       | Engenheiro de Software|
| R003   | Perda de membro essencial da equipe    | Médio             | Alto        | Alto               | Compartilhar conhecimento         | Gerente de Projeto|

---

### Ferramentas Utilizadas
1. **Microsoft Teams**: Para coordenação e comunicação de riscos.
2. **Excel/Google Sheets**: Para manutenção do registro de riscos.
3. **Jira/Trello**: Para acompanhamento de ações relacionadas aos riscos.

-----






