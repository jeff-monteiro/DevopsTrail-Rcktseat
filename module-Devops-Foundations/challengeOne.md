# Práticas Devops

* Separando por partes os problemas podemos implementar melhor cada melhoria.

    - No processo atual temos um time inteiro majoritariamente capacitado com as mesmas tecnologias, e apenas um profissional com o conhecimento específico. Nesse sentido, é nítido que a **Tech** possui dois projetos em andamento e um deles é um sistema legado, causando centralização e dependência de conhecimento.

        _Para que esse problema seja solucionado, seria interessante separar parte do time que já domina mais tecnologias e traçar um plano de aprendizado da tecnologia específica do sistema legado a fim de disseminar o conhecimento do sistema legado e descentralizar a força da mão de obra de um único profissional_

    - Nesses dois projetos da **Tech** foi percebida uma demora considerável no processo de entrega do código ao deploy, logo em seguida, monitoramento. 
    
       _Para esse cenário, podemos automatizar o processo de entrega do código, testes e deploy da aplicação, o que pode facilitar o monitoramento também usando alguma ferramenta deobservabilidade e monitoramento integrados a pipeline de cada ambiente_


    * Com essas abordagens podemos reduzir consideravelmente o tempo médio entre a entrega do código e o deploy. Com a integração de testes automatizados, podemos assumir que os sucesso de deploys tende a melhorar, assim como o número de incidentes tende a cair. O tempo médio de recuperação da aplicação terá melhoria considerável ao inserirmos o monitoramento da aplicação integrados, com envio de mensagens. Existem várias abordagens que podem facilitar cada vez mais no processo de automação e agilidade.