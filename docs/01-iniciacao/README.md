# Iniciação

# Estrutura do Documento

- [Fase de Iniciação](#iniciação)
- [Introdução](#introdução)
  - [Problema](#problema)
  - [Objetivos](#objetivos)
  - [Justificativa](#justificativa)
  - [Critérios de Sucessos](#critérios-de-sucesso)
- [Partes Interessadas](#partes-interessadas)
  - [Identificação das Partes Interessadas](#identificação-das-partes-interessadas)
  - [Avaliação das Partes Interessadas](#avaliação-das-partes-interessadas)
- [Termo de Abertura do Projeto](#termo-de-abertura-do-projeto)
  - [Estimativa de Custo](#estimativa-de-custo)
  - [Estimativa de Prazo](#estimativa-de-prazo)
  - [Escopo Preliminar e Premissas](#escopo-preliminar-e-premissas)
    - [Requisitos Funcionais](#requisitos-funcionais)
    - [Requisitos Não Funcionais](#requisitos-não-funcionais)
    - [Restrições](#restrições)
    - [Contra-Escopo](#contra-escopo)
    - [Condições para início do Projeto](#condições-para-início-do-projeto)
  - [Marcos Agendados e Entregas](#marcos-agendados-e-entregas)
- [Metodologia](#metodologia)
  - [Divisão de Papéis](#divisão-de-papéis)
  - [Ferramentas](#ferramentas)

# Introdução

No cenário atual de alta competitividade no setor de locação de veículos, as empresas enfrentam desafios crescentes para gerenciar suas frotas de maneira eficiente e segura. A ausência de um monitoramento em tempo real pode resultar em altos custos operacionais, manutenção reativa em vez de preditiva, dificuldades na prevenção de fraudes e ineficiências logísticas. Estes fatores comprometem não apenas a rentabilidade, mas também a capacidade de resposta às demandas do mercado e a satisfação dos clientes.

Em resposta a esses desafios, o presente trabalho propõe o desenvolvimento do "Sistema de Monitoramento Avançado para Frotas de Locadoras de Carros" (SMA). Este projeto visa integrar tecnologias de ponta, como sensores avançados, módulos GPS e câmeras digitais, à plataforma Xilinx Zynq-7000 SoC, para criar uma solução robusta que permita o monitoramento contínuo e em tempo real dos veículos. Com isso, espera-se proporcionar uma gestão mais eficaz da frota, reduzir custos operacionais, aumentar a segurança dos veículos e, consequentemente, melhorar a competitividade das locadoras no mercado.

## Problema

As locadoras de veículos, como a Localiza, enfrentam diversos desafios significativos na gestão eficaz de suas frotas. Um dos principais problemas é a falta de monitoramento em tempo real, que resulta em uma série de dificuldades operacionais e financeiras.

Primeiramente, a ausência de monitoramento contínuo dos veículos leva a altos custos operacionais. Sem informações atualizadas sobre o estado dos veículos, as manutenções são frequentemente realizadas de forma reativa, após a ocorrência de falhas, em vez de preventivamente. Isso não só aumenta os custos com reparos, mas também expõe os veículos a riscos maiores, como a operação com problemas não detectados, tais como baixa pressão dos pneus ou desgaste excessivo do motor, que podem elevar o consumo de combustível e causar um uso ineficiente dos recursos.

Além disso, a falta de dados em tempo real impede a realização de manutenções preventivas eficazes, o que pode resultar em falhas mecânicas inesperadas. Essas falhas aumentam os custos com reparos de emergência e reduzem a disponibilidade dos veículos para aluguel, impactando negativamente a receita da locadora.

Outro problema significativo é a dificuldade na prevenção de fraudes. Sem monitoramento preciso, as locadoras enfrentam desafios no controle do consumo de combustível e no uso indevido dos veículos. Fraudes, como o abastecimento irregular ou o uso não autorizado dos carros, tornam-se difíceis de detectar, resultando em prejuízos financeiros.

Por fim, a falta de dados sobre a localização e o status dos veículos em tempo real compromete a otimização da logística e da utilização da frota. Isso leva a uma distribuição ineficiente dos veículos, aumentando o tempo de ociosidade e reduzindo a capacidade de resposta da empresa às demandas dos clientes. Esses problemas, combinados, resultam em uma gestão ineficaz da frota, comprometendo a competitividade e a lucratividade das locadoras de veículos.


## Objetivos

O objetivo é melhorar a gestão da frota, monitorando em tempo real diversos aspectos do veículo, como temperatura, umidade, nível de combustível, pressão dos pneus e a condição do motor. 

## Objetivos específicos

1. Desenvolver uma plataforma integrada de monitoramento em tempo real
Criar e implementar um sistema que permita o monitoramento contínuo de aspectos críticos dos veículos da frota, como temperatura do motor, umidade interna, nível de combustível, pressão dos pneus e localização via GPS, até 10/11/2024.

2. Reduzir os custos operacionais em pelo menos 15% em um período de seis meses
Implementar práticas de manutenção preditiva e otimização do uso de combustível e pneus, utilizando os dados coletados pelo sistema, com o objetivo de reduzir os custos operacionais das locadoras em 15% até 10/05/2025.

3. Melhorar a segurança dos veículos e reduzir incidentes em 10%
Introduzir funcionalidades de detecção de impactos e monitoramento visual que permitam a rápida identificação e resposta a incidentes, visando reduzir em 10% o número de incidentes relacionados à frota até 10/05/2025.

4. Implementar um sistema de prevenção de fraudes
Desenvolver um módulo que analise o consumo de combustível e o uso dos veículos para detectar padrões irregulares, com o objetivo de reduzir as fraudes associadas ao abastecimento e uso não autorizado em 20% até 10/12/2024.

5. Otimizar a logística e a utilização da frota
Criar uma interface centralizada que permita a visualização e análise em tempo real da localização e estado dos veículos, melhorando a eficiência logística e reduzindo o tempo de ociosidade da frota em 25% até 07/10/2024.

6. Realizar testes e validações do sistema em um ambiente controlado
Concluir a fase de testes e validações, garantindo que todos os componentes do sistema (sensores, câmeras, módulos GPS) estejam funcionando corretamente e integrados à plataforma, até [data 15/10/2024.

7. Treinar a equipe de TI e de manutenção da Localiza
Desenvolver e ministrar um programa de treinamento para capacitar os funcionários da Localiza na utilização e manutenção do sistema, assegurando a autonomia da equipe para lidar com a tecnologia implementada, até 22/10/2024.

8. Entregar a solução final dentro do prazo e orçamento estabelecidos
Garantir que o sistema completo seja entregue à Localiza, cumprindo todos os requisitos técnicos e funcionais, dentro do prazo de 2000 horas e orçamento de R$ 972.704, conforme o cronograma estabelecido.

## Justificativa

* O SMA tem como objetivo minimizar a dificuldade da gestão de frotas, sendo eles, os altos custos operacionais, a falta de segurança e a necessidade de manutenção eficiente.

* A redução dos custos operacionais, sendo a manutenção e otimização de recursos.

* Aumento da Segurança: Alertas em tempo real com a localidade em situações de risco.

* Melhoria na Gestão da Frota: Controle preciso da localização e estado dos veículos com atualização em tempo real.

* Sustentabilidade: Redução de emissões através do monitoramento eficiente.

* Diminuição de Custos com Seguros: Controle rigoroso sobre a segurança e a manutenção dos veículos.

* Impacto Previsto: O projeto visa melhorar a segurança e sustentabilidade, agilidade.

* Beneficiará a locadora e seus clientes, podendo servir de exemplo pro setor.

## Critérios de Sucesso

**Critérios de Sucesso para o Sistema de Monitoramento Avançado para Frotas de Locadoras de Carros**

1. **Entrega Dentro do Prazo e Orçamento Estipulados**: Um critério fundamental de sucesso será a capacidade de entregar o sistema completo dentro do prazo definido no cronograma e sem exceder o orçamento previsto. O cumprimento dessas metas demonstra a eficiência na gestão do projeto.

2. **Satisfação do Cliente**: O projeto será considerado bem-sucedido se atender ou superar as expectativas da locadora de carros, como a Localiza. Isso inclui a facilidade de uso do sistema, a precisão das informações coletadas e a capacidade do sistema em contribuir para a redução de custos operacionais e aumento da segurança da frota.
 
3. **Qualidade do Produto Final**: A qualidade do sistema será medida pela confiabilidade e precisão dos dados coletados pelos sensores integrados.

5. **Atendimento aos Requisitos e Expectativas das Partes Interessadas**: O sucesso do projeto também será determinado pela capacidade de atender a todos os requisitos técnicos e funcionais estabelecidos no início do projeto. Além disso, a colaboração com as partes interessadas, como engenheiros de software, técnicos de manutenção, gerentes de frota e outros envolvidos, será crucial para garantir que o sistema atenda às necessidades e expectativas de todos.

6. **Gestão Eficaz de Riscos**: A habilidade da equipe em identificar, mitigar e resolver possíveis riscos durante o desenvolvimento do sistema será outro indicador importante de sucesso. A prevenção de atrasos, a minimização de falhas técnicas e a resolução rápida de problemas emergentes contribuirão para o sucesso global do projeto.

# Partes Interessadas

## Identificação das Partes Interessadas

| Nome            | Posição / Cargo | Papel Projeto | E-mail      | Telefone    |
|-----------------|-----------------|---------------|-------------|-------------|
| Pessoa Localiza 1 | Gerente Operações | Validar entregas |      x       |      x     |
| Pessoa Localiza 2 | Engenheiro Mecânico |  Instalar hardware carros |     x     |      x     |
| Pessoa TI Localiza |  TI |  Instalar software |     x     |      x     |
|   Investidor  |   Acionista   |  Suporte financeiro |      x       |      x       |
|  Pessoa loja hardware  | fornecedora/consultora  |   Fornecer sensores e hardware |      x     |     x   |
|   Fernanda  |  Engenheira de Hardware   |   Comprar sensores e CI, projetar hardware e programar, testar funcionalidades  |       x      |       x      |
|   Lucas     |  Engenheiro de software  |  desenvolver Backend  |      x       |       x      |
|   Samira    |  Engenheiro de software |  desenvolver Front end |     x        |       x      |
|   Julia     |  Engenheiro de Dados  |      desenvolver banco de dados, configurar comunicação entre dispositivos embarcados e servidor  |   x   |x|


## Avaliação das Partes Interessadas

| Nome            | Expectativa no Projeto | Influência    | Importância / Poder | Apoio       | Observações   |
|-----------------|------------------------|---------------|---------------------|-------------|---------------|
|  Investidor  | Aumento no retorno de lucros e na cartela de clientes |  Média  | alta | Positivo  | o valor do investimento pode ser incrementado de acordo com percurso do projeto e os resultados demonstrados  |
| Pessoa loja hardware|Manter o fluxo do fornecimento dos componentes|baixa|alta|neutro|os produtos serão entregues em quantidade estabelecida previamente|
| Pessoa Localiza 2 |ajudar na instalação dos sensores nos veículos|Média|Média|positivo|pode ajudar também na manutenção do hardware|
|Samira|desenvolver a interface do usuario com qualidade e fluidez, com ferramentas intuitivas e fáceis de serem manipuladas |Média|alta|positivo| parte das tarefas depende da finalização da etapa de desenvolvimento do software backend|
|Fernanda|desenvolver sistema de hardware completo e que atende os requisitos|alta|Média|positivo|               |
|Pessoa Localiza 1|Aprovar produto final e ter um sistema de monitoramento completo e atual|Alta|Alta|Neutro|               |
|    Lucas        | Desenvolver e manter o backend do sistema com alta performance e segurança. |    Média    |    Alta                 |    Positivo         |         Crucial para a integração eficiente com o frontend e garantindo o desempenho e a segurança do sistema.       |
|Julia|desenvolver e manter pipelines de dados, banco de dados, projetar arquitetura de dados e garantir a segurança dos dados|Alta|Alta|Positivo|               |

```diff
+ Tarefa 01
+ Fim da seção a ser atualizada.
```


-----
```diff
+ Tarefa 02
+ Termo de Abertura do Projeto
```

# Termo de Abertura do Projeto

## Estimativa de Custo

| Item de Custo           | Descrição | Qtd. horas | Valor / hora | Valor total |
|-------------------------|-----------|------------|--------------|-------------|
| Recursos Humanos        |Quatro desenvolvedores|2000|120,00|960.000|
| Hardware                |sensores de monitoramento e placa de desenvolvimento|-|-|1874 por carro|
| Serviços de Rede        |Internet|2000|0,15|305,56|
| Hospedagem e Nuvem      |Hospedagem da Localiza, Nuvem da AWS|2000|1,65|3300|
| Software de terceiros   |Linux, Visual Code|-|0|0|
| Serviços e treinamento  |Treinamento para capacitar os funcionários da Localiza em manutenção e instalação dos equipamentos|60|120|7200|
| **Total Geral**         |           |            |              |972679,56|


## Estimativa de Prazo

* Prazo previsto (em horas): 8000 horas
* Data de início: 01 / 09 / 2024
* Data de término: 30 / 09 / 2025

## Escopo Preliminar e Premissas

O projeto visa desenvolver um sistema de monitoramento para frotas de veículos, como os da Localiza, com o objetivo de melhorar a gestão por meio do monitoramento em tempo real. Isso permitirá a manutenção preditiva, redução de custos operacionais e aumento da segurança.

As funcionalidades incluem o monitoramento da temperatura do motor para evitar superaquecimento, controle da umidade interna para prevenir corrosão, detecção de impactos para identificar colisões e avaliar danos, e monitoramento da combustão para reduzir emissões. Além disso, o sistema controlará o consumo de combustível, monitorará a pressão dos pneus, rastreará a localização dos veículos em tempo real e oferecerá monitoramento visual por câmeras.

O desenvolvimento será feito na plataforma Xilinx Zynq 7000 SoC, integrando os sensores e processando os dados em tempo real. Com isso, o sistema poderá sugerir manutenções preventivas e centralizar as informações em uma interface para facilitar a tomada de decisões, sempre visando a segurança e a eficiência.

Esse escopo preliminar pode ser ajustado conforme o desenvolvimento avança e novas necessidades surgem.

## Declaração de Escopo
  Requisitos Funcionais (RF)
 - Monitoramento de Temperatura: O sistema deve monitorar a temperatura interna do motor em tempo real para evitar superaquecimento.
 - Controle de Umidade: O sistema deve detectar e monitorar os níveis de umidade no interior do veículo para prevenir corrosão e danos aos componentes eletrônicos.
 - Detecção de Impactos: O sistema deve identificar colisões e impactos no veículo, auxiliando na avaliação de possíveis danos estruturais.
 - Monitoramento da Combustão: O sistema deve monitorar a eficiência da combustão do motor através da análise dos gases de escape, ajudando a reduzir emissões e a manter a eficiência do motor.
 - Gestão de Combustível: O sistema deve monitorar o nível de combustível em tempo real, permitindo o controle preciso do consumo e a prevenção de fraudes.
  - Monitoramento da Pressão dos Pneus: O sistema deve monitorar a pressão dos pneus e alertar sobre insuficiência de pressão para prevenir acidentes e otimizar o consumo de combustível.
  - Rastreamento de Localização: O sistema deve rastrear a localização dos veículos da frota em tempo real através de um módulo GPS.
  - Monitoramento Visual: O sistema deve integrar câmeras digitais para capturar e transmitir imagens em tempo real, reforçando a segurança dos veículos.
  
  Requisitos Não Funcionais (RNF)
  - Plataforma de Desenvolvimento: O sistema deve ser desenvolvido utilizando a plataforma Xilinx Zynq 7000 SoC para garantir a integração eficiente dos sensores e o processamento de dados em tempo real.
  - Manutenção Preditiva: O sistema deve ser capaz de sugerir intervenções de manutenção com base nos dados coletados, visando prevenir falhas e minimizar paradas não planejadas.
  - Interface Centralizada: O sistema deve centralizar todos os dados coletados em uma interface única para facilitar a análise e a tomada de decisões.
  - Segurança de Dados: O sistema deve criptografar todos os dados transmitidos e armazenados para garantir a segurança das informações.
  - Desempenho e Escalabilidade: O sistema deve ser capaz de processar grandes volumes de dados em tempo real e escalar conforme o aumento da frota.

### Requisitos Funcionais

A tabela a seguir apresenta os requisitos funcionais do projeto. 

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|-------|
|RF-001|Monitorar a temperatura interna do motor | ALTA | 
|RF-002|Detectar e monitorar os níveis de umidade no interior do veículo| ALTA |
|RF-003|Identificar colisões e impactos no veículo| ALTA |
|RF-004|Análise dos gases de escape| ALTA |
|RF-005|Monitorar o nível de combustível| ALTA |
|RF-006|Monitorar a pressão dos pneus| ALTA |
|RF-007|Rastrear a localização dos veículos| ALTA |
|RF-008|Câmeras digitais para capturar e transmitir imagens| ALTA |
|RF-009|Segurança na Transmissão de Dados|MÉDIA|
|RF-010|Armazenamento e Histórico de Dados|MÉDIA|

### Requisitos Não Funcionais

A tabela a seguir apresenta os requisitos não funcionais do projeto. 

|ID     | Descrição do Requisito                                            |Prioridade |
|-------|-------------------------------------------------------------------|-----------|
|RNF-001| O sistema deve ser responsivo para rodar em tempo real| ALTA| 
|RNF-002| O sistema deve ser desenvolvido utilizando a plataforma Xilinx Zynq 7000 SoC| BAIXA| 
|RNF-003| O sistema deve ser capaz de sugerir intervenções de manutenção com base nos dados coletados|ALTA| 
|RNF-004| O sistema deve criptografar todos os dados|ALTA| 
|RNF-005| Sistema deve ser capaz de processar grandes volumes de dados|ALTA| 
|RNF-006| O sistema deve monitorar continuamente a pressão dos pneus de cada veículo da frota.|ALTA| 
|RNF-007| O sistema deve rastrear a localização dos veículos em tempo real utilizando GPS.|ALTA| 
|RNF-008| O sistema deve integrar câmeras digitais nos veículos para capturar e transmitir imagens do interior e exterior.|ALTA| 
|RNF-009| O sistema deve garantir que todos os dados transmitidos entre os sensores, o servidor e a interface central sejam seguros e criptografados.|MÉDIA|
|RNF-010| O sistema deve armazenar dados históricos para análise posterior e geração de relatórios detalhados.|MÉDIA|


### Restrições

A tabela a seguir apresenta as restrições do projeto. 

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|-------|
|RE-001| O cliente alterar o banco de dados | ALTA | 
|RE-002| Nao funciona em carros eletricos| BAIXA |
|RE-003| Nao pode interagir com o hardware via atuadores | BAIXA |
|RE-004| Funciona somente em territorio nacional| ALTA |
|RE-005| O sistema depende de conexão à internet para funcionalidades de monitoramento em tempo real |MÉDIA|


### Contra-Escopo

A tabela a seguir apresenta as atividades que não serão executadas no projeto

|ID    | Descrição do Contra-Escopo          | 
|------|-------------------------------------|
|CE-001| Treinamento para todos funcionarios da localiza|
|CE-002| Pesquisa de viabilidade do mercado. |
|CE-003| Compra e implementacao de um dominio unico|
|CE-004| Manutencao de componentes de hardware|
|CE-005| Implementacao do hardware na frota|

### Condições para início do Projeto

A tabela a seguir, apresente as condições para que o projeto seja iniciado.

|ID    | Descrição de Condições para Início do Projeto    | 
|------|--------------------------------------------------|
|CI-001| Assinatura de contrato de prestação de serviços. |
|CI-002| Apresentação de garantias definidas no contrato. |
|CI-003| Verificação da disponibilidade para compra dos sensores na data de inicio |

## Marcos Agendados e Entregas


|ID   | Marco do Projeto                                                                 | Data de Entrega Prevista |
|-----|----------------------------------------------------------------------------------|--------------------------|
|M-1  | Conclusão da fase de iniciação e aprovação do Termo de Abertura do Projeto (TAP) | 05/09/2024               |
|M-2  | Finalização da arquitetura do sistema e especificações dos requisitos            | 12/09/2024               |
|M-3  | Aquisição e integração inicial dos sensores de monitoramento                     | 20/09/2024               |
|M-4  | Desenvolvimento do backend e integração com os sensores                          | 30/09/2024               |
|M-5  | Desenvolvimento da interface do usuário (frontend)                               | 07/10/2024               |
|M-6  | Testes de sistema e ajustes finais com a equipe da Localiza                      | 15/10/2024               |
|M-7  | Treinamento dos funcionários da Localiza para uso do sistema                     | 22/10/2024               |
|M-8  | Entrega final e homologação do sistema completo                                  | 10/11/2024               |


```diff
+ Tarefa 02
+ Fim da seção a ser atualizada.
```

-----
```diff
+ Tarefa 03:
+ Metodologia do Projeto
```

# Metodologia

### Metodologia Adotada

O grupo está utilizando uma combinação das metodologias **Scrum** e **Lean** para organizar e gerenciar o projeto de forma ágil e eficiente.

#### Scrum
O **Scrum** é um framework ágil que facilita a gestão do projeto por meio de sprints (ciclos curtos de desenvolvimento), normalmente de duas a quatro semanas. Cada membro da equipe participa de reuniões diárias rápidas (daily stand-ups) para relatar o progresso, identificar obstáculos e planejar o trabalho do dia. Ao final de cada sprint, a equipe realiza uma retrospectiva para discutir o que funcionou bem, o que pode ser melhorado e os próximos passos.

#### Lean
O **Lean**, inspirado na indústria automobilística, complementa o Scrum ao focar na eliminação de desperdícios, garantindo que cada etapa do processo agregue valor direto ao produto final. A abordagem Lean permite que a equipe foque em processos enxutos e na entrega rápida de resultados, ao mesmo tempo em que mantém a qualidade e eficiência.

### Ferramentas Empregadas
A equipe utiliza diversas ferramentas para facilitar a comunicação, organização e desenvolvimento. Entre elas estão:

- **Kanban Git:** Para gestão de tarefas e acompanhamento do progresso de sprints.
- **GitHub:** Controle de versão para colaborar no desenvolvimento de software.
- **Slack:** Para comunicação rápida e centralizada.

## Divisão de Papéis

A equipe está dividida de acordo com as especializações de cada membro, garantindo que as tarefas sejam bem distribuídas e todos os aspectos do projeto sejam cobertos.

- **Fernanda (Engenheira de Hardware):** Responsável pela compra de sensores e circuitos integrados (CIs), projeto do hardware e programação. Também testa as funcionalidades dos componentes de hardware.
  
- **Lucas (Engenheiro de Software):** Responsável pelo desenvolvimento do **backend**, implementando a lógica de negócio e a interface com o banco de dados e dispositivos embarcados.

- **Samira (Engenheira de Software):** Focada no desenvolvimento do **front-end**, criando interfaces de usuário intuitivas e eficientes que permitem interação com o sistema de forma amigável.

- **Julia (Engenheira de Dados):** Responsável pelo desenvolvimento do **banco de dados** e pela configuração da comunicação entre os dispositivos embarcados e o servidor, garantindo que os dados sejam armazenados e transmitidos corretamente.
  
## Ferramentas

| Ambiente              | Plataforma         | Link de Acesso             | Justificativa |
|-----------------------|--------------------|----------------------------|---------------|
| Quadro Kanban         | Github| https://github.com/orgs/ICEI-PUC-Minas-PMG-EC-GPS/projects/22 | Centralização e organização do projeto no próprio repositório. |
| Repositório de código | GitHub|||
| Protótipo Interativo  | Figma |||
| Documentos Textuais   |Google Docs||Documentacao de retrospectivas e processos |
| Planilhas e Gráficos  | Google Planilhas   ||Representar graficos com info dos sensores|
| Programar codigo| Visual code| | Programar codigos do projeto|
| Banco de dados |Visual code | |Desenvolver banco de dados da aws|
|| | | |

```diff
+ Tarefa 03:
+ Fim da seção a ser atualizada.
```

----
