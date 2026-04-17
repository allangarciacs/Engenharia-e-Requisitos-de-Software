---
Anotações da disciplina de Engenharia e Requisitos de Software
---

## SOFTWARE
<pre>
- Conjunto de Instruções
- Dados
- Documentação
- É desenvolvido por um processo de engenharia, ou seja, não é fabricado no sentido clássico
- Um software não se desgasta

Campos de APLICAÇÃO de Software 
- Softwware de Sistema: Conjunto de programas para atender a outros programas (Sistema operacional)
- Software de aplicação: Necessidade específica de negócio (processamento de transações em pontos de venda)
- Software científico/de engenharia: Number Crunching (Geogebra -corrosão de materiais-, logística de entrega)
- Software embutido: Residente num produto (ar condicionado, microondas, geladeiras modernas)
- Software para linha de produtos: Semelhante ao de aplicação, mas com muitos clientes (Word,Ecxel, computação gráfica)
- Aplicação para Wen: Centralizada em rede (nuvem) 
- Software de inteligêngia artificial: solucionar problemas complexos que não são possíveis de computação ou de análise direta
- Software legado>: desenvolvido décadas atrás 
</pre>

## WebApps
<pre>
Atributos encontrados em Webapps
- Uso intensivo de redes: Um Webapp reside em uma rede e deve atender as necessidades de uma comunidade
- Simultaneidade: Muitos usuários podem acessar o Webaoo ao mesmo tempo
- Carga não previsivel: Número de usuários pode variar, em ordem de grandeza, de um dia para outro
- Desempenho: Ele deve ser eficiente, se não for o cliente pode buscar outra opção
- Disponivilidade: Visa-se o Webapp estar disponível todos os 365 dias do ano
- Orientação de dados: Usar hipermidias para apresentar textos, mídias, audios, gráficos, etc para o usuário
- Imediatismo: Colocar o software no mercado o mais rápido possível
- Estética: Uma das principais características é o visual do Webapp
</pre>

## ENGENHARIA DE SOFTWARE 
<pre>
Engenharia: É a organização de um processo para a construção de um produto

A engenahria de software é uma tecnologia em camadas
   . Ferramentas . 
  .    Métodos    .
 .    Processo     .
. Foco na qualidade . 

1. FOCO NA QUALIDADE: É a pedra fundamental que sustenta a engenharia de software.
2. PROCESSO: Conjunto de atividades, ações e tarefas na criação de algum produto de trabalho. No contexto de engenharia de software
, é uma abordagem adaptável que permite o pessoal da equipe realizar o trabalho e escolher o conjunto certo de ações e tarefas. Visa
entregar o software dentro do prazo e com qualidade. 
- atividade : objetivo amplo
- ação      : conjunto de tarefas que resultam num artefato de software
- tarefa    : objetivo pequeno, porém bem definido
3. MÉTODOS: Fornecem as informações técnicas para desenvolver o software. Uma ampla gama de tarefas, que incluem comunicação,
análise de requisitos, modelagem de projeto, contrução de programa, testes e suporte. São um conjunto de princípios básicos.
4. FERRAMENTAS: Fornecem o suporte automatizado ou semi automatizado para o processo e para os métodos. 

PROCESSO DE SOFTWARE
 - COMUNICAÇÃO   -> Características / Requisitos
   - PLANEJAMENTO  -> Custo / Tempo / *protótipo
    - PROJETO       -> U.M.l., esboço do produto            } Qualidade -> Teste / Gerência 
       - CONSTRUÇÃO    -> Criando código                  
         - ENTREGA       -> Documentação / Manutenção    

Metodologia ou Ciclo de Vida
- Controle e acompanhamento do projeto
- Gerantia de qualidade
- Revisões técnicas
</pre>

## PRINCIPIOS GERAIS 
<pre>
Os sete principios da engenharia de software, por David Hooker
1 - A razão de existir: gerar valor a seus usuários
2 - KISS (Keep It Simple, Stupid!): todo projeto deve ser o mais simples possível 
3 - Mantenha a visão: visão clara 
4 - O que um produz os outros consomem: projeto pensando que alguem terá de entender oq vc entá fazendo
5 - Esteja aberto para o futuro: Jamais faça projetos limitados
6 - Planeje com antecedência, visando a reutilização: Reduz o custo para reuso e aumenta o valor do sistema
7 - Pense!: Antes de agir, pensar de forma clara
</pre>

