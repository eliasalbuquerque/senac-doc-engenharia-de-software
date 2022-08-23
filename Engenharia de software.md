# Engenharia de Software


> Conteúdo extraído das webaulas e serve apenas para **anotações pessoais** referente aos estudos da matéria. Sendo assim, não pode ser utilizado como material de desenvolvimento de trabalhos escolares de outras instituições.


Aula01

## Processo de Software - Atividades fundamentais

- **Especificação de software:** Desenvolvedor e cliente definem o que será feito.
- **Desenvolvimento de software:** Projetado e programado.
- **Validação de software:** Verifica se atende às necessidades do cliente.
- **Evolução de software:** Atende às mudanças de requisitos do projeto.



## Requisitos de Qualidade de Software

- Manutenibilidade.
- Confiança e proteção.
- Eficiência.
- Aceitabilidade.

> Obs.: Não existe *requisitos padrão* de qualidade para o desenvolvimento. Cada aplicação tem a sua e deve ser analisada de acordo com as suas próprias características.



## Engenheiro de Software

O engenheiro de software deve ter os seguintes requisitos:

- **Conhecimento técnico:** Para o uso de ferramentas e tecnologias para solucionar o problema.
- **Conhecimento da área de negócios:** Para adequar o desenvolvimento e a implantação do software ao ambiente de negócio do cliente.
- **Comportamento Ético e Moral:** Comporta-se conforme os aspectos éticos e morais da sociedade. Isso abrange também:
    - Confidencialidade
    - Competência
    - Direitos de propriedade intelectual
    - Preservação de recursos

----

Aula02

## Processo de Desenvolvimento de Software: Sequência e Evolução

Os seguintes pontos devem ser analisados para a qualidade de desenvolvimento do projeto.

- **Ciclo de vida:** Da concepção até a descontinuação.
- **Modelo de ciclo de vida do software:** Para gerenciar o desenvolvimento de software é necessário haver uma representação através de diagramas.
- **Processo de software:** Conjunto de atividades divididas em fases. Começa com uma abstração do que será o projeto, por textos, documentos, diagramas, etc, e conforme evolui o projeto, mais concreto fica a solução. Dentre as fases mais comuns são:
    - Especificação
    - Projeto
    - Implementação
    - Testes
    - Evolução
- **Necessidade do negócio:** Referente a construção ou evolução de um software:
    - Correção
    - Adaptação
    - Funcionalidades e características
    - Novo produto
- **Dificuldades:** Alguns pontos como exemplo:
    - Complexidade
    - Conformidade
    - Modificabilidade
    - Invisibilidade

----

Aula03

## Processo de Desenvolvimento de Software: Prototipagem, Modelo Espiral, Componentização e UP

- **Estratégia linear:** Inadequada para lidar com mudanças de requisitos.
- **Estratégia iterativa:** Adequada quando temos apenas uma ideia vaga dos requisitos, e será detalhada ao longo do desenvolvimento.
- **Estratégia evolucionária:** Executa a atividade de forma circular e a cada volta produz uma versão mais completa do software.
- **Prototipagem:** Útil principalmente na fase de requisitos e no projeto de interface gráfica de usuário. Após definido os requisitos, o protótipo é descartado.
- **Modelo espiral:** Muito parecido com a Estratégia Evolutiva, suas características são:
    - Integração entre disciplinas de Gerência de Projetos e Engenharia (técnica).
    - Diminuição de riscos do desenvolvimento (análise de riscos).
    - Envolvimento do cliente a cada iteração ou produto obtido.
    - Aplicável quaisquer estratégias anteriores em cada ciclo do Modelo Espiral.
- **Componentização:** Reutilização de artefato de software para compor outros projetos.
- **Modelo de processo UP (Unified Process):** Adota:
    - Desenvolvimento baseado em componentes.
    - Processo iterativo e incremental.
    - **RUP (_Rational Unified Process_):** Instância mais específica do UP:
        - Desenvolvimento iterativo.
        - Utiliza arquitetura de componentes.
        - Modelagem visual _UML_.
        - Necessidade de ferramentas de desenvolvimento.
        - **Etapas do projeto RUP:**
            - Concepção: Definição clara do que é o produto a ser desenvolvido.
            - Elaboração: Detalhamento da especificação (análise).
            - Construção: Elaborar o software.
            - Transição: (Implantação) Atividades que conduzem o produto ao ambiente de produção.

