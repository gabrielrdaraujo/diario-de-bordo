---
title: "Formação de equipe — 23/09/2026"
authors: ["DiscípuloDoNoFluxo"]
tags: [formacao-equipe]
date: 2026-09-23
---

## Pergunta 1 da fase

**Descreva como está sendo o processo de organização da sua equipe até agora — papéis, expectativas, primeiras decisões.**

No início do projeto, dividimos as responsabilidades principalmente por áreas. Duas pessoas ficaram responsáveis pelo backend, uma pelo Docker, uma pelo frontend, uma pelo banco de dados e outra pela documentação. Apesar dessa divisão, desde o começo existia a ideia de que todos poderiam atuar de forma flexível nas partes em que fosse necessário. Eu fiquei inicialmente responsável pelo backend e, nas primeiras semanas, também criei várias Agent Skills que atualmente são utilizadas no projeto. Depois disso, passei a trabalhar principalmente nas issues que me eram atribuídas pelo PO.

Eu já imaginava que a divisão inicial não permaneceria rígida durante todo o desenvolvimento. Isso me parece natural em trabalhos em grupo, porque algumas tarefas acabam exigindo mais esforço do que outras e as dificuldades não aparecem de maneira uniforme. Foi exatamente o que aconteceu: houve momentos em que o frontend precisou de apoio de outra pessoa e, em outra situação, uma tarefa de backend exigiu a participação de vários membros além de quem estava originalmente responsável. Para mim, esses remanejamentos não significaram que a divisão tinha falhado, mas que o grupo estava conseguindo se adaptar ao que o projeto exigia.

Particularmente, gostei da organização inicial e considerei justa a decisão de deixar quem assumiu os papéis de PO e Scrum Master com maior liberdade para acompanhar e auxiliar os desenvolvedores. Também considero que foi uma boa escolha separar essas funções. O PO conseguiu organizar bem as EPICs e Features, enquanto a Scrum Master pôde acompanhar o andamento do grupo e ajudar na organização do trabalho.

Entre as primeiras decisões importantes, procuramos adotar as práticas solicitadas na disciplina, incluindo Scrum e SDD. Também realizamos reuniões para discutir os requisitos e construir o Figma do projeto. Olhando para essas primeiras semanas, uma coisa que eu faria diferente seria realizar mais reuniões, mesmo que nem todos os integrantes pudessem participar. Perdemos bastante tempo procurando horários em que o grupo inteiro estivesse disponível e muitas vezes esse momento ideal simplesmente não existia. Eu manteria, porém, a prática de discutir e distribuir as issues em conjunto pelo GitHub, porque isso tem ajudado a evitar que o trabalho fique excessivamente concentrado em uma única pessoa. Também deixaria o PO ainda mais livre de issues de implementação para que pudesse se concentrar nas revisões de Pull Requests, que acabam sendo numerosas.

## Pergunta 2 da fase

**Que sensações ou pensamentos você tem tido em relação ao início desta disciplina e ao projeto que vocês vão desenvolver?**

Eu comecei a disciplina bastante animado com o projeto. É a primeira vez que participo da construção de uma aplicação que vejo como próxima de um contexto real de mercado e que poderá, de fato, ser utilizada por usuários. Saber que o que estamos desenvolvendo pode ajudar alunos da UnB dá um sentido muito maior às tarefas, porque não parece apenas um exercício feito para receber uma nota: existe a possibilidade de produzir algo que tenha utilidade real.

Ao mesmo tempo, no começo muita coisa parecia obscura e difícil de conectar. O vocabulário utilizado em engenharia de software, as práticas de desenvolvimento e as particularidades das tecnologias que começamos a utilizar formavam um conjunto de informações que eu ainda não conseguia enxergar como um todo. Isso, porém, também me despertava curiosidade. Eu queria entender melhor como engenheiros de software realmente trabalham no dia a dia e como todas aquelas ferramentas e processos se relacionavam durante a construção de um produto.