## MODELOS DE PROCESSO
<pre>
É um roteiro que ajuda a criar um resultado de alta qualidade e dentro do prazo estabelecido.
É realizado pelos engenheiros de software e os gerêntes do processo adaptam às suas necessidades.
Importância: proporciona estabilidade, controle e organização para uma atividade, que sem controle, pode ser caótica. Contudo, ele
deve ser ágil. 

Modelo de processo genérico: 
1. comunicação
2. planejamento
3. modelagem
4. construção
5. entrega
-> fluxo de processo linear: executa cada uma das atividades em sequência

FLUXO DE PROCESSO
Iterativo    : Repete uma mais atividades antes de prosseguir para a seguinte
Evolucionário: Executa as atividades de uma forma circular, onde cada volta gera uma versão mais completa
Parelelo     : Executa uma ou mais atividades em paralelo com outras (ex. modelagem paralelo c contrução)

MODELOS DE PROCESSO ESPECIALIZADOS
.DESENVOLVIMENTO BASEADO EM COMPONENTES: Incorpora características do modelo espiral. É evolucionário por natureza,
demandando abordagem iterativa para a criação do software. 
.MODELO DE MÉTODOS FORMAIS: Engloba um conjunto de atividades que conduzem à especificação matemática formal do
software. Métodos permitem especificar, desenvolver e verificar um sistema baseado em computador atravéz da aplicação
de uma notação matemática rigorosa. 
.DESENVOLVIMENTO DE SOFTWARE ORIENTADO A ASPECTOS: AOSD -> é um paradigma de engenharia de software relativamente
novo que oferece uma abordagem metodológica e de processos para definir, projetar e contruir aspectos.

PROCESSO UNIFICADO 
É uma tentativa de aproveitar os melhores recursos e características dos modelos tradicionais de processo de software,
mas caracterizando-os de modo a implementar muitos dos melhores principios do desenvolvimento de software.  
</pre>

## TIPOS DE MODELOS DE PROCESSO 
<pre>
V           : Garantia de qualidade. Testes depois de cada atividade
INCREMENTAL : Combina fluxos lineares e paralelo, Aplica sequências lineares
CASCATA     : Abordagem sequencial e sistemática com suporte contínuo do software concluído
 - Problemas 
  -> Mudanças podem provocar confusão à medida que o projeto processegue
  -> Requer que o cliente estebelece explicitamente todas as necessidades (oq é difícil)
  -> Cliente precisa ter paciência, pois ira demorar pra ter versões operacionais para teste

EVOLUCIONÁRIO: Tem características que permitem desenvolver versões cada vez mais completas do software.
 -> PROTOTIPAÇÃO:
 Protótipo elaborado rapidamente, "projeto rápido", que servirá para aprimorar requisitos
  - Problemas
   -> Exige que os engenheiros produzam os protótipos muito rapidamente, oq causa problemas
   -> Cliente pode não entender o que é um protótipo (n necessariamente organizado) e reclamar
   
 -> ESPIRAL:
 Gera modelos de processos utilizados para guiar a engenharia.
  - Problemas
   -> Difícil de convencer clientes (possível desconfiança na controle)
   -> Exige especialização na avaliação de riscos 
   -> Se um risco importante não for descoberto, inevitavelmente ocorrerão problemas
   
 -> CONCORRENTE: 
 Possibilita a equipe representar elementos concorrentes e iterativos de qualquer modelo.
 As atividades coexistem concorrendo entre si (estão em diferentes estados)
</pre>

## DESENVOLVIMENTO ÁGIL
<pre>
Combina filosofia e princípios de desenvolvimento, focando na forma como o software é criado.

EXTREME PROGRAMMING (XP) - É um método ágil criado por Kent Beck, focado em simplicidade
- Utiliza o princípio KIS (Keep It Simple)
Envolve as seguintes atividades:
- Planejamento : levantamento de requisitos por meio de histórias de usuário
- Projeto      : criação de soluções simples e adaptáveis
- Codificação  : desenvolvimento baseado em testes e programação em dupla
- Testes       : uso de testes automatizados e testes definidos pelo cliente

SCRUM - É um método ágil baseado em ciclos curtos chamados sprints
Foi criado por Jeff Sutherland e Ken Schwaber. Possui os seguintes elementos:
- Backlog          : lista de tarefas priorizadas
- Sprint           : período de desenvolvimento de 1 a 4 semanas
- Reuniões diárias : acompanhamento do progresso da equipe
- Scrum Master     : responsável por facilitar o processo
- Demos            : apresentação do software ao cliente

DSDM (Dynamic Systems Development Method) - Método ágil baseado em desenvolvimento iterativo e incremental
- Utiliza o princípio de Pareto (80/20) 
- Tem como foco entregar valor de forma rápida ao cliente
Suas fases incluem:
- Estudo de viabilidade
- Estudo do negócio
- Iterações de desenvolvimento
- Implementação

