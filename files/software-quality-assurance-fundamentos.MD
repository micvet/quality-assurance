# Fundamentos de teste de software

* Este arquivo teve como base para sua criação o [Guia de Fundamentos de Testes](https://aicsvirtual.org/wp-content/uploads/2024/01/Guia-rapida-de-Fundamentos-del-Testing%E2%84%A2-3.pdf), da Asociación Internacional de Calidad de Software ™ e o documento ["Tipos de Teste de Software"](https://edisciplinas.usp.br/pluginfile.php/384739/mod_resource/content/1/Aula%205_2014_Tipos-de-teste-software-v2.pdf), do Departamento de Sistemas Eletrônicos da Escola Politécnica da USP. 

## 1) Conceituando a construção de um Software
Software é um conjunto de instruções ou programas de computador que são executados em um dispositivo eletrônico, como um computador, smartphone, ou outro dispositivo inteligente, e é projetado para oferecer funcionalidades específicas para os usuários. 

Possui um ciclo de vida, que pode variar muito a depender da matodologia utilizada em seu desenvolvimento, necessidades do projetos, etc. Mas de uma forma geral, podemos resumir seu ciclo de vida em:
### 1.1. Concepção:

Nesta fase, as necessidades e requisitos do software são identificados e documentados. Isso pode envolver a coleta de requisitos dos stakeholders, análise de mercado e definição de objetivos para o software.

### 1.2. Design:

Nessa fase, os requisitos coletados na fase anterior são transformados em um design técnico, incluindo a arquitetura do sistema, a definição de interfaces de usuário, o design de banco de dados, etc.

### 1.3. Desenvolvimento:

Nesta etapa, o software é construído com base no design. Os desenvolvedores escrevem código, criam interfaces de usuário, implementam funcionalidades, integram componentes do sistema, etc.\

### 1.4. Testes:

Os testes são uma parte crucial do ciclo de vida do software e podem ocorrer em várias etapas do seu ciclo de vida, a depender do objetivo r metodologia utilizada no desenvolvimento da aplicação.
Implantação/Implementação:

Após o software ser desenvolvido e testado, ele está pronto para ser implantado em um ambiente de produção. Isso pode envolver a instalação do software em servidores, a configuração de sistemas de banco de dados, etc.
Após a implantação, o software entra na fase de manutenção.

### 1.5. Manutenção:
Nesta etapa, o software é mantido, atualizado e aprimorado com o passar do tempo. Isso pode envolver a correção de bugs, a implementação de novos recursos, a otimização de desempenho, etc.

### 1.6. Descontinuação:

Em algum momento, o software pode ser retirado do mercado ou descontinuado devido a mudanças nas necessidades do usuário, avanços tecnológicos ou diversos outros motivos.<br>  

Um fator de grande importância quando abordamos o ciclo de vida de um software, é a fase de testes. Apesar de ser elencada como uma fase isolada, ele desempenha um papel muito importante durante todas as fases do ciclo de desenvovimento do software.

## 2. Teste de Software

### 2.1. O que é o teste de software?

Um teste de software é muito mais que simplesmente realizar um teste e documentar resultados. É o conjunto de atividades que garantem a qualidade do software e reduzem os riscos de falhas. Pode ser realizado em diferentes etapas do ciclo de vida do software.

### 2.2. Objetivos e benefícios do teste de software

**Principais objetivos:**<br>
* Garantir a qualidade do software, assegurando que atenda aos requisitos e seja confiável.
* Reduzir os riscos de falhas, detectando e corrigindo problemas antes da produção.
* Melhorar a confiabilidade do software para um funcionamento consistente.
* Validar os requisitos do software.
* Identificar e corrigir erros precocemente no processo de desenvolvimento.

**Principais benefícios:**<br>
* Redução de custos ao detectar e corrigir erros precocemente.
* Aumento da satisfação do cliente ao entregar software que atende às suas necessidades.
* Melhora da imagem da empresa ao oferecer software de qualidade.
* Redução de riscos ao identificar problemas de segurança ou integridade de dados.
* Melhoria da qualidade do software ao detectar e corrigir problemas.

### 2.3. Principios do teste de software
Os princípios da execução dos testes inclui os seguintes conceitos: <br>

* Detecção precoce de defeitos: a detecção precoce de defeitos aumenta a qualidade e economia de recursos do software.
* Não é possível alcançar exaustividade absoluta nos testes: é impossível testar tudo.
* Defeitos tendem a se agrupar.
* A paradoxa do pesticida: um conjunto fixo de testes eventualmente perde eficácia.
* A ausência de erros é uma falácia, mas é possível alcançar um risco aceitável de falhas.
* A importância de adaptar o enfoque de testes ao contexto do software.

### 2.4. Outros conceitos importantes:<br> 

**2.4.1.  Diferença entre Erros, Defeitos e Falhas**<br>

* Erro: Ação humana que produz um resultado incorreto ou inesperado.
* Defeito: Problema no código ou design do software que causa mau funcionamento. É a consequência do erro.
* Falha: Manifestação visível de um defeito quando o software é executado.

**2.4.2. Diferenças entre QA e QC** <br>

* QA:  foca em processos preventivos para verificar o software em desenvolvimento.
* QC: concentra-se em medidas corretivas, examinando o produto acabado para garantir seu desenvolvimento conforme os requisitos definidos.

Em resumo, o QA tem um escopo mais amplo, enquanto QC se aprofunda em aspectos de execução e verificação, como testes.

**2.4.3. Diferenças entre QA e Teste de Software** <br>

* QA: QA (ou garantia da qualidade, em português), concentra-se na qualidade do processo de desenvolvimento de software e abrange todo o ciclo de vida do desenvolvimento de software, desde o planejamento até a implementação. É de responsabilidade da equipe de desenvolvimento de software e é Orientado ao Processo. Adota um enfoque preventivo e garante que os padrões de qualidade sejam seguidos em todo o processo de desenvolvimento de software, resultando em um produto final de qualidade.

* Teste de software: Já o teste de software concentra-se na qualidade do produto de software, e se limita principalmente à fase de testes, que como visto anteriormente, pode ocorrer  junto a outras fases do desenvolvimento do software. O teste é responsabilidade da equipe de testes e é Orientado ao Produto (Teste de Software). Adota um enfoque corretivo: identifica defeitos no software para que possam ser corrigidos antes do lançamento.

**2.4.4. Teste e Depuração**

É muito importante diferenciar o processo de teste e depuração. O teste descobre defeitos, enquanto a depuração elimina esses defeitos do sistema. A depuração é um processo de resolução de problemas existentes que começa após a conclusão do teste, quando a equipe de desenvolvimento busca as causas subjacentes dos defeitos relatados.
A depuração não deve ser abordada sem um conhecimento completo de todas as possíveis causas. Ela inicia quando a natureza do defeito é completamente compreendida, evitando a introdução de novos problemas em outros módulos.
A conexão entre teste e depuração se manifesta em um ciclo contínuo, onde as testagens descobrem, a depuração corrige e o feedback melhora a estratégia de teste. A colaboração entre esses processos é essencial para alcançar um software confiável e de qualidade.

**2.4.5. Verificação e Validação**

Verificação e a validação são duas dimensões essenciais que, embora relacionadas, abordam aspectos diferentes no campo da qualidade do software. 

* Verificação: A verificação refere-se ao processo de avaliação e confirmação de que um produto de software, sistema ou componente cumpre com as especificações e requisitos estabelecidos durante o seu desenvolvimento. Abrange diversas atividades, como testes unitários, revisões de código, testes de documentação e outras verificações para garantir que cada elemento do software esteja em conformidade com os padrões estabelecidos.

* Validação: A validação foca em confirmar que o software entregue satisfaz as necessidades e expectativas reais do usuário final. Assegura que o software esteja construído corretamente,  e que também seja relevante para aqueles que o utilizarão.<br>

Em resumo, a verificação constante assegura que cada ajuste cumpra com as normas, enquanto a validação intensifica seu enfoque para o usuário final nas etapas finais do desenvolvimento.

**2.5.6. Cargos comuns numa equipe de testes:**

* Líder/Gerente de Testes (Test Lead/Manager): Responsável por liderar o processo de testes, definindo e planejando as atividades de testes para a equipe, garantindo recursos adequados, supervisionando a alinhamento entre testes e desenvolvimento de software, gerando relatórios de status e mantendo uma comunicação eficaz com a equipe e clientes. Necessita de experiência em gestão e liderança.

* Engenheiro de Testes (Test Engineer): Responsável pela execução dos testes, incluindo compreensão e análise de documentos para identificar o que será testado, colaboração com o gerente de testes para determinar recursos necessários, desenvolvimento e execução de casos de teste, relatório e priorização de defeitos. Suas habilidades devem ser focados em habilidades técnicas de teste.

### 2.5. Fases do processo de testes<br>

O desenvolvimento de software envolve uma série de atividades essenciais que são executadas de forma relacionada. Essas atividades geralmente ocorrem em uma sequência lógica, mas sua implementação pode variar conforme as necessidades do projeto. Essas fases são:

**2.5.1. Planejamento de Testes:** Baseia-se em definir objetivos de testes e selecionar a estratégia mais adequada para alcançá-los, considerando os contextos gerais do projeto.

**2.5.2. Monitoramento dos Testes:** A supervisão das atividades de testes e do progresso, com o plano estabelecido, são fundamentais. O controle de testes envolve tomar ações para cumprir os objetivos dos testes, garantindo sua efetividade.

**2.5.3. Análise de Testes:** Este passo envolve a análise da base de testes para identificar as características que podem ser testadas, e a definição e priorização das condições de teste e seus riscos. É a avaliada possibilidade de defeitos nos objetos de teste.

**2.5.4. Design de Testes:** O design detalha como os testes serão executados, desde a elaboração de condições de teste até a criação de casos de teste, etc. Inclui a definição de requisitos, design do ambiente de teste e identificação da infraestrutura e das ferramentas necessárias.

**2.5.6. Implementação de Testes:** A implementação inclui a criação dos testes necessários para sua execução, organização de casos de teste e criação de scripts de teste, tanto manuais quanto automatizados.

**2.5.7. Execução de Testes:** Esta etapa envolve a execução dos testes. Os testes podem ser manuais ou automatizados, e os resultados obtidos são comparados com o esperado. Desconformidades são analisadas para identificar suas possíveis causas e toda a informação relevante é registrada.

**2.5.8. Encerramento de Testes:** Ao atingir o fim dos testes planejados, são realizadas atividades de encerramento que incluem a resolução de defeitos pendentes, a identificação e arquivamento de elementos de teste úteis para o futuro, e a análise de lições aprendidas para melhorar projetos futuros.

##2.6. Tipos de Teste de Software
De acordo com o ISTQB, os testes podem ser classificados em função do estágio do ciclo de vida ou em função do objetivo de teste.

**2.6.1.** Classificação dos Testes de Acordo com o Estágio do Ciclo de Vida do Produto:

Essa abordagem se concentra em avaliar o software em diferentes fases do seu desenvolvimento e implementação.<br>
Pode incluir:

* Teste de Unidade: Avaliação individual dos componentes do software para garantir seu funcionamento correto. Geralmente feito pelo desenvolvedor e pode envolver simulação de dependências.

* Teste de Integração: Verificação das interações entre os diferentes módulos ou componentes do sistema para garantir sua integração adequada. Pode ser conduzido em vários níveis, incluindo integração entre componentes e integração entre sistemas.

* Teste de Sistema: Avaliação do sistema como um todo para verificar se atende aos requisitos funcionais e não funcionais. O ambiente de teste deve refletir o ambiente de produção o máximo possível.

* Teste de Aceitação: Conduzido pelos usuários finais ou clientes para validar se o sistema atende às suas necessidades deles. 

* Teste de Manutenção: Realizado após modificações no sistema para garantir que as alterações não introduzam novos defeitos.

**2.6.2.** Classificação dos Testes de Acordo com o Objetivo do Teste:

Esse conjunto de tipos de teste visa abordar diferentes aspectos do software além de sua funcionalidade básica:

* Teste Funcional: Verificação das funcionalidades do software com base nos requisitos especificados. Visa garantir que o software realize as operações esperadas corretamente. Considera o comportamento externo do software (teste de caixa-preta).

* Teste Não Funcional: Avaliação de aspectos como desempenho, usabilidade, segurança e confiabilidade do software, que não estão relacionados diretamente às suas funcionalidades específicas. Inclui os testes:
** Teste de desempenho; 
** Teste de carga; 
** Teste de estresse; 
** Teste de usabilidade; 
** Teste de interoperabilidade; 
** Teste de manutenibilidade; 
** Teste de confiabilidade; 
** Teste de segurança; 
** Teste de portabilidade.

* Teste Estrutural (Teste de Caixa Branca): Avaliação da estrutura interna do software, examinando o código fonte e sua execução para garantir que a lógica do programa seja correta e eficiente.

* Teste de API: Verificação das interfaces de programação de aplicativos (APIs) para garantir que se comuniquem corretamente e forneçam os resultados esperados.

* Smoke Test: Verificação rápida das principais funcionalidades do software para garantir que esteja estável o suficiente para testes mais detalhados.

* Teste Exploratório: Abordagem de teste não estruturada, onde os testadores exploram o software dinamicamente para descobrir defeitos inesperados.

* Teste de Acessibilidade: Avaliação do software para garantir que seja acessível a todos os usuários, incluindo aqueles com deficiências visuais, auditivas ou motoras.

* Teste de Máquinas de Estado: Avaliação do comportamento do software em diferentes estados ou condições, verificando se as transições entre estados ocorrem corretamente e sem falhas.

