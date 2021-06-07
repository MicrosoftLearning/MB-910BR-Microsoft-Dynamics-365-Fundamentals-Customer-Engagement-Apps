---
lab:
    title: 'Laboratório 2.3: Laboratório Capstone do Dynamics 365 for Sales'
    module: 'Módulo 2: Aprenda os conceitos básicos do Dynamics 365 for Sales'
---

Módulo 2: Aprenda os conceitos básicos do Dynamics 365 for Sales
========================

## Laboratório prático 2.3 - Laboratório Capstone do Dynamics 365 for Sales

## Cenário do laboratório

A ABC Company é especializada na fabricação, venda, instalação e manutenção de equipamentos de segurança. Seus produtos incluem câmeras de segurança internas e externas, sensores de incêndio e umidade, serviços de monitoramento etc. 

A ABC Company usa aplicativos do Dynamics 365 para interagir com todos os clientes em diversas áreas da organização, desde vendas até manutenção. 

**Vendas e Marketing**

A ABC Company usa campanhas de marketing segmentadas para anunciar produtos e serviços diretamente a seus clientes residenciais. Os clientes são segmentados em termos de cidade e outros fatores. Os materiais de marketing são enviados por email e direcionados conforme as interações com os emails. 

Embora alguns produtos menores sejam vendidos por varejistas, a maioria é vendida diretamente aos clientes por equipes de vendas internas.

Internamente, o foco da empresa é em duas áreas principais: 

- **Clientes residenciais:** Clientes residenciais buscam geralmente componentes individuais ou compram uma solução residencial completa. Esses ciclos de vendas são geralmente mais curtos e provêm de redes sociais, sites, indicações ou de contato direto com o prospecto. Como os clientes residenciais focam mais em produtos específicos ou instalações menores, os ciclos de vendas geralmente duram poucos dias ou semanas. 

- **Clientes empresariais:** Os vendedores empresariais focam em clientes com necessidades mais específicas e soluções comerciais personalizadas. As vendas empresariais geralmente abrangem várias localizações com comunicação interligada e exigem vários recursos para conclusão do projeto. Esses ciclos de vendas são geralmente mais longos e têm muito mais peças móveis. 

É importante que todos os vendedores da ABC Company tenham as ferramentas, os recursos e as orientações necessárias para vender aos clientes, independentemente da área de foco. 

**Instalação de sistema:**

O processo de instalação para equipamentos de segurança adquiridos varia de acordo com o tipo de cliente que os comprou. 

- **Clientes residenciais:** Como as instalações residenciais geralmente levam menos de um dia, elas são feitas por funcionários internos. Após a realização de uma venda, a empresa cria uma ordem de serviço e designa e agenda um técnico qualificado para fazer a instalação. 

- **Clientes empresariais:** Implantações empresariais podem levar meses e exigem um gerente de projetos para supervisionar as operações diárias. Isso inclui criar planos de projeto, definir equipes de projeto e programar recursos. 

**Atendimento e suporte:**

Após a instalação dos sistemas, a ABC Company presta suporte de pós-venda. Se um cliente tiver algum problema, ele poderá contatar o suporte ao cliente. Um agente tentará ajudá-lo remotamente para resolver o problema. Se não for possível resolvê-lo, o agente de suporte criará uma ordem de serviço do problema aos cuidados de um técnico de campo qualificado para agendamento e resolução.  

## Objetivos

Você trabalha como representante de vendas residenciais na ABC Company. Embora muitos de seus clientes potenciais provenham de eventos patrocinados pela empresa, campanhas de marketing e listas adquiridas, você ainda recebe consultas diretamente de clientes. Quando recebe essas consultas, você precisa registrar manualmente o cliente potencial e gerenciá-lo pelo ciclo de vida de vendas. 

Recentemente, você atendeu uma pessoa chamada Piper Smith. Tem ocorrido uma série de roubos em seu bairro, e ela gostaria de adquirir alguns equipamentos de segurança residencial. Você fará o registro do cliente potencial em nome de Piper no sistema, tentará qualificá-la e fará seu avanço pelo ciclo de vendas. 

Depois de concluir o laboratório, você terá feito isto:

- Registrar um cliente potencial no Dynamics 365 for Sales

- Qualificar e converter um cliente potencial em uma oportunidade de vendas.

- Gerenciar atividades diárias associadas a uma oportunidade. 

