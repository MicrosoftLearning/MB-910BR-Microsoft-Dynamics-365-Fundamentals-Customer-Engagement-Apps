---
lab:
    title: 'Laboratório 3.3: Laboratório Capstone do Dynamics 365 for Customer Service:'
    module: 'Módulo 3: Aprenda os conceitos fundamentais do Dynamics 365 for Customer Service'
---

Módulo 3: Aprenda os conceitos fundamentais do Dynamics 365 for Customer Service
========================

## Laboratório de prática 3.3 - Laboratório Capstone do Dynamics 365 for Customer Service

## Cenário do laboratório

A empresa ABC se especializa em fabricar, vender, instalar e dar manutenção em equipamentos de segurança. Seus produtos incluem câmeras de segurança internas e externas, sensores de umidade e incêndio, serviços de monitoramento e mais. 

A empresa ABC usa os aplicativos Dynamics 365 para envolver-se com todos seus clientes por todas as diferentes áreas de sua organização, desde vendas até serviço. 

**Vendas e Marketing**

A empresa ABC anuncia para os clientes residenciais diretamente por meio de campanhas de marketing direcionadas. Os clientes são direcionados com base nas cidades em que estão e outros fatores. O material de marketing é enviado por e-mail e, com base na interação deles com o e-mail, direcionado respectivamente. 

Enquanto alguns de seus produtos menores são vendidos por varejistas, a maioria é vendida diretamente aos consumidores pela equipe de vendas interna.

Internamente, eles se concentram em duas principais áreas: 

- **Clientes residenciais:** Esses clientes procuram tipicamente por componentes individuais ou comprar uma solução doméstica completa. Esses ciclos de vendas são normalmente mais curtos e se originam de mídias sociais, websites, indicações ou contato direto do cliente em potencial. Como os clientes residenciais estão normalmente mais focados em produtos específicos ou instalações menores, os ciclos de vendas para eles normalmente duram alguns dias ou semanas. 

- **Clientes empresariais:** Os vendedores empresariais se concentram em clientes que precisam de soluções de negócios mais especializadas e sob medida. As vendas empresariais normalmente abrangem várias localizações com comunicação vinculada, e frequentemente exigem múltiplos recursos para concluir o projeto. Normalmente, esses ciclos de vendas são mais longos e têm muitas mais partes móveis. 

É importante que todos os vendedores da empresa ABC tenham as ferramentas, recursos e orientação necessários, independentemente de sua área de foco enquanto vendem a seus clientes. 

**Instalação do sistema:**

O processo de instalação para equipamento de segurança adquirido varia com base no tipo de cliente para quem foi vendido. 

- **Clientes residenciais:** Como instalações residenciais normalmente precisam de menos de um dia, são feitas por funcionários internos. Depois que a venda é feita, uma ordem de serviço é criada e um técnico qualificado é identificado e agendado para realizar a instalação. 

- **Clientes empresariais:** Implantações empresariais podem levar meses e exigem um gerente de projetos para supervisionar as operações diárias. Isso inclui criar planos de projeto, definir equipes de projeto e agendar recursos. 

**Serviço e suporte:**

Assim que os sistemas são instalados, a empresa ABC oferece suporte após a venda. Se um cliente tiver um problema, ele pode entrar em contato com o suporte ao cliente. Um agente tentará trabalhar com o cliente remotamente para resolver seu problema. Se seu problema não puder ser resolvido remotamente, o agente de suporte pode escalar o problema para uma ordem de serviço que será agendada e trabalhada por um técnico de campo qualificado. 

## Objetivos

Muitas vezes, os clientes podem encontrar problemas com seus equipamentos. Quando forem encontrados problemas, eles são informados ao help desk da empresa ABC. Os problemas podem ser informados de várias maneiras. Em alguns casos, o equipamento pode informar problemas de modo proativo. À medida que os problemas são informados, os agentes tentam resolvê-los remotamente. Se isso não funcionar, um técnico de campo será enviado para resolver o problema. Você tem corrigido muitos sensores que pararam de funcionar recentemente. Você percebeu que isso se deve a um bug de software. Você deseja criar um artigo de conhecimento que outros agentes possam usar como referência quando encontrarem o mesmo problema. 

