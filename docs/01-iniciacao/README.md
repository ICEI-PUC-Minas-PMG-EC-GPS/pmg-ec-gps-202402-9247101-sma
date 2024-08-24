# Iniciação

> A fase de iniciação, em gerência de projetos, é o estágio que estabelece as bases para o sucesso do empreendimento. 
> Durante essa etapa, os objetivos definidos, identificando-se suas metas, escopo, partes interessadas (*stakeholders*) e restrições. 
> É o momento em que a viabilidade do projeto é avaliada, analisando-se recursos necessários, riscos potenciais e benefícios esperados.
> Nesta etapa é elaborado o Termo de Abertura do Projeto (TAP).
> Essa fase serve como um alicerce estratégico, proporcionando uma compreensão abrangente do que o projeto busca alcançar e delineando as diretrizes que orientarão as etapas subsequentes. 
> O sucesso na fase de iniciação contribui significativamente para a eficácia do gerenciamento de projetos como um todo.

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

```diff
+ Tarefa 01:
+ Tema do projeto e lista de Stakeholders
```

## Problema

O projeto busca resolver a necessidade de melhorar a gestão de frotas em locadoras de veículos, como a Localiza, por meio de um sistema de monitoramento avançado. A ausência de monitoramento em tempo real dos veículos resulta em altos custos operacionais, manutenções imprevistas e maior risco de acidentes. 


## Objetivos

O objetivo é melhorar a gestão da frota, monitorando em tempo real diversos aspectos do veículo, como temperatura, umidade, nível de combustível, pressão dos pneus e a condição do motor. 

## Justificativa

* O SMA tem como objetivo minimizar a dificuldade da gestão de frotas, sendo eles, os altos custos operacionais, a falta de segurança e a necessidade de manutenção eficiente.

* Os benefícios esperados seriam:

* A redução dos custos operacionais, sendo a manutenção e otimização de recursos.

* Aumento da Segurança: Alertas em tempo real com a localidade em situações de risco.

* Melhoria na Gestão da Frota: Controle preciso da localização e estado dos veículos com atualização em tempo real.

* Sustentabilidade: Redução de emissões através do monitoramento eficiente.

* Diminuição de Custos com Seguros: Controle rigoroso sobre a segurança e a manutenção dos veículos.

* Impacto Previsto:
O projeto visa melhorar a segurança e sustentabilidade, agilidade.

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

> Opções de avaliação:
> - Expectativa: descrição da expectativa da parte interessada no projeto.
> - - Ex.: Diminuição do tempo de realização das tarefas, aumento da produtividade, aumento da satisfação do cliente, etc.
> - Influência: Alta, Média, Baixa
> - Importância: Alta, Média, Baixa
> - Apoio: Positivo, Negativo, Neutro
> - Observações: Informações adicionais, para o cliente.

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

> O Termo de Abertura do Projeto (TAP) representa o ponto de partida oficial para o empreendimento. 
> Ele sintetiza de maneira clara e concisa os objetivos, escopo, partes interessadas envolvidas, entregas esperadas, cronograma preliminar e recursos necessários para a execução bem-sucedida do projeto. 
> O TAP funciona como um contrato inicial entre a equipe do projeto e as partes interessadas, estabelecendo as bases para uma compreensão compartilhada dos propósitos e limites do projeto. 
> Ao delinear esses elementos de forma detalhada, o Termo de Abertura do Projeto (TAP) fornece uma direção sólida para orientar as atividades subsequentes, facilitando a gestão eficaz do projeto desde o início até o encerramento. 
> Essa documentação garante a clareza, alinhamento e comprometimento de todos os envolvidos, contribuindo assim para o sucesso do projeto.

> Você pode utilizar como referência o seguinte documento:
> [Termo de Abertura do Projeto](artefatos/termo-abertura-projeto.docx)

## Estimativa de Custo

......  COLOQUE AQUI O SEU TEXTO ......

> A avaliação da viabilidade econômica busca determinar a sustentabilidade financeira e o retorno sobre o investimento do empreendimento. 
> Este processo envolve a análise dos custos associados ao projeto, incluindo investimentos iniciais, despesas operacionais e potenciais custos de manutenção. 
> Simultaneamente, são examinados os benefícios esperados, como receitas, economias de custos e ganhos tangíveis e intangíveis. 
> A elaboração de projeções financeiras realistas e a aplicação de métricas como o Valor Presente Líquido (VPL) e a Taxa Interna de Retorno (TIR) contribuem para uma avaliação abrangente da viabilidade econômica do projeto. 
> Este processo permite que os gestores de projeto e as partes interessadas tomem decisões informadas sobre a continuidade, ajustes ou mesmo a interrupção do projeto, garantindo uma alocação eficiente de recursos e maximizando os benefícios econômicos esperados.

