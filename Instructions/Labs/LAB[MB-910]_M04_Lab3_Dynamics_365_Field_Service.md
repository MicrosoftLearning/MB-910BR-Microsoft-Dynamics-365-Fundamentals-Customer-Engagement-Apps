---
lab:
    title: 'Laboratório 4.3: Laboratório Capstone do Dynamics 365 Field Service'
    module: 'Módulo 4: Aprenda o básico do Dynamics 365 Field Service'
---

Módulo 4: Aprenda o básico do Dynamics 365 Field Service
========================

## Pratique o Laboratório 4.3 - Laboratório Capstone do Dynamics 365 Field Service

## Cenário do Laboratório

A empresa ABC é especializada na fabricação, comercialização, instalação e manutenção de equipamentos de segurança. Seus produtos incluem câmeras de segurança internas e externas, sensores de umidade e incêndio, serviços de monitoramento e muito mais. 

A empresa ABC usa aplicativos do Dynamics 365 para interagir com todos os seus clientes em diferentes áreas da sua organização, desde vendas até serviço. 

**Vendas e Marketing**

A empresa ABC comercializa para seus clientes residenciais diretamente por meio de campanhas de marketing direcionadas. Os clientes são direcionados com base em sua cidade e em outros fatores. Os materiais de marketing são enviados por email e, com base em sua interação com o email, são orientados de acordo. 

Embora alguns dos seus produtos menores sejam vendidos por varejistas, a maioria dos produtos é vendida diretamente aos consumidores por sua equipe interna de vendas.

Internamente, eles se concentram em duas áreas principais: 

- **Clientes residenciais:** Os clientes residenciais geralmente procuram componentes individuais ou uma solução para toda a casa. No geral, esses ciclos de vendas são mais curtos e se originam de mídias sociais, sites, referências ou contato direto do cliente em potencial. Como, de modo geral, os clientes residenciais estão mais focados em produtos específicos ou instalações menores, seus ciclos de vendas costumam durar alguns dias ou semanas. 

- **Clientes corporativos:** Os vendedores corporativos se concentram nos clientes que precisam de soluções de negócios mais especializadas e personalizadas. As vendas corporativas geralmente se estendem por vários locais com comunicação vinculada e, no geral, requerem vários recursos para concluir o projeto. Normalmente, esses ciclos de vendas são mais longos e têm muito mais peças móveis. 

É importante que todos os vendedores da empresa ABC tenham as ferramentas, os recursos e a orientação necessários, independentemente de sua área de foco ao vender para seus clientes. 

**Instalação do sistema:**

O processo de instalação do equipamento de segurança adquirido varia de acordo com o tipo de cliente para quem foi vendido. 

- **Clientes residenciais:** Como as instalações residenciais geralmente levam menos de um dia, elas são feitas por funcionários internos. Após a efetivação da venda, uma ordem de serviço é criada e um técnico qualificado é identificado e agendado para realizar a instalação. 

- **Clientes corporativos:** As implantações corporativas podem levar meses e exigem um gerente de projeto para supervisionar as operações do dia a dia. Isso inclui a criação de planos de projeto, definição de equipes de projeto e agendamento de recursos. 

**Serviço e suporte:**

Uma vez os sistemas instalados, a empresa ABC fornece suporte após a venda. Se um cliente tiver algum problema, ele pode entrar em contato com o suporte ao cliente. Um agente tentará trabalhar com o cliente remotamente para resolver o problema. Se o problema não puder ser resolvido remotamente, o agente de suporte pode escalar o problema para uma ordem de serviço que será agendada e trabalhada por um técnico de campo qualificado. 

## Objetivos

Normalmente, a empresa ABC envia técnicos de campo no local para trabalhar nos itens do cliente em um dos três cenários. 

- Quando um novo sistema de segurança é adquirido e precisa ser instalado.

- Quando um agente do help desk não consegue resolver um problema do cliente remotamente.

- Quando os contatos de um cliente usam diretamente para solicitar serviço no local. 

Recentemente, um cliente corporativo Active Transport, Inc. contatou o suporte sobre um problema que estava tendo com uma câmera em seu sistema de segurança. O técnico do help desk não conseguiu resolver o problema remotamente, portanto, um técnico de campo precisará ser expedido. Neste cenário, você fará o seguinte:

- Converter um registro de caso em ordem de serviço

- Agendar uma ordem de serviço

- Resolver uma ordem de serviço usando o aplicativo móvel. 

## Configuração do laboratório

  - **Tempo estimado**: 45 minutos

## Instruções

## Exercício 1: Criar um caso e encaminhá-lo para uma ordem de serviço 

### Tarefa 1: Criar um registro de caso

1. Se ainda não estiver aberto, abra o aplicativo **Dynamics 365 Field Service**. 

2. Usando a navegação no lado esquerdo da tela, selecione **Casos**. 

3. Na **Barra de Comandos**, selecione o botão **Novo** para criar um novo registro de caso.

4. Preencha o novo registro do caso da seguinte forma:

	- **Título do caso:** Câmera desligada

	- **Cliente:** Active Transport Inc.

	- **Origem:** Telefone

5. Selecione a guia **Serviço de Campo**

6. Defina o campo **Tipo de Incidente** como **Câmera desligada**.