Como agente de help desk, você é responsável por trabalhar em problemas informados por clientes. Você recentemente atendeu um telefonema de Piper Smith. Piper está informando que um dos sensores em seu sistema não está funcionando. Você precisa registrar a chamada dela e tentar localizar uma resolução para seu problema. 

Após concluir o laboratório, você terá:

- Criado um artigo de conhecimento 

- Gerenciado casos usando o hub de atendimento ao cliente.

- Criado e registrado um caso. 

- Gerenciar um registro de caso ao longo do ciclo de vida. 

## Configuração do laboratório

  - **Tempo estimado**: 45 minutos

## Instruções

## Exercício 1: Criar e publicar um artigo de conhecimento

### Tarefa 1: Criar um artigo de conhecimento

1. Se ainda não estiver aberto, abra o aplicativo **Dynamics 365 for Customer Service Hub**. 

2. Usando a navegação no lado esquerdo da tela, selecione **Artigos de conhecimento**. 

3. Para ver facilmente quais artigos estão em diferentes estágios, selecione a seta suspensa ao lado de **Meus artigos ativos**. 

4. Selecione **Artigos de rascunho**. Provavelmente você verá dois artigos no modo de rascunho.

5. Use o seletor de exibição para selecionar **Artigos aprovados**. Você deve ver pelo menos um artigo aprovado. 

6. Use o seletor de exibição para alternar de volta para **Meus artigos ativos**

7. Na **Barra de comando**, selecione o botão **Novo**. 

8. Conclua o artigo como se segue:

	- **Título:** O sensor não está funcionando - Suas iniciais

	- **Palavras-chave:** Sensor, danificado, não funcionando

	- **Descrição:** Ajuda a trabalhar em cenários onde um sensor não está funcionando. 

9. Digite o seguinte texto na caixa **Designer de conteúdo**.   

	O sensor não está funcionando atualmente

	Quando o sensor não está funcionando como deveria, faça o seguinte:

	1. Localize e substitua as baterias no dispositivo. 

	2. Pressione e mantenha pressionado o botão liga/desliga por 3 segundos. 

	3. O dispositivo abrirá em modo de administrador. 

	4. Pressione e mantenha pressionado o botão do par até que a luz mude de vermelha para azul. 

	5. Pressione o botão de redefinição. 

	Assim que o dispositivo reiniciar, ele estará on-line novamente. 

10. No editor de contexto, selecione o texto “O sensor não está funcionando atualmente”

11. Altere o tamanho da fonte para **22** e selecione o botão **Negrito**. 

12. Na **Barra de comando**, selecione o botão **Salvar** para salvar o artigo de conhecimento e deixá-lo aberto. 

13. No **Novo processo**, selecione o estágio do **Autor**, defina o campo **Assunto do artigo** para **Serviço**. 

14. Defina o campo **Marcar para revisão** como **Concluído**.

15. Selecione o botão **Próximo estágio** para avançar ao estágio de **Revisão**.

16. Na **Barra de comando**, selecione o botão **Salvar e fechar** para salvar suas alterações e fechar o artigo.

 

### Tarefa 2: Gerenciar um artigo ao longo do processo de aprovação

Na maioria das organizações, depois que o autor do artigo cria o registro, ele passa por um processo de aprovação antes que fique disponível. Na maior parte do tempo isso é feito por um indivíduo diferente. Neste exemplo, agiremos como um aprovador. 

1. Nos Artigos de conhecimento, alterne a exibição para **Artigos propostos** para ver quais artigos precisam de aprovação. 

2. Abra o artigo **Sensor não está funcionando - suas iniciais** que acabou de criar.

3. Em **Novo processo**, selecione o estágio de **Revisão**. Defina o campo **Revisão** como **Rejeitado**.

4. Na tela de Artigo de conhecimento rejeitado, digite o texto **Essas etapas não funcionam quando tento replicá-las.**