......  ATUALIZE OS ITENS DE CUSTO DO SISTEMA. ADICIONE NOVOS OU SUBDIVIDA ITENS, CASO NECESSÁRIO ......

| Item de Custo           | Descrição | Qtd. horas | Valor / hora | Valor total |
|-------------------------|-----------|------------|--------------|-------------|
| Recursos Humanos        |           |            |              |             |
| Hardware                |           |            |              |             |
| Serviços de Rede        |           |            |              |             |
| Hospedagem e Nuvem      |           |            |              |             |
| Software de terceiros   |           |            |              |             |
| Serviços e treinamento  |           |            |              |             |
| **Total Geral**         |           |            |              |             |


## Estimativa de Prazo

......  COLOQUE AQUI O SEU TEXTO ......

> A estimativa de prazo orienta tanto o cliente quanto a equipe de desenvolvimento do projeto em termos do tempo necessário para a conclusão do projeto como um todo. 
> Esta estimativa possibilita a criação de um cronograma realista e viável, permitindo o planejamento adequado das fases do projeto, alocação de recursos de maneira eficiente e antecipação de eventuais desafios.
> Uma estimativa precisa orienta a execução do projeto, contribui para a gestão de expectativas e para o estabelecimento de metas alcançáveis.

> Indique:
> * Prazo previsto (em horas) 
> * Data de início
> * Data de término

* Prazo previsto (em horas): XX horas
* Data de início: __ / __ / _____
* Data de término: __ / __ / _____

## Escopo Preliminar e Premissas

> Os requisitos preliminares fornecem uma visão inicial do escopo, funcionalidades-chave e as expectativas a serem atendidas. 
> 
> ***A quantidade mínima de requisitos a serem preenchidos nas seções abaixo não incluem os exemplos previamente fornecidos.***

## Declaração de Escopo

> Você pode utilizar como referência o seguinte documento:
- [Declaração de Escopo](artefatos/declaracao-escopo.docx)

> Enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:
>
> - [Requisitos Funcionais (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
>   correspondem a uma funcionalidade que deve estar presente na
>   plataforma (ex: cadastro de usuário).
>
> - [Requisitos Não Funcionais (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
>   correspondem a uma característica técnica, seja de usabilidade,
>   desempenho, confiabilidade, segurança ou outro (ex: suporte a
>   dispositivos iOS e Android).
>
> Lembre-se que cada requisito deve corresponder à uma e somente uma
> característica alvo da sua solução. Além disso, certifique-se de que
> todos os aspectos capturados nas Histórias de Usuário foram cobertos.
> 
> **Links Úteis**:
> 
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)


### Requisitos Funcionais

......  ATUALIZE OS REQUISITOS FUNCIONAIS DO SISTEMA (MÍNIMO 10) ......

A tabela a seguir apresenta os requisitos funcionais do projeto. 

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|-------|
|RF-001| Permitir que o usuário cadastre tarefas | ALTA | 
|RF-002| Emitir um relatório de tarefas no mês   | MÉDIA |

### Requisitos Não Funcionais

......  ATUALIZE OS REQUISITOS NÃO FUNCIONAIS DO SISTEMA (MÍNIMO 5) ......

A tabela a seguir apresenta os requisitos não funcionais do projeto. 

|ID     | Descrição do Requisito                                            |Prioridade |
|-------|-------------------------------------------------------------------|-----------|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móvel | MÉDIA     | 
|RNF-002| Deve processar requisições do usuário em no máximo 3s             | BAIXA     | 


### Restrições

......  ATUALIZE AS RESTRIÇÕES DO SISTEMA (MÍNIMO 5) ......

A tabela a seguir apresenta as restrições do projeto. 

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|-------|
|RE-001| Permitir que o usuário cadastre tarefas | ALTA | 
|RE-002| Emitir um relatório de tarefas no mês   | MÉDIA |


### Contra-Escopo

......  ATUALIZE O CONTRA-ESCOPO DO SISTEMA (MÍNIMO 5) ......

A tabela a seguir apresenta as atividades que não serão executadas no projeto

|ID    | Descrição do Contra-Escopo          | 
|------|-------------------------------------|
|CE-001| Treinamento de modelo de LLM        |
|CE-002| Pesquisa de viabilidade do mercado. |

### Condições para início do Projeto

......  ATUALIZE AS CONDIÇÕES PARA INÍCIO DOS PROJETOS (MÍNIMO 3) ......

A tabela a seguir, apresente as condições para que o projeto seja iniciado.

|ID    | Descrição de Condições para Início do Projeto    | 
|------|--------------------------------------------------|
|CI-001| Assinatura de contrato de prestação de serviços. |
|CI-002| Apresentação de garantias definidas no contrato. |

## Marcos Agendados e Entregas

......  ATUALIZE OS MARCOS AGENDADOS DO PROJETO E AS DATAS PARA ENTREGAS DAS TAREFAS ......

A tabela a seguir, identifique os marcos do projeto e os entregáveis previstos (requisitos).

|ID   | Marco do Projeto                                                  | 
|-----|-------------------------------------------------------------------|
|M-1  | Liberação do sistema para cadastro de informações e configuração. |
|M-2  | Permissão para uso do sistema, por usuários focais.               |
|M-3  |                                                                   |
|M-4  |                                                                   |
|M-5  |                                                                   |
|M-6  |                                                                   |

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

......  COLOQUE AQUI O SEU TEXTO ......

> Nesta parte do documento, você deve apresentar a metodologia adotada pelo grupo, descrevendo o processo de trabalho baseado nas metodologias ágeis, a divisão de papéis e tarefas e as ferramentas empregadas.
>
> Coloque detalhes sobre o processo utilizado e a implementação do Framework Scrum seguido pelo grupo. 
> O grupo deverá gerenciar as tarefas utilizando o GitHub Project para acompanhar o andamento do projeto, a execução das tarefas e o status de desenvolvimento da solução.
> 
> **Links Úteis**:
> - [Github Project](https://docs.github.com/en/issues/planning-and-tracking-with-projects/creating-projects/creating-a-project)
> - [O que é o GitHub Projects? | Guia de Iniciantes](https://www.youtube.com/watch?v=vxYTpsFKdiQ&ab_channel=JulioArruda)
> - [Introduction to GitHub Project Boards](https://www.youtube.com/watch?v=idZyqNIrt84&list=PLiO7XHcmTslc5hGrbnnmHIb0SeJLTpOEu&ab_channel=MickeyGousset)
> - [11 Passos Essenciais para Implantar Scrum no seu Projeto](https://mindmaster.com.br/scrum-11-passos/)
> - [Scrum em 9 minutos](https://www.youtube.com/watch?v=XfvQWnRgxG0)

## Divisão de Papéis

......  COLOQUE AQUI O SEU TEXTO ......

> Apresente a divisão de papéis e tarefas entre os membros do grupo.
> Indique as responsabilidades de cada membro do grupo no projeto.

## Ferramentas

......  COLOQUE AQUI O SEU TEXTO - SIGA O EXEMPLO DA TABELA ABAIXO  ......

> Liste as ferramentas empregadas no desenvolvimento do projeto, justificando a escolha delas, sempre que possível.
> Todas as ferramentas utilizadas devem ser listadas.
> Qualquer tipo de ferramenta que for utilizada para construção de um artefato deve ser identificada, uma vez que podem ser necessárias alterações.
> A necessidade de uso de licenças e possíveis custos relacionados devem ser indicados.

| Ambiente              | Plataforma         | Link de Acesso             | Justificativa |
|-----------------------|--------------------|----------------------------|---------------|
| Quadro Kanban         | Github             | https://github.com/XXXXXXX | Centralização e organização do projeto no próprio repositório. |
| Repositório de código | GitHub             | https://github.com/XXXXXXX |               |
| Protótipo Interativo  | MavelApp ou Figma  | https://figma.com/XXXXXXX  |               |
| Documentos Textuais   | LibreOffice Writer | N/A                        |               |
| Planilhas e Gráficos  | Google Planilhas   | https://docs.google.com/   |               |
| EAP / WBS             | | | |
| Cronograma do Projeto | | | |
| Matriz RACI           | | | |

```diff
+ Tarefa 03:
+ Fim da seção a ser atualizada.
```

----
