[Sumário](https://github.com/lucasfantacuci/DevOpsRevelado/blob/master/README.md)


[Anterior](https://github.com/lucasfantacuci/DevOpsRevelado/blob/master/CHAPTER03/3-3-YOUBUILDSYSTEMSTOACHIEVEBUSINESSGOALS.md)


## 3.4 - Você cria com qualidade e monitoramento


Você cria ciclos de *feedbacks* amplificados, confiáveis e rápidos em todos os estágios do ciclo de vida da sua entrega e operações de software. Qualidade não é um monopólio no qual pertence a um determinado time, todo mundo se esforça para construir com qualidade. A fim de ter certeza que você tem feito corretamente o seu trabalho, você não pergunta para outra pessoa a permissão para implantar o seu código em produção. Você confia em seu time com *peer reviews* do seu design, cdigo, testes e infraestrutura.


Você sempre constrói automatização de testes e monitoramento (telemetria) para todas atividades passíveis de teste e métricas. Você está consciente que se uma funcionalidade merece seu tempo para ser codificada e entregue, ela também merece automatização de testes continuos, confiáveis, ŕápidos e consistentes. Mais além, ela merece monitoramento contínuo e ser construida com sistema de análises em seu *software* para validar se o que você ganha com esta funcionalidade vai de encontro com o porque você construíu antes de outras. Em todos os ambientes incluindo produção e não produção.   


Toda integração do seu repositório de código automaticamente adapta, reestrutura ou se necessário, reconstrói seu ambiente operacional, recria automaticamente os aplicativos afetados e, finalmente, executa todos os testes automatizados para validar as funcionalidades existentes e a proposta da sua última integração de código. Uma vez que a validação obteve sucesso, as mesmas mudanças são automaticamente adaptadas para a sua produção.


Você cria na suas aplicações sistemas para análise e telemetria para continuamente monitorar e gravar eventos chave em seu *software* e em seu ambiente operacional. A métricas chave (tais como número de pedidos, numero de erros, tamanho das queries no banco de dados, entre muitos outros) são constantemente gravados e apresentados em tempo real, então  só uma questão de minutos, se não segundos antes que o seu time descubra um impacto negativo disparado por uma implantação. E isto é o porque ciclos de feedbacks rápidos so vitais para ter o seu trabalho feito rapidamente.


[Próximo](https://github.com/lucasfantacuci/DevOpsRevelado/blob/master/CHAPTER03/3-5-THANKSTOERRORSYOULEARNANDTEACH.md)