----

Aula04 

## Metodologia Ágil

Valorizar mais:

- **Indivíduos e interações** do que processos e ferramentas.
- **Software em funcionamento:** do que documentação abrangente.
- **Colaboração com o cliente** do que negociação de contratos.
- **Responder às mudanças** do que seguir um "plano".

Metodologia Ágil mais famosa é o **_Scrum_**:

- Framework (conjunto de conceitos) aplicado para resolver o problema de desenvolvimento de software.
- Papéis específicos:
    - Equipe de desenvolvimento: Grupo auto-organizável e multifuncional.
    - Product Owner: Pessoa que sabe o que é o software que tem que ser feito. Responsável pelo _Backlog do Produto_.
    - Scrum Master: Especialista na metodologia _Scrum_ e facilitador quando surgem problemas durante o desenvolvimento.
- Características do _Scrum_:
    - 30 dias de _sprint_
    - A cada 24h, uma reunião de 15min para verificar 3 pontos:
        - O que foi realizado desde a última reunião?
        - Há alguma dificuldade?
        - O que você irá fazer antes da próxima reunião?

----

Aula05

## Gerência de Projetos

**Projeto** é o esforço temporário para criar um produto.

Características de um projeto:

- Objetivo: Definido no começo e deve ser alcançado no final.
- Ciclo de vida definido: Iniciação, planejamento, execução, controle e encerramento.
- Complexidade de diferentes níveis no desenvolvimento.
- Produz um produto, serviço ou resultado único.
- Riscos.
- Recursos limitados: Tempo, custo, materiais, equipamentos e pessoas.

Fatores de sucesso de um projeto:

- Acordo entre desenvolvimento, gerência e cliente.
- Plano do caminho geral e responsabilidades definidas.
- Comunicação constante e efetiva entre todos os envolvidos.
- Escopo controlado.
- Gerência apoiada deve ser o patrocinador do projeto e facilitador do desenvolvimento.

Gerente de projetos, atribuições e responsabilidades:

- Elaboração de propostas.
- Planejamento de projetos:
    - Criar definição do projeto.
    - Desmembrar o trabalho em tarefas menores.
    - Identificar as relações entre as tarefas.
    - Fazer estimativas de tempo de execução de cada tarefa.
    - Calcular o cronograma inicial.
    - Atribuir e nivelar os recursos.
- Gerenciamento de riscos:
    - Riscos de projeto.
    - Riscos de produto.
    - Riscos de negócio.
    - Fases:
        - Identificação de riscos: Lista de riscos potenciais.
        - Análise de riscos: Lista priorizada de riscos.
        - Planejamento de riscos: Prevenção de riscos e planos de contingência.
        - Monitoração de riscos: Avaliação de riscos.
- Gerenciamento de pessoas:
    - Montar equipes conforme as características do projeto.
    - Motivar, desenvolver habilidades e capacitar membros da equipe segundo as necessidades do projeto.
- Gerenciamento de comunicação: Processos requeridos para garantir a geração, coleta, disseminação e armazenamento das informações do projeto.

----

Aula06

## Engenharia de Sistemas

**Sistema** - Conjunto de componentes que funcionam juntos para garantir um objetivo.

Tipos de sistemas:
    
- Sistemas de computadores: Integração de hardware e software
- Sistemas sócio-técnicos: Agrega conhecimento e componentes para alcançar metas objetivos.


Propriedades dos Sistemas

- Propriedades funcionais: Refere-se a funcionalidade do sistema.
- Propriedades não funcionais: Referem-se ao comportamento do sistema em seu ambiente operacional.

**Engenharia de Sistemas** - Fluxo de atividades que começa na aquisição, especificação, projeto, implementação, validação, operação e manutenção de sistemas sociotécnicos.

----

Aula07

## Engenharia de Requisitos

- **Requisito (Sommerville)** - Declaração em alto nível de um serviço que o sistema deve oferecer ou uma restrição imposta que deve ser atendida.
- Entendimento pleno das necessidades do cliente.
- Descrição clara do que o sistema deve atender.
- Processo iterativo para definir as requisições.