- Adicionar uma cotação a uma oportunidade. 

- Fechar uma oportunidade de vendas. 

- Gerar uma fatura. 

## Configuração do laboratório

  - **Tempo estimado**: 30 minutos

## Instruções
  
## Exercício 1: Crie e qualifique um cliente potencial no Dynamics 365 for Sales


### Tarefa 1: Crie um novo cliente potencial

1. Se necessário, abra um navegador Privado e acesse [Https://home.Dynamics.com](https://home.dynamics.com/) 

2. Quando solicitado, faça login com as credenciais de usuário que seu instrutor forneceu. 

3. Na lista de aplicações exibidas, selecione **Hub de Vendas.**

4. Use a área de navegação à esquerda da tela e selecione **Clientes Potenciais**. 

5. Para exibir todos os clientes potenciais que existem no sistema, clique na seta para baixo ao lado de **Meus Clientes Potenciais em Aberto**. No menu exibido, selecione **Clientes Potenciais Ativos**. 

6. Para voltar à lista de clientes potenciais, clique na seta para baixo ao lado de Clientes Potenciais Ativos e, no menu exibido, selecione **Meus Clientes Potenciais em Aberto**. 

7. Em seguida, crie um novo cliente potencial em nome de Piper Smith. Na exibição **Meus Clientes Potenciais em Aberto**, selecione o botão **Novo** na barra de comandos.

8. Preencha o registro do novo cliente potencial da seguinte maneira:

	- **Tópico:** Procurando equipamentos de segurança - "Seu Nome"

	- **Nome:** Piper

	- **Sobrenome:** Smith - "Suas iniciais"

	- **Telefone celular:** 888 555-1762

	- **Email:** piper@sample.com

	- **Endereço 1:** 1989 191<sup data-htmlnode="">st</sup> Ave N

	- **Cidade:** Seattle

	- **Estado/Província:** WA

	- **CEP/Código postal:** 98001 

9. Selecione o botão **Salvar** na barra de comandos para salvar o novo cliente potencial e deixá-lo em aberto.

10. Observe o fluxo de processo comercial **Cliente Potencial para Oportunidade** na parte superior do registro. Clique no **Estágio Qualificar** para selecioná-lo. Preencha o estágio da seguinte maneira:

	- **Período de Compra:** Este trimestre

	- **Orçamento Estimado:** 10000 

	- **Processo de Compra:** Individual

	- **Identificar Tomador de Decisões:** Concluído

11. Clique em **X** na janela do estágio para fechá-la. 

12. Acesse a **Linha do tempo** de registro no meio da tela e clique no **Ícone do Sinal de Mais** para incluir uma nova atividade. 

13. No menu exibido, selecione **Chamada Telefônica**.

14. Na tela Criar rápido: Chamada Telefônica, preencha os dados da seguinte maneira:

	- **Assunto:** Procurando equipamentos de segurança residencial

	- **Telefone:** 888 555-1762

	- **Direção:** Recebida

	- **Descrição:** Após alguns incidentes em seu bairro, ela resolveu adquirir um sistema de segurança. 

15. Clique no botão **Salvar e Fechar**.

16. Observe que a atividade **Procurando equipamentos de segurança residencial** agora está exibida na **Linha do Tempo** de registro. Posicione o cursor sobre a atividade e selecione a atividade de fechamento **Ícone de Marcação** para marcar a chamada telefônica como concluída. 

17. Na janela **Fechar Chamada Telefônica**, verifique se o status definido é **Concluído** e selecione o botão **Fechar**.

 

**IMPORTANTE:** Não feche o registro de cliente potencial. Deixe-o aberto para ser usado na próxima tarefa. 

 

### Tarefa 2: Qualifique o cliente potencial como uma oportunidade

Após visitar Piper, você identificou que há interesse suficiente da parte dela para justificar o avanço no processo e que temos produtos e serviços que a beneficiariam. Em seguida, você qualifica o registro de cliente potencial. Isso cria um registro de Oportunidade relacionado e avança para o próximo estágio do processo de vendas Cliente Potencial para Oportunidade. 

1. Nas **Barra de Comandos**, selecione o botão **Qualificar**. 

2. Depois de qualificar o cliente potencial, o sistema cria um novo registro de Oportunidade, e o processo comercial avança para o estágio **Desenvolver**. Selecione o estágio **Qualificar** para exibir o registro de cliente potencial original. 

3. Selecione o estágio **Desenvolver** para retornar à oportunidade.

4. Clique no botão **Salvar e Fechar** para fechar o registro de Oportunidade criado. 

 

 

## Exercício 2: Gerencie uma oportunidade de vendas no Dynamics 365 for Sales

Agora que qualificamos com êxito o cliente potencial como uma oportunidade, é hora de gerenciar a oportunidade pelo ciclo de vida.

### Tarefa 1: Gerencie uma oportunidade de vendas e crie uma cotação 

1. Use a área de navegação à esquerda da tela e selecione **Oportunidades**. 

2. Clique na seta de lista suspensa ao lado da exibição **Minhas Oportunidades em Aberto**. No menu exibido, selecione **Oportunidades em Aberto**.

3. Na barra de comandos, selecione Mostrar Gráfico. Observe que o gráfico Principais Clientes é exibido com base na tabela Oportunidade. 

4. Clique na seta de lista suspensa ao lado de Principais Clientes. No menu exibido, selecione **Pipeline de Vendas**.

5. Selecione a parte Qualificar do Funil. Observe que a lista de Oportunidades muda para exibir aquelas que estão no estágio de qualificação. 

6. Clique em qualquer lugar do espaço em branco do gráfico para exibir novamente todas as oportunidades em aberto. 

7. Clique na seta de lista suspensa ao lado da exibição **Oportunidades em Aberto**. No menu exibido, selecione **Minhas Oportunidades em Aberto**. O item **Procurando Equipamentos de Segurança - Suas Iniciais** provavelmente será a única ocorrência, e o gráfico deve refletir isso. 

8. Na **Barra de Comandos**, selecione o botão **Ocultar Gráfico**. 

9. Abra o item **Procurando Equipamentos de Segurança - Suas Iniciais** que você criou anteriormente ao qualificar o cliente potencial. Observe que o registro já está na fase **Desenvolver**, já que foi criado com base em um cliente potencial qualificado anteriormente.  

10. No cabeçalho da oportunidade **Procurando Equipamentos de Segurança - Suas Iniciais** na parte superior do registro, selecione a seta para baixo ao lado do campo de proprietário. 

11. Preenche da seguinte maneira:

	- **Data de Fechamento Est.:** Amanhã

	- **Receita Est.:** 12.500,00

12. Acesse a **Linha do tempo de Registro** no meio da tela e clique no **Ícone do Sinal de Mais** para incluir uma nova atividade. 

13. No menu exibido, selecione **Compromisso**.

14. Na tela **Criar Rápido: Compromisso**, preencha da seguinte maneira:

	- **Assunto:** Reunião Rápida - “Suas Iniciais”

	- **Localização:** Online

	- **Hora de Início**: Amanhã, às 10h

	- **Hora de Término:** Amanhã, às 10h30

15. Na Barra de Comandos, selecione **Salvar e Fechar**

16. No fluxo de processo comercial Cliente Potencial para Oportunidade, selecione o estágio **Desenvolver**. Observe que é necessário Identificar Partes Interessadas e Concorrentes.

17. Clique no **X** na janela do estágio para fechá-la e continuar o trabalho. 

18. Na subgrade **Partes Interessadas**, observe que **Piper** já está definida como parte interessada. 

19. Na subgrade Equipe de Vendas, selecione a **Elipse Vertical**. No menu exibido, selecione **Nova Conexão**. 

20. No campo **Pesquisar**, insira o texto **Sistema** e selecione o registro **Administrador do Sistema**. Depois de terminar, clique no botão **Adicionar**. O Administrador do Sistema deve ser exibido na equipe de vendas. Caso contrário, selecione o botão **Atualizar** na barra de comandos. 

21. Na subgrade Concorrentes, selecione a **Elipse Vertical**. No menu exibido, selecione **Adicionar Concorrente Atual**. 

22. Na tela **Registro de Busca**, selecione **Novo** e depois **Concorrentes**.

23. Na tela Criar Rápido: **Concorrente**, preencha o campo **Nome** com **Coho Security - “Suas Iniciais”**.

24. Selecione o botão **Salvar e Fechar**.

25. Confirme se o registro Coho Security recém-criado está selecionado e clique no botão **Adicionar**. 

26. Clique no estágio **Desenvolver** no fluxo de processo comercial **Cliente Potencial para Oportunidade** e defina as etapas **Identificar Partes Interessadas** e **Identificar Concorrentes** para **Concluído**. 

27. Clique no botão **Próximo Estágio** para avançar ao estágio **Propor**.

28. No estágio **Propor**, marque **Identificar Equipe de Vendas** como **Concluído**.

29. Clique no **X** no estágio Propor para fechar essa janela. 

30. No registro de oportunidade, selecione a guia **Cotações**. 

31. Na subgrade Cotações, clique no botão **Nova Cotação**.

 

**IMPORTANTE:** Como esses ambientes têm vários apps próprios instalados, é possível que o formulário de cotação exibido no momento não seja o correto para a função de vendas. Se o texto abaixo do nome da cotação **Procurando Equipamentos de Segurança - Suas Iniciais** for: **Cotação. Cotação**, o formulário correto será carregado. Se for **Cotação. Informações de Serviço de Campo**, será necessário trocá-lo. Se isso for necessário, selecione a seta de lista suspensa ao lado de **Cotação. Informações de Serviço de Campo**. No menu exibido, selecione **Cotação**. 

 

### Tarefa 2: Gerencie uma cotação

Agora que já tem uma cotação relacionada, você a prepara para apresentar a um cliente. Em situações normais, provavelmente incluiríamos produtos no registro de cotação antes de enviar a um cliente. Como estamos trabalhando em ambientes compartilhados, vamos pular a inclusão de linhas na cotação e passaremos para seu envio. 

1. Na **Barra de Comandos**, selecione o botão **Ativar Cotação** para ativá-la. 

2. É necessário selecionar uma Lista de Preços para anexar à Oportunidade.  Em **Lista de Preços** no painel esquerdo, selecione o ícone Procurar e depois na opção **Lista de Preços Padrão**.

3. Agora que criamos a cotação, vamos atualizar o registro de oportunidade para refletir os novos dados. No registro de Cotação, selecione **Procurando Equipamentos de Segurança** – **“Seu Nome”** no campo **Oportunidade** na seção **Informações de Vendas**. O registro de oportunidade deve abrir na tela. 

3. No registro de oportunidade, selecione o estágio **Propor**. 

4. Marque **Desenvolver Proposta**, **Concluir Revisão Interna**, e **Apresentar Proposta** como **Concluído** e clique no botão **Próximo Estágio** para avançar ao estágio **Fechar**. 

5. No estágio **Fechar**, marque **Concluir Proposta Final**, **Apresentar Proposta Final**, **Enviar Agradecimento** e **Arquivar Avaliação** como **Concluído**. 

6. Defina **Confirmar Data de Decisão** para **Data de hoje**. 

7. Clique no botão **Finalizar**. 

8. Selecione o **X** na janela do estágio Fechar para fechá-la. 

9. Selecione a guia **Cotações**. 

10. Abra a cotação **Procurando Equipamentos de Segurança - Suas Iniciais**. 

11. Na **Barra de Comandos**, selecione o botão **Criar Pedido**.

12. Na janela Criar Pedido, preencha da seguinte maneira:

	- **Motivo do Status:** Ganho

	- **Data de Ganho:** Data de hoje

	- **Fechar Oportunidade:** Sim

	- **Calcular Receita Real das Cotações:** Não

	- **Receita Atual:** $ 12.500

13. Selecione o botão **OK** 

O sistema cria um novo pedido de vendas relacionado ao item. E fecha o registro de cotação e o registro de oportunidade relacionado. Depois de tudo concluído, o pedido será aberto na tela. Deixe o pedido aberto. 

###  

### Tarefa 3: Gerencie o pedido e a fatura

Agora que criamos um pedido de vendas, vamos fechar o pedido e gerar a fatura. Em situações normais, incluiríamos produtos do registro de cotação no pedido de vendas. Como estamos trabalhando em ambientes compartilhados, vamos continuar como se já houvesse produtos anexos. 

 

1. Na **Barra de Comandos**, selecione o botão **Preencher Pedido**. 

2. Na tela Preencher Pedido, preencha da seguinte maneira:

	- **Motivo do Status:** Completo

	- **Data de Preenchimento:** Data de hoje

3. Selecione o botão **Preencher**. 

4. Na **Barra de Comandos** do pedido, selecione o botão **Criar Fatura**. 

5. Depois de abrir o registro de Fatura, selecione **Fatura Paga*.
