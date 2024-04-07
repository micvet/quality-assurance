# **Resumo Syllabus CTFL v4**

# 1. O que é um teste?

Teste é um conjunto de atividades para descobrir defeitos e avaliar a qualidade de partes de um software. O teste inclui diversas atividades e deve ser alinhado com o ciclo de vida do software.
Além da busca por erros, é importante se atentar ao fato de que o teste não serve apenas para validar os requisitos do programa, mas também para validar se atende às necessidades do cliente.

A testagem é de grande importância para garantir que os programas funcionem como deveriam, evitando problemas sérios, como perda financeira ou danos. Existem dois tipos principais de teste: dinâmico, que envolve executar o software, e estático, onde o programa não é executado. Além disso, o teste é uma atividade que requer planejamento, gerenciamento e habilidades analíticas dos testadores, apesar do auxílio de ferramentas.

## Principais objetivos de um teste:

* Identificar falhas e defeitos;
* Avaliar requisitos, histórias de usuários, projetos e código;
* Garantir a cobertura necessária de um objeto de teste;;
Verificar se os requisitos especificados foram atendidos;
* Verificar se o objeto de teste está em conformidade com os requisitos contratuais, legais e
normativos;
* Fornecer informações aos stakeholders para que eles possam tomar decisões informadas;
* Criar confiança na qualidade do objeto de teste;

O objetivo de um teste pode mudar conforme o produto testado, o ciclo de vida de desenvolvimento de software, contexto do negócio, etc. 

## Teste e depuração 
Teste e depuração são atividades diferentes. 
Um exemplo,  quando um teste dinâmico causa e identifica um problema, a depuração concentra-se em encontrar suas causas, analisá-las e resolvê-las. A depuração inclui:
* Reproduzir o problema;
* Identificar a causa raiz;
* Corrigir a causa.

Após as correções, é feito um teste de confirmação para verificar se o problema foi resolvido, de preferência pelo mesmo responsável pelo teste inicial. Testes de regressão adicionais podem ser realizados para garantir que as correções não afetem outras partes do sistema.

Quando um defeito é identificado pelo teste estático, a depuração concentra-se em sua remoção, já que o teste estático apenas encontra defeitos, sem os provocar.

## A necessidade dos testes de software

Os testes desempenham um papel crucial na entrega do produto prometido, com a qualidade desejável, dentro do prazo e escopo esperados.

Sua importância não está limitada às equipes de teste, pois qualquer pessoa envolvida pode contribuir para o sucesso do projeto com habilidades de teste. Ao testar componentes, sistemas e documentação associada, os defeitos no software podem ser identificados.

As contribuições dos testes para o sucesso são diversas. Eles fornecem uma maneira eficiente de detectar defeitos, e garantem que a real necessidade do projeto seja atendida. 
Por fim, testes podem ser necessários para cumprir requisitos contratuais, legais ou regulatórios.


## QA e QC

Embora "teste" e "garantia da qualidade" (QA) sejam usados quase como sinônimocs, na verdade o teste é uma ferramenta de controle de qualidade (QC), focado na detecção de defeitos. Já QA, é a abordagem preventiva, orientada ao processo, que se concentrando na implementação e aprimoramento dos processos de desenvolvimento e teste. 
Enquanto o QC é corretivo, a QA é proativa e visa garantir que os processos corretos sejam seguidos para gerar produtos de qualidade. Os resultados dos testes são utilizados tanto no QC, para corrigir defeitos, quanto no QA, para fornecer feedback sobre o desempenho dos processos de desenvolvimento e teste.


## Erros, Defeitos, Falhas e Causas-raiz

Definições:
* Erros:  equívocos provocados por seres humanos;
* Defeitos: defeito é ocasionado pelo erro (falta, bugs). Eles podem existir em várias partes do processo de desenvolvimento, compo na documentação, especificação de requisitos, no código-fonte ou até mesmo no script de teste. Se não forem detectados no início, podem gerar problemas nas fases posteriores. Ao serem executados, fazem com quem o programa tenha um resultado diferente do esperado. Esse resultado pode acontecer sempre ou em condições específicas;
* Falha: ocorrência em que o produto não executa uma função conforme esperado;
* Causa-raiz: a causa-raiz é o motivo que levou o produto a apresentar o defeito.

