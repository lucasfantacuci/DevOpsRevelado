[Anterior](https://github.com/lucasfantacuci/DevOpsRevelado/blob/master/README.md)


# O que  DevOps?


Devops é um processo para desenvolver, entregar e operar software. Tão simples quanto isso, você realmente não deveria subestimar o entendimento de o que DevOps realmente é. Existem muitas definições por ai emcima de prateleiras e na Internet sobre DevOps que são ou definições de interesse próprio de quem os propõe, ou na melhor das hipóteses, definições incompletas e confusas.


Algumas definições de DevOps dirigidas comercialmente acoplam DevOps altamente com certa ferramenta de build ou de delivery, ou à plataformas de infraestrutura cloud. Embora estas ferramentas e plataformas possam ser realmente úteis para alcançar suas metas de TI e metas organizacionais com DevOps, você não pode ainda acoplar à elas outra ferramenta (onde você usualmente não tem muito controle sobre ela pois você não à escreveu) ou você não pode migrar suas aplicações de software para uma infraestrutura de cloud e então anunciar que você e sua organização agora entrega com DevOps. Como alguns velhos desconhecidos diziam, os corvos riam disso. 


Outra definição equivocada, porém continua uma melhor variante para definir Devops, é ver DevOps como uma intersecção de trabalho e pessoas em uma organização de TI no qual trás desenvolvedores de software, testers de software, e operadores de software em produção juntos. Tendo dito isto, uma vez que você chegar ao final deste livro, você não poderá ajudar, mas irá ver o quão seca esta definição é.
 

A melhor maneira para definir DevOps é assemelhá-lo com desenvolvimento iterativo e ágil de software e com frameworks de melhoria de processos tais como Scrum, Lean, ITIL, IDEAL e Six Sigma DMAIC.


Embora Scrum, Lean, ITL, IDEAL e Six Sigma DMAIC possam servir como eficientes habilitadores para DevOps, DevOps não é para ser visto como um melhorado e combinado super conjunto destas metodologias e técnicas. A simples razão é que nenhuma destas metodologias e frameworks exceto Scrum foram introduzidos para especificamente resolver os problemas e servir a industria de software.


Muitas práticas e principios DevOps tem sido derivados do movimento Lean após elas terem sido adaptadas, experimentadas, validadas e refinadas para o desenvolvimento de software, entrega de software e operações. Mais que isto, DevOps emprestou e adaptou muitas tecnicas e filosofias do movimento de Delivery Continuo, Melhoria Toyota Kata, Teoria das Restrições, Manifesto ágil e Infraestrutura Ágil.


## Movimento de Entrega Contínua


Você habilita a entrega contínua através do pipeline de deploy. O Pipeline de deploy possui três missões importante: Visibilidade, Feedback, e Deploy contínuo.


- Visibilidade - Você faz com que todos os aspectos do sistema de entrega incluindo building, deploying, testes e releasing sejam visíveis para todos os membros do seu time e outros times, pois assim você promove colaboração em seu time, e você oferece transparência para seus clientes e stakeholders.


- Feedback - Você e seu time aprendem sobre os problemas tão cedo quanto eles ocorram, com isso vocês são capazes de corrigí-los rapidamente antes que vocês coloquem outro block sobre um bloco que já est em colapso.


- Deploy contínuo - Você faz o deploy e a release de qualquer versão do software para qualquer ambiente incluindo ambientes de teste e produção através de um processo totalmente automatizado.


## Melhoria Toyota Kata


Você usa a melhoria Toyota Kata como uma rotina para mover-se de uma situação atual para mover-se de uma situação corrente para uma nova situação de uma maneira criativa, direta e significativa. Este processo é baseado em um model de quatro partes: 


- Em sua consideração de uma grande visão ou uma direção aperfeiçoada...
- Você compreende as condições correntes.
- Então você define as proximas condições alvo.
- E por ultimo, você continuamente e iterativamente tenta se mover até a condição alvo. Durante este caminho você descobre obstáculos que necessitam ser trabalhados e você os resolve. 


Em contraste com outras abordagens de melhoria onde você tenta adivinhar o caminho e foca na implementação, com a melhoria Toyota Kata você aprende e constrói nas descobertas que ocorrem durante o caminho. Você e seus times usam a melhoria Toyota Kata para aprender assim como você se esforça para alcançar uma condição alvo, e vocês se adaptam baseado em que vocês estão aprendendo.


## Teoria das restrições


Em uma organização incluindo a sua que entrega qualquer tipo de software, existe sempre um conflito em andamento entre sua TI e o seu negócio. Rápidamente respondendo as necessidades de negócio enquanto continuamente assegurando ambiente de produção estável e previsível é uma troca continuamente enfrentada pela sua TI. Assumindo que você ja está completamente consciente que não existe risco na release de produção, em um sistema como o seu você não pode ser rápido o suficiente se você quer assegurar uma release em produção de baixo risco. E você no pode assegurar um release em produção de baixo risco se você quer rapidamente realizar seu código em seu ambiente de produção.


E você lida com este conflito quando : 


- Você divide sua organização de TI em vários pequenos, autonomos, independentes, autosuficientes e altamente colaborativos times (Você deveria começar a ver seus times como "unidades inteligentes" com missão).
- Você reduz o seu *batch size* (a quantidade do seu trabalho em progresso) dado à cada time.
- Você reduz o seu *lead time* (tempo requerido para converter ideias e requisitos em beneficios e funcionalidades rodando em ambiente de produção).
- Você constrói cíclos de feedbacks rápidos, confiantes e contínuos para assegurar prontidão para deployment.


## Manifesto Ágil


Agile Manifesto:
With DevOps you adhere to the cornerstones
defined by the agile manifesto:
• You respect individuals and interactions over
processes and tools.
• You respect working software over comprehensive
documentation.
• You respect customer collaboration over contract
terms and negotiation.
• You respect responding to change over following
a plan. 


## Agile Infrastructure:


Our organizations large and small including probably
yours are relying on hybrid cloud infrastructures,
combining public and private cloud with dedicated
servers. Therefore, you collect the rewards of
colocation security in combination with the flexibility
and scalability of public cloud.
Here’s some of major drivers why an agile infrastructure
is beneficial for DevOps:
• You pay for what you use with transparent and
simple pricing.
• You can quickly provision and de-provision your
test and production environments from your code
base (IaC - Infrastructure as Code).
• You have architectural flexibility.
• You can easily expand other geographies.
• You probably have better security
• You stay compliant without audits and additional
costs. 

CONCLUSION
In this section we explained you what DevOps is and
what it isn’t. For you we have also covered the major
movements and principles which DevOps was
derived from.
A small caveat: Like many agile practitioners have
been unfortunately doing in their agile practices
since years, you shouldn’t stick to any stone-grained
definition of DevOps to dictate how your particular
organization, your product, your service and most
importantly your team should use DevOps. There is
no one-size-fits-all solution. Neither in agile nor in
DevOps.
Never forget that it is all about learning, experimentation
and adaptation. As DevOps will do a lot of good
work for us, it is our role biggest duty as human
minds to identify our correct version and tone of
DevOps. This is what each and every successful
DevOps organization including Google, Amazon,
Facebook, Netflix and Apple have been doing

[Próximo](https://github.com/lucasfantacuci/DevOpsRevelado/blob/master/1-1-LEANMOVIMENT.md)