7. Na **Barra de comando**, selecione o botão **Salvar e Fechar** para salvar e fechar o registro do caso. 

 

### Tarefa 2: Criar manualmente uma ordem de serviço

Voltaremos depois ao seu registro de caso criado. A seguir, vamos examinar como criar manualmente um registro de ordem de serviço. 

 

1. Na navegação à esquerda, selecione **Ordens de Serviço**.

2. Na **Barra de Comandos**, selecione o botão **Novo** para criar uma nova ordem de serviço.

3. Preencha os detalhes da ordem de serviço da seguinte forma:

	- **Conta de serviço:** Freios e engrenagens 

	- **Lista de preços:** Lista de preços padrão

	- **Tipo de incidente principal:** Ventilador não funcionando

	- **Tributável:** Não

4. Anote o número da ordem de serviço para garantir que esteja trabalhando com a ordem de serviço correta mais tarde. 

5. Selecione a guia **Configurações**.

6. Defina o campo **Território de Serviço** como **WA**.

7. Em **Preferências**, configure as preferências de tempo conforme mostrado a seguir:

	- **Hora de Início Prometida:** Hoje às 9:00

	- **Hora de Término Prometida:** Hoje às 11:00

8. Selecione **Salvar e Fechar** para salvar as alterações e sair da nova ordem de serviço.

 

### Tarefa 3: Gerar uma ordem de serviço a partir de um caso

Outra forma de gerar ordens de serviço é escalar registros de casos. Neste exemplo, escalaremos o registro de caso Câmera desligada que criamos anteriormente. 

 

1. Usando a navegação esquerda, selecione **Casos**. 

2. Abra o caso **Câmera Desligada** criado anteriormente. 

3. Na **Barra de Comando**, selecione o botão **Converter em Ordem de Serviço**. 

4. Quando a ordem de serviço estiver criada, clique no botão **OK** na tela pop-up para exibir os detalhes da ordem de serviço. 

5. Selecione a guia **Serviços** e verifique se os serviços **Inspecionar integridade do sistema** e **Inspecionar alcance de movimento** foram adicionados à ordem de serviço. **OBSERVAÇÃO:** Caso não os veja inicialmente, pressione F5 para atualizar a tela. 

6. Selecione a guia **Tarefa de Serviço** e verifique se as 4 tarefas foram adicionadas.

 

Ambas as ordens de serviço recém-criadas estão prontas para serem agendadas. 

## Exercício 2: Agendar itens com o Dynamics 365 Field Service  

### Tarefa 1: Agendar diretamente de uma ordem de serviço

1. Usando a navegação esquerda, selecione **Quadro de Horários**.

2. No canto superior direito da tela, defina a experiência **Novo Quadro de Horários** como **ON** (Ativado). 

3. Usando o campo de pesquisa **Pesquisar recursos**, insira o nome da sua conta de usuário. (Seu registro de recurso deve ser exibido.)

4. Na parte inferior da tela no painel de requisitos, selecione **Ordens de Serviço Não Agendadas**.  (Se o painel de requisitos não for exibido, selecione a seta na parte inferior da tela para expandi-lo.) 

5. Localize a ordem de serviço **Active Transport** que você criou a partir do registro de caso. (Lembre-se do número da ordem de serviço). 

6. Arraste o registro **Active Transport** e coloque-o em um intervalo aberto para o seu registro de usuário. 

7. Às vezes, talvez você precise reagendar uma ordem de serviço com base em conflitos técnicos ou outros itens. Isso pode ser feito facilmente pelos despachantes que utilizam o quadro de horários. 

8. Clique na caixa de pesquisa de recursos no quadro de horários (localizado logo acima da coluna do nome do recurso), digite **Brady** e localize a ordem de serviço que está agendada para **Brady Hannon** ainda hoje. 

9. **Clique com o botão direito** no item agendado. No menu exibido, selecione **Reatribuir**. Clique em usando a caixa de pesquisa e selecione seu registro de recurso.

 

 

### Tarefa 2: Agendar com o quadro de horários

1. Usando a navegação esquerda, selecione **Quadro de Horários**.

2. Usando o campo de pesquisa **Pesquisar recursos**, insira o nome da sua conta de usuário. (Seu registro de recurso deve ser exibido.)

3. Na parte inferior da tela no painel de requisitos, selecione **Ordens de Serviço Não Agendadas**.  (Se o painel de requisitos não for exibido, selecione a seta na parte inferior da tela para expandi-lo.) 

4. Localize a ordem de serviço **Active Transport** que você criou a partir do registro de caso. (Lembre-se do número da ordem de serviço). 

5. Arraste o registro **Active Transport** e coloque-o em um intervalo aberto para o seu registro de usuário. 

6. Às vezes, talvez você precise reagendar uma ordem de serviço com base em conflitos técnicos ou outros itens. Isso pode ser feito facilmente pelos despachantes que utilizam o quadro de horários. 

7. Clique na caixa de pesquisa de recursos no quadro de horários (localizado logo acima da coluna do nome do recurso), digite **Brady** e localize a ordem de serviço que está agendada para **Brady Hannon** ainda hoje. 

8. **Clique com o botão direito** no item agendado. No menu exibido, selecione **Recurso Substituto**. Clique na caixa Selecionar/Pesquisar, selecione seu registro de recurso e selecione **Reatribuir**