5. Selecione o botão **Rejeitar**

6. Selecione **Salvar e Fechar** para fechar o registro do artigo.

7. Usando o **seletor de exibição**, altere a visualização para **Meus artigos ativos**. 

8. Abra o registro **Sensor não está funcionando - suas iniciais**.

9. Assim que o registro for aberto, selecione a guia **Resumo**. 

10. Na **Linha do tempo** do registro, observe uma nota que indicou que o artigo foi rejeitado e o motivo da rejeição. 

11. Selecione a guia **Conteúdo**

12. No campo **Conteúdo**, posicione o cursor antes da palavra **Pressionar** na etapa 5. 

13. Pressione a tecla **Enter**. 

14. Digite o texto e pressione o botão **Confirmar**. 

15. Na **Barra de comando**, selecione o botão **Salvar e Fechar**.

16. Use o **Seletor de exibição** e alterne a exibição para **Artigos propostos**.

17. Abra o artigo **Sensor não está funcionando - suas iniciais**. 

18. No fluxo de processo empresarial **Novo processo**, selecione o estágio de **Revisão**.

19. Alterne o Status para **Aprovado**. 

20. Você será solicitado a confirmar a aprovação do artigo; selecione **OK**. 


### Tarefa 3: Aprovar o artigo de conhecimento

Agora que o artigo foi aprovado, vamos publicá-lo para que ele fique disponível para pessoas trabalhando em casos. 

1. Clique no botão **Próximo estágio** para avançar ao estágio de **Publicação**. 

2. Marque **Definir associações de produto** como **Concluído**. 

3. Defina a **Data de validade** para **um ano a partir de hoje às 0:00**. 

4. Clique no botão **Finalizar** para completar o processo. 

5. Na **Barra de comando** para o artigo, clique no botão **Publicar**. 

6. Confirme se o seguinte está selecionado:

	- **Publicar:** Agora

	- **Status de publicação:** Publicado

	- **Data de validade:** Um ano a partir de hoje às 0:00

	- **Estado da validade:** Expirado

	- **Status da validade:** Expirado

7. Clique no botão **Publicar** para publicar o artigo.


## Exercício 2: Gerenciar um caso de suporte ao longo do ciclo de vida


### Tarefa 1: Criar e gerenciar um caso

1. Se ainda não estiver aberto, abra o aplicativo **Dynamics 365 for Customer Service Hub**. 

2. Usando a navegação no lado esquerdo da tela, selecione **Painéis de controle**. Isso abrirá o painel de **Nível 1**. 

3. Na **Barra de comando**, selecione o botão **Exibir filtros de visual**.

4. No gráfico **Mix de casos (por origem)**, selecione **Telefone**. Observe que o Filtro de casos exibe apenas os Casos telefônicos.  

5. Selecione **Apagar tudo** para apagar o filtro.

6. No gráfico **Casos por prioridade**, selecione **Alta**. Observe que a lista de casos será ainda mais filtrada para incluir casos de Alta prioridade.  

7. Clique no primeiro caso que aparece na lista para abri-lo. Depois que o caso abrir, clique no botão **Salvar e Fechar** na barra de comando para fechar o caso e retornar ao painel de **Nível 1**. 

8. Remova qualquer filtro aplicado selecionando **Apagar tudo**. 

9. Painéis de controle adicionais oferecem mais detalhes sobre a carga de casos atual. Você pode trabalhar com outros painéis de controle usando o seletor de painéis. Troque o painel de **Painel de nível 1** para **Painel de nível 2**. 

 

Agora que você está familiarizado com algumas das diferentes visualizações e painéis, vamos criar um registro de caso para auxiliar Piper com o problema dela.

 

10. Usando a navegação no lado esquerdo da tela, selecione **Casos**. 

11. Na **Barra de comando**, selecione o botão **Novo** para criar um registro de caso.