FDD (Feature Driven Development) - É um método baseado no desenvolvimento por funcionalidades
Cada funcionalidade é pequena e pode ser entregue rapidamente. Suas vantagens incluem:
- Facilidade de entendimento pelo cliente
- Melhor organização do projeto
- Entregas frequentes
Exemplos de funcionalidades:
- Adicionar produto ao carrinho
- Mostrar detalhes de produto

DEVOPS - Integra desenvolvimento e operações para melhorar o processo de entrega
Tem foco em automação e entrega contínua. Envolve etapas como:
- Planejamento
- Codificação
- Compilação
- Testes
- Lançamento
- Implantação
- Operação
- Monitoramento

KANBAN - É um método visual para gerenciamento de tarefas
Seus principais elementos são:
- Backlog  : lista de tarefas pendentes
- Workflow : etapas do processo
- WIP      : limite de tarefas em andamento
- Cartões  : representam as tarefas
Vantagens  :
- Melhor visualização do trabalho
- Identificação de gargalos
- Melhor fluxo de tarefas
Desvantagens :
- Menor foco em prazos
- Dependência da disciplina da equipe  
   
</pre>
   
## ENGENHARIA DE REQUISITO
<pre>
O que são REQUISITOS? Requisitos de um sistema são as descrições do que o sistema deve fazer, os serviços
que oferece e as restrições a seu funcionamento. Eles refletem as necessidades dos clientes para um sistema
que serve a uma finalidade determinada.

O que é ENGENHARIA DE REQUISITO? É o processo de analisar, descobrir, documentar e verificar esses serviços 
e restrições. 

STAKEHOLDERS: São pessoas, grupos ou organizações que influenciam ou são influenciadas pelo produto/projeto 
(positiva ou negativamente) em qualquer uma das fases. São todos aqueles interessados no sistema. Tipos:
- Internos       : membros da equipe e da organização
- Externos       : clientes, usuários finais, fornecedores, órgãos reguladores, etc.
- Diretos        : Primários - Usam, operam, ou recebem o resultado (usuário do sistema)
- Indiretos      : Secundários - sofrem impacto sem usar diretamente
- Patrocinadores : Têm poder de orçamento e prioridades (decisores)
- Reguladores    : definem normas, conformidade e padrões
- Opositores     : são afetados negativamente, podem perder poder/rotina com a mudança

DOMÍNIO DE NEGÓCIO
Trata-se da área específica na qual o software será desenvolvido. Corresponde à parte do mundo real que é
relevante para o desenvolvimento do software. Exemplos:
- Bancário : contas, transações, crédito, tarifas, compliance
- Saúde    : pacientes, atendimentos, exames, prescrições, prontuários
- Educação : cursos, turmas, matrículas, avaliações, histórico escolar

ENGENHARIA DE REQUISITO
- CONCEPÇÃO    -> Entender o problema e o objetivo do sistema em alto nível. Indentificar os stakeholders,
                   contexto e restrições
 - LEVANTAMENTO  -> Descobrir requisitos com os stakeholders e fontes de informação
  - ELABORAÇÃO    -> Classificar os requisitos
   - NEGOCIAÇÃO    -> Resolver conflitos 
    - ESPECIFICAÇÃO -> Resgistrar requisitos de forma clara
     - VALIDAÇÃO     -> Checar se o requisito foi feito da forma correta, revisão com stakeholder,
                        protótipos e testes de verificação
      - GERENCIAMENTO  -> Controlar mudanças, versionar e rastrear requisitos, monitorar status e manter o
                          sistema atualizado  
   
ANÁLISE DE REQUISITOS (Problemas)
- Comunicação do cliente com analista
- Evolução dos requisitos
- Gerenciamento de alterações
- Falta de conhecimento sobre o Domínio

LEVANTAMENTO DE REQUISITOS 
Há três tipos de atividades realizadas no processo de levantamento de requisitos:
- Elicitação dos requisitos : comunicação com os Stakeholders para determinar os requisitos do sistema
- Análise de requisitos     : determina estado do requisito (inacabado, incompleto, ambíguo, contraditíro)
- Registro de requisitos    : documentar os requisitos de várias formas - linguagem natural, casos de uso,
ou ainda processo de especificação

TIPOS DE REQUISITO
- Funcional     : Ação realizada pelo sistema
- Não funcional : Características de qualidade
- Normativos    : Dois tipos -> 1 - Normas dentro da lei
                             -> 2 - Normas criadas por 'você'
   
</pre>
