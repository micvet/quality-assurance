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

## Atividades de Teste

O processo de teste compreende diversas etapas cruciais, que, embora possam ocorrer em paralelo, desempenham papéis importantes na garantia da qualidade do software.
* O Planejamento do Teste define metas e escolhe a abordagem adequada para atingí-las dentro das limitações contextuais;
* O Monitoramento do Teste envolve a supervisão contínua das atividades de teste, comparando o progresso real com o planejado e tomando medidas conforme necessário;
* A Análise do Teste compreende a identificação de recursos testáveis, priorização das condições de teste e avaliação dos riscos associados, respondendo à pergunta "o que testar?";
* A Modelagem de Teste elabora as condições de teste em casos de teste, identifica itens de cobertura e define requisitos de dados de teste, ambiente de teste e qualquer infraestrutura ou ferramenta que será neessária para o teste, respondendo à pergunta "como testar?";
* A implementação do teste prepara os materiais necessários, como dados de teste, e elabora os casos de teste, organizando-os em procedimentos e conjuntos. Scripts de teste são criados, manualmente ou automaticamente, e priorizados conforme um cronograma para execução. O ambiente de teste é estabelecido e verificado;
*A execuçao do Teste realiza os teste conforme planejado, de forma manual ou automatizada, incluindo diferentes abordagens. Os resultados são comparados com o esperado, registrados, e quaisquer anomalias são analisadas para relatar falhas;
*A conclusão do Teste ocorre em marcos do projeto (lançamento, fim, etc.) para resolver defeitos remanescentes, solicitações de alteração. etc. Materiais úteis são identificados e armazenados, o ambiente de teste é encerrado, as lições aprendidas são revisadas para futuras melhorias e um relatório de conclusão é elaborado para os stakeholders.

## Processo de Teste no Contexto

Os testes estão inseridos nos processos de desenvolvimento de um negócio, financiados pelos stakeholders para atender às necessidades deles, variando conforme diversos fatores contextuais, como: <br>

* Stakeholders: Suas necessidades, expectativas, requisitos e colaboração.

* Membros da equipe: Habilidades, experiência, disponibilidade e necessidades de treinamento.

* Domínio do negócio: Criticidade do objeto de teste, riscos, demandas do mercado e normas legais.

* Fatores técnicos: Tipo de software, arquitetura e tecnologia.

* Restrições do projeto: Escopo, tempo, orçamento e recursos.

* Fatores organizacionais: Estrutura, políticas e práticas organizacionais.

* Ciclo de vida do desenvolvimento: Práticas de engenharia e métodos de desenvolvimento.

* Ferramentas: Disponibilidade, usabilidade e conformidade.

Esses elementos influenciam diversos aspectos dos testes, como estratégia, técnicas e automação cobertura necessária, detalhamento da documentação de teste e relatórios, etc.

## Testware

O testware é gerado como produto das Atividades de Teste, com variações na forma como é produzido, organizado e gerenciado pelas organizações.
Existem variações na criação, modelagem, nomenclatura, organização e gestão de seus produtos de trabalho, conforme a organização.
Produtos de trabalho incluem planejamento de testes, monitoramento, análise, modelagem, implementação e execução de testes, entre outros:

* Produtos de trabalho do Planejamento de Testes: Incluem plano de testes, cronograma de testes, registro de riscos e critérios de entrada e saída. O registro de riscos é uma lista de riscos com probabilidade, impacto e informações de mitigação;

* Os produtos de Monitoramento e Controle de Testes: Incluem relatórios de progresso de testes, documentação de diretrizes de controle e informações sobre risco;

Os produtos de Análise de Teste: Incluem condições de teste priorizadas e relatórios de defeitos relacionados, referentes a defeitos na base de
teste;

Os produtos de Modelagem de Teste: Incluem casos de teste priorizados, cartas de teste, itens de cobertura, requisitos de dados de teste e requisitos de ambiente de teste;