# Princípios de Teste

Existem diretrizes que podem ser aplicadas a todos os tipos de testes. São elas:

1) Os testes revelam a presença, mas não a ausência de falhas: Eles podem indicar que há falhas no sistema testado, mas não podem garantir sua total correção.
2) Testes exaustivos são impossíveis: Não é possível testar tudo. Em vez disso, devemos utilizar técnicas de teste, priorização de casos e testes baseados em riscos.
3) Testes antecipados economizam tempo e dinheiro: Corrigir defeitos no início do processo evita problemas posteriores e reduz os custos de qualidade.
4) Os defeitos se agrupam: A maioria dos problemas tendem a ser encontrados em algumas partes específicas do sistema.
5) Os testes se degradam: Repetir os mesmos testes pode torná-los menos eficazes na detecção de novas falhas. Modificações nos testes ou a criação de novos podem ser necessárias.
6) Os testes dependem do contexto: Não há uma abordagem única para todos os casos. Eles variam conforme as circunstâncias.
7) Falácia da ausência de defeitos: A ideia equivocada de que veritifcar o software garante o sucesso do sistema. Mesmo testando e corrigindo todos os defeitos encontrados, o sistema pode não atender às expectativas dos usuários ou aos objetivos do cliente.

# Atividades de teste, Testware e Papéis no teste 

O teste varia conforme o contexto, mas geralmente envolve conjuntos comuns de atividades que formam um processo de teste. Esse processo pode ser adaptado conforme a situação e é decidido durante o planejamento do teste. Vamos ver os aspectos gerais do processo de teste:

## Atividades e Tarefas de Teste

O processo de teste compreende diversas etapas cruciais, as quais, embora possam ocorrer em paralelo ou de forma iterativa, desempenham papéis essenciais na garantia da qualidade do software.
O Planejamento do Teste define metas e escolhe uma abordagem adequada para alcançá-las dentro das limitações contextuais, detalhado na seção 5.1.
O Monitoramento e Controle do Teste envolve a supervisão contínua das atividades de teste, comparando o progresso real com o planejado e tomando medidas corretivas conforme necessário, conforme explicado na seção 5.3.
A Análise de Teste compreende a identificação de recursos testáveis, priorização das condições de teste e avaliação dos riscos associados, respondendo à pergunta "o que testar?" com critérios de cobertura mensuráveis.
A Modelagem de Teste elabora as condições de teste em casos de teste, identifica itens de cobertura e define requisitos de dados de teste e ambiente de teste, respondendo à pergunta "como testar?".

## Processo de Teste no Contexto

Os testes estão inseridos nos processos de desenvolvimento organizacional, financiados pelos stakeholders para atender às necessidades de negócio, variando conforme diversos fatores contextuais.
Estes fatores influenciam aspectos como estratégias de teste, técnicas utilizadas e grau de automação, além de afetar questões como relatórios e documentação de teste.

Testware

O testware é gerado como produto das atividades de teste, com variações na forma como é produzido, organizado e gerenciado pelas organizações.

Produtos de trabalho incluem planejamento de testes, monitoramento, análise, modelagem, implementação e execução de testes, entre outros.

Rastreabilidade entre a Base de Teste e o Testware

A rastreabilidade é fundamental para monitorar e controlar efetivamente os testes, estabelecendo conexões entre elementos da base de teste, testware associado, resultados dos testes e defeitos detectados.
Ela apoia a avaliação da cobertura e facilita a detecção de mudanças e impactos durante o processo de teste, além de contribuir para auditorias e atender aos critérios de governança de TI.

Papéis no Teste

São abordados dois principais papéis nos testes: gerenciamento de testes e testador, com atividades e tarefas atribuídas variando de acordo com o contexto.

As responsabilidades de gerenciamento de testes envolvem planejamento, monitoramento, controle e conclusão de testes, enquanto os testadores focam na análise, modelagem, implementação e execução de testes.