Uma questão que me causou certa frustração no início foi a forma como a Inteligência Artificial passou a ser utilizada no desenvolvimento. Eu imaginava que ela teria principalmente o papel de ajudante, mas em alguns momentos tive a sensação de que o agente estava se aproximando mais de um funcionário que conseguia executar grande parte da tarefa sozinho. Conforme o semestre avançou, percebi que a quantidade de conhecimentos envolvidos era grande demais para que eu dominasse tudo imediatamente e que, para conseguir acompanhar as tarefas atribuídas a mim, eu precisaria aprender a utilizar a IA de forma mais consciente.

Um momento concreto em que percebi isso ocorreu durante um trabalho relacionado à integração com o SIGAA. Em determinado ponto, havia 88 testes executados com sucesso, enquanto eram necessários 110 para que a issue pudesse ser considerada concluída. Eu não entendia inicialmente o motivo da diferença e precisei recorrer ao agente de IA para investigar e conseguir completar as verificações restantes. Esse episódio reforçou para mim que simplesmente aceitar o que o agente produz não é suficiente. Desde então, procuro ler o que foi implementado, pedir explicações detalhadas e entender as decisões tomadas antes de considerar uma tarefa concluída.

Hoje vejo a IA como uma ferramenta necessária para conseguir lidar com o volume e a variedade das tarefas do projeto, mas tento evitar utilizá-la no modo automático. Minha intenção é que ela acelere o trabalho sem substituir meu aprendizado. Por isso, tenho buscado compreender as implementações e pedir que os agentes expliquem o que fizeram e por que fizeram daquela maneira.

## Pergunta 3 da fase

**Que conhecimentos, ferramentas ou práticas você sente que já domina, e quais ainda são novidade para você neste momento?**

Antes de começar a disciplina, eu já possuía algum conhecimento de Python, Java e C, além de ter mais domínio de C++, embora essa linguagem não seja utilizada neste tipo de projeto. Também conseguia ler e compreender códigos de frontend escritos em HTML, CSS e JavaScript. Em relação ao Git e ao GitHub, considero que já possuía o conhecimento necessário para executar as tarefas básicas do projeto.

Por outro lado, banco de dados e Docker eram áreas praticamente novas para mim. Atualmente, Docker e FastAPI ainda estão entre os pontos em que sinto mais dificuldade. Como não fiquei diretamente responsável por essas partes, pretendo estudar com mais atenção o código produzido pelos colegas para entender melhor como essas tecnologias estão sendo utilizadas dentro do nosso próprio projeto.

Outros conceitos novos foram mais tranquilos de compreender e aplicar. Scrum, SDD e Agent Skills fizeram sentido para mim rapidamente. A parte de documentação também foi uma descoberta muito interessante. Gostei de perceber como o desenvolvimento pode ser planejado e descrito com bastante detalhe antes e durante a implementação. Essa forma minuciosa de organizar requisitos, decisões e trabalho combina bastante com a maneira como eu gosto de compreender um problema.

Entre tudo o que aprendi até agora, acredito que uma das maiores descobertas foi entender como aplicar Scrum de maneira concreta dentro do GitHub. Antes, eu conhecia ferramentas isoladas, mas passei a enxergar melhor como issues, organização do trabalho, responsabilidades e revisões podem representar o processo de desenvolvimento da equipe. Junto disso, também mudou bastante minha visão sobre o uso de agentes de IA. Passei a perceber a importância de fornecer contexto e regras por meio de recursos como skills, specs e `AGENTS.md`, em vez de tratar o agente apenas como alguém para quem se faz um pedido de código.

Essas experiências têm mudado minha visão sobre desenvolvimento de software. Estou começando a perceber que produzir software não é apenas programar, mas organizar pessoas, requisitos, decisões, documentação, ferramentas e processos de forma que todos consigam trabalhar sobre o mesmo contexto.