Os produtos de Implementação de Teste: Incluem procedimentos de teste, scripts de teste automatizados, conjuntos de teste, dados de teste, cronograma de execução de teste e elementos do ambiente de teste. Exemplos de elementos do ambiente de teste: stubs, drivers, simuladores e virtualizações de serviço.

Os produtos de Execução de Testes: Incluem registros de testes e relatórios de defeitos.
Registros de testes e relatórios de defeitos são gerados aqui.

Os produtos de Conclusão do Teste: Incluem relatório de conclusão do teste, itens de ação para melhoria de projetos ou iterações subsequentes, lições aprendidas documentadas e solicitações de alteração.


## Rastreabilidade entre a Base de Teste e o Testware

Para efetuar o controle dos testes de forma eficaz, é crucial manter uma ligação entre os elementos da base de testes, o testware relacionado e os resultados obtidos. Essa conexão é fundamental para avaliar a extensão da cobertura dos testes, sendo útil estabelecer critérios mensuráveis para tal cobertura na base de testes.
Exemplo de utilidade é verificar se os requisitos estão abordados nos casos de teste, ou avaliar o risco remanescente através da correlação entre os resultados dos testes e os riscos identificados.
Além de avaliar a cobertura, a rastreabilidade facilita a compreensão das mudanças, auxilia em auditorias de teste, contribui para atender critérios de governança de TI, e também torna os relatórios de progresso mais compreensíveis e comunica de forma acessível os aspectos técnicos dos testes aos stakeholders, fornecendo informações cruciais para avaliar a qualidade do produto e o progresso do projeto.

## Papéis no Teste 

- No âmbito deste currículo, dois papéis principais são discutidos: o papel de gerenciamento de testes e o papel do testador.
- As responsabilidades desses papéis variam de acordo com o contexto do projeto, as habilidades das pessoas envolvidas e a estrutura organizacional.
- O gerenciamento de testes assume a liderança nas atividades de planejamento, monitoramento, controle e conclusão dos testes, podendo ser desempenhado por diferentes membros da equipe dependendo do contexto, como líderes de equipe ou gerentes de desenvolvimento.
- O testador concentra-se na engenharia técnica dos testes, envolvendo atividades como análise, modelagem, implementação e execução.
- Pode ocorrer que uma pessoa assuma ambos os papéis em momentos distintos ou até mesmo simultaneamente.

## Habilidades e Práticas Essenciais em Testes

- Habilidade é a capacidade de executar tarefas com eficiência, baseada em conhecimento, prática e aptidão.
- Testadores devem possuir habilidades essenciais para desempenhar bem suas funções, incluindo participação eficaz em equipe e capacidade de realizar testes com diferentes níveis de independência.

# Habilidades essenciais e boas práticas em testes 

Habilidades como conhecimento sobre testes, meticulosidade, comunicação eficaz, pensamento analítico, conhecimento técnico e de domínio são fundamentais para os testadores. A comunicação eficaz é crucial para superar possíveis resistências à informação de defeitos e falhas, transmitindo-as de maneira construtiva.

## Abordagem de Equipe Completa

A habilidade de trabalhar efetivamente em equipe e contribuir para objetivos comuns é crucial para os testadores. A abordagem de equipe completa, originada da Extreme Programming, enfatiza a colaboração entre os membros da equipe, permitindo que todos contribuam para a qualidade do projeto.
Isso inclui a colaboração com outros membros da equipe, como representantes de negócios e desenvolvedores, para alcançar os níveis desejados de qualidade e influenciar o desenvolvimento do produto.

## Independência nos Testes

Um certo grau de independência é importante para os testadores, pois permite que identifiquem defeitos de forma mais eficaz devido às diferenças nos vieses cognitivos.
Os testes podem ser realizados com diferentes níveis de independência, cada um com suas vantagens e desvantagens, visando identificar uma ampla gama de defeitos.
Testadores independentes podem reconhecer diferentes tipos de falhas, mas também podem enfrentar desafios como falta de colaboração e possível isolamento da equipe de desenvolvimento.
