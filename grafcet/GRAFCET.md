# Grafcet - SFC (Sequential Function Chart)

O Grafcet ( Graphe Fonctionnel de Commande, Étapes Transitions ) é uma linguagem gráfica que permite a descrição de ações sequenciais, paralelas e alternativas existentes numa aplicação, em uma parte específica do comando, de um sistema automatizado. Ele é utilizado para desenvolver acionamentos sequenciais ou dependentes do tempo.

## História

A linguagem Grafcet surgiu no ano de 1977, na França, quando a AFCET (Associação Francesa de Cibernética Econômica e Técnica), juntamente com a ADEPA (Agência Nacional de Desenvolvimento para a Produção) definiram a linguagem Grafcet como uma representação gráfica que traduz a evolução do ciclo de um automatismo sequencial.

## Conceito

Os conceitos básicos desse sistema de controle discreto eram extremamente claros e simples:

* `etapa`
* `ação associada à etapa`
* `transição`
* `condição associada à transição`

A "etapa" representa um estado parcial do sistema, no qual uma ação é realizada, uma etapa pode estar *ativa* ou *inativa*. A "ação associada" somente é realizada se a etapa estiver **ativa**, e permanece inalterada se a etapa estiver **inativa**. A "transição", essa conecta a etapa seguinte, representa uma decisão para mudança de estado do sistema. Para uma transição seja efetuada, tem que existir as condições que a "etapa" precedente à transição esteja ativa e que a condição associada à transição seja verdadeira.

A modelagem do processo que utiliza a linguagem Grafcet é dividida em cinco etapas:

* Especificação do processo
* Divisão do processo em etapas
* Descrição da parte sequencial para o controle das etapas
* Desenho de parte combinacional de cada etapa
* Implementação do processo

## Diagrama Funcional Sequencial (SFC)

Os elementos do **Diagrama Funcional Sequencial** são:

* **Etapas** - às quais são associadas as **Ações**.
* **Transições** - às quais são associadas as **Condições**.
* **Ligações Orientadas** - que conectam as etapas às condições, e estas às etapas.

Com essas combinações o Sistema Automatizado propociona uma representação *estática*, com isso a visão do sistema fica *dinâmica*.