12. Conclua o novo registro de caso como se segue:

	- **Título do caso:** O sensor não está funcionando - Suas iniciais

	- **Cliente:** Piper Smith

	- **Origem:** Telefone

	- **Descrição:** Piper está informando que um dos sensores que ela recebeu não está funcionando adequadamente. 

13. Selecione o botão **Salvar** para salvar o registro e deixe-o aberto. 

14. Usando a **Linha do tempo do registro**, selecione o **Ícone de sinal de mais** para criar uma atividade. 

15. No menu exibido, selecione **Chamada telefônica**.

16. No formulário **Criação rápida: Chamada telefônica**, complete a atividade como se segue:

	- **Assunto:** Retornar chamada para Piper

	- **Direção:** Saída

	- **Número de telefone:**  888 555-1762

	- **Duração:** 15 minutos.

17. Clique no botão **Salvar e Fechar**. 

18. Em **Telefone para Processo do caso**, selecione o estágio **Identificar**.

19. Clique no botão **Próximo estágio** para avançar ao estágio **Pesquisa**. 

20. Clique no **X** na janela flutuante do estágio **Pesquisa** para remover a janela e poder continuar trabalhando. 

21. Usando a **Linha do tempo do registro**, selecione o **Ícone de sinal de mais** para criar uma atividade. 

22. No menu exibido, selecione **Tarefa**.

23. No formulário **Criação rápida: Chamada telefônica**, complete a atividade como se segue:

	- **Assunto:** Pesquisar o problema da Piper

	- **Descrição:** Aproveitar a base de conhecimentos para pesquisar o problema da Piper. 

	- **Duração:** 30 minutos.

24. Clique no botão **Salvar e Fechar**. 

25. No lado direito da tela de caso, localize e selecione o ícone de livro **Conhecimento**. (Ele estará diretamente abaixo do ícone de chave inglesa).

26. Observe que o título do caso está sendo usado automaticamente como texto da pesquisa. Localize e selecione o artigo **Sensor não está funcionando - suas iniciais** que você criou anteriormente. 

27. O conteúdo completo do artigo será exibido; selecione o ícone de **Polegar para cima** na parte inferior do artigo para indicar que o artigo foi útil. 

28. Selecione o ícone **Vincular este artigo ao registro atual**. Verifique se o texto **Vinculado ao caso** aparece. 

 

### Tarefa 2: Fechar o caso

Agora que identificamos uma resolução para o problema da cliente, vamos nos preparar para resolver o caso. A primeira etapa para fechar o caso é encerrar quaisquer atividades abertas que foram associadas a ele. 

1. Na **Linha do tempo** do registro, passe o mouse sobre a **tarefa Pesquisar o problema da Piper** que você criou anteriormente**.** Selecione a marca cheia **Ícone de marca de verificação** para concluir a atividade. 

2. Na tela **Fechar tarefa**, verifique se o status está Concluído e selecione o botão **Fechar**. O status da tarefa deve dizer **Fechada**. 

3. Passe o mouse sobre a **Chamada telefônica - Retornar chamada para Piper** que você criou anteriormente**.** Selecione a marca cheia **Ícone de marca de verificação** para concluir a atividade. 

4. Na tela **Fechar chamada telefônica**, verifique se o **Estado** está **Concluído** e se o **Status** está **Feito**. Selecione o botão **Fechar**. Verifique se a atividade aparece como fechada na Linha do tempo. 

5. No **Telefone para processar caso**, selecione o estágio **Pesquisar** e selecione **Próximo estágio** para avançar ao estágio **Resolver**. 

6. No estágio **Resolver**, selecione o botão **Finalizar** para concluir o fluxo do processo. 

7. Na **Barra de comando** para o registro do caso, selecione o botão **Resolver caso**.

8. Na janela **Resolver caso**, defina o campo **Resolução** para **Artigo de conhecimento**. 

9. Verifique se os campos **Tempo total** e **Tempo faturável** estão definidos para **45 minutos** (isso representa o tempo total gasto nas atividades Chamada telefônica e Tarefa adicionadas ao registro.) 

10. Selecione o botão **Resolver** para completar o processo. 

