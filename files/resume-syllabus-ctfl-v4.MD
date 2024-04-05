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