----

Aula08

## Documento de Visão de Projeto

- **Escopo:** Roteiro do que deve ser feito pela equipe de desenvolvimento.
- **Escopo do produto:** Características e funções do resultado esperado após o desenvolvimento.
- **Escopo do projeto:** Trabalho que deve ser realizado para a entrega do produto.
- **Gestão dos escopos:** Envolve definições, rastreabilidade e gerenciamento de mudanças.

----

## Modelagem de Sistemas e UML

Aula09

A modelagem irá facilitar a discussão e as decisões de projeto, registro em forma de documento e elaboração da descrição do projeto.

O modelo gráfico mais famoso é o UML (_Unified Modeling Language_) que reune requisitos para a visualização dos modelos de sistemas e as interações entre si.

----

## Orientação a Objetos

Aula10

<!-- Esse modelo auxilia no gerenciamento da complexidade do projeto, no entendimento, na comunicação, redução de custos do processo e previsão de comportamentos futuros do sistema. -->

**Orientação a objetos** é uma forma de organizar o software como uma coleção de objetos distintos, que interagem de acordo com seu comportamento e estrutura préviamente definida. Dentre seus componentes temos:

- Objetos
- Classes
    - Atributos
    - Metodos
- Encapsulamento
- Herança
- Polimorfismo

----

## Modelagem de Sistemas e UML

Aula11

Abordado na Aula 09, modelagem de sistemas é a visualização gráfica dos sistemas do projeto e suas interligações. É composto pelas seguintes características:

- **Diagrama de classes:** Descreve classes, atributos, métodos, instâncias, associações e restrições entre classes.
- **Classe:** Contém os atributos e os métodos a serem instânciados.
- **Atributos:** Propriedades do objeto.
- **Métodos:** Funções que podem ser de uso dos objetos ou de outras classes.
- **Associação:** Indica correlação entre classes.
- **Multiplicidade:** Relação entre as classes:
    - 0: não pode ser acessado.
    - 1: um acesso.
    - *: vários.
- **Herança:** Sub-classes que herdam características de uma classe superior (Super-classe).
- **Restrição:** Condicional criada para classes.
- **Agregação:** Classes que são dependentes entre si. Representado por um losângulo vazio.
- **Composição:** É o mais comum de ter em um projeto, onde uma classe e suas sub-classes são totalmente dependentes de uma classe superior. Representado por um losangulo preenchido.
- **Classe associativa** ou **Composta de Associação:** Classe que está entre duas classes associadas e instância um resultado dessa associação.
- **Classes abstratas:** Essas classes não possuem Objetos, nesse caso não podem ser instanciadas diretamente. Seus objetos se dão por sub-classes associadas a elas.
- **Classes concretas:** Classes que possuem Objetos e podem ser instanciadas diretamente.
- **Interface:** Estabelece as funções que podem ser acessadas para cada classe.

A modelagem de sistemas pode ser usada em:

- Modelagem de processo de negócio.
- Modelagem da lógica de um caso de uso.
- Modelagem da lógica de uma operação complexa.

----

## Verificação, Validação e Testes

Aula14

- **Verificar** e **Validar** avalia a qualidade do software quanto a sua especificação.
- **Teste** é a principal atividade da Verificação e da Validação. Suas características de Estratégia de Testes são:
    - Planejamento de teste.
    - Projeto de casos de teste.
    - Execução de teste.
    - Avaliação dos resultados.

Garante que o sistema de software produzido atenda os requisitos do escopo do projeto.

----

## Evolução

Aula15

O software não termina na entrega do produto, existe uma evolução de projeto após a entrega e visa adaptar o software quanto às atualizações de funcionalidades, requisitos, leis, processos novos de desenvolvimento e etc.

Para tal, existe a **Gestão de Mudanças** que gerencia a avolução do software e organiza os requisitos necessários como:

- Documentação atualizada.
- Requisitos rastreáveis.

Ao término das fases de desenvolvimento temos um **Release**, que de acordo com as necessidades, o processo de desenvolvimento reinicia para gerar novo release.

