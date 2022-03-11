Aqui você vai encontrar todas as informações básicas sobre o projeto PAD UPE.

## **O que é o PAD?**

---

A resolução CONSUN Nº 015/2019 normatiza o Plano de Atividades Docentes (PAD), um instrumento de referência para o conjunto de atividades que podem ser desenvolvidas pelos docentes em cada um dos eixos (Gestão, Ensino, Pesquisa, Extensão e Cultura) na Universidade de Pernambuco.

## **O que é o PAD-WEB?**

---

PAD-UPE é um sistema web em desenvolvimento, que tem como objetivo suportar e guiar a operacionalização, monitoramento e publicação do PAD no âmbito institucional.

Será através dela que os professores, coordenadores setoriais, coordenadores de curso e gestores poderão preencher, validar e consultar os PADs do corpo docente e torná-los públicos à comunidade acadêmica.

## **Como surgiu o PAD-WEB?**

---

O Departamento de Computação da Universidade de Pernambuco Campus Garanhuns oferece à comunidade dois cursos de computação: Licenciatura em Computação e Bacharelado em Engenharia de Software. Existe uma visão na condução destes cursos em sempre alinhar as vivências práticas e teóricas através da construção de projetos colaborativos nos moldes de fábrica de software.

Este tipo de abordagem torna possível propiciar aos alunos, em diferentes estágios de seus cursos, a vivência colaborativa de projetos de desenvolvimento de um produto de software. Além de aproximar os discentes em formação da vivência real e aplicada dos conhecimentos contribuímos com o processo de melhoria e informatização institucional.

Por esta razão, acreditamos que a iniciativa com o PAD-WEB tem o potencial de poder propiciar o estreitamento entre os elos de ensino, pesquisa e extensão na vivência dos docentes e discentes dirata ou indiretamente envolvidos.

{{% alert color="warning" %}}
Este sistema é uma iniciativa do Multicampi Garanhuns de operacionalizar a normatização do PAD oportunizando também aos discentes a vivência de construção de um produto real vivenciando todas as etapas do ciclo de desenvolvimento de um software.
{{% /alert %}}

## **Documentaçao da Arquitetura**

---

O principal objetivo deste site é manter e registrar a arquitetura do sistema PAD-WEB. Documentar a arquitetura de um sistema de software compreende um esforço que exige tempo, conhecimento de ferramentas e técnicas de diagramação. O principal desafio é contemplar uma estratégia que permita que as informações arquiteturais sejam simples, objetivas e minimamente burocráticas de se manter.

Aqui nosso principal objetivo é tornar o processo de manter o registro das informações arquiteturais utilizando uma abordagem que nos permita fugir de dois cenários reais das documentações na engenharia de software:

- **Cenário 1:** Documentações complexas, confusas, obsoletas, que perdem seu propósito. Um investimento de esforço para algo que muitas vezes não é utilizado.

- **Cenário 2:** Documentações que sofrem com falhas, pouca informação e muita erosão.

A vivência de quaisquer um destes dois cenários não é benéfica para qualquer pessoa que trabalhe no ciclo de vida deste sistema.

A arquitetura do projeto tem como principal objetivo melhorar a experiência do usuário, por este motivo é essencial documentá-la, porque ela responde a várias perguntas, por exemplo:

- Como os componentes do PAD se integram, seja internamente ou com outros sistemas?
- Como consigo escalá-lo?
- Como garantir sua segurança?

Pensando nisso, o time do PAD-UPE criou uma visualização da nossa arquitetura utilizando uma abordagem mais mais simples: o C4 Model.

## **O que é o C4Model?**

---

Proposto po Simon Brown o C4 Model é baseado no modelo 4+1 e o UML. Ele foca em resolver problemas da documentação de arquitetura, com base em quatro tipos de diagramas que atendem a diferentes públicos alvo com diferentes níveis de detalhe.
A grande ideia é trazer mais clareza para o projeto utilizando níveis diferentes de diagramas que vão expressar, a cada nível mais interno, um grau maior de detalhe que o do nível anterior.
