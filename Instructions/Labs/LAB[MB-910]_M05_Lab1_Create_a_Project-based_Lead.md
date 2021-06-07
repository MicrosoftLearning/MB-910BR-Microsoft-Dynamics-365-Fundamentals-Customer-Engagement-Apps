---
lab:
    title: 'Laboratório 5.1: criar um lead baseado em projeto'
    module: 'Módulo 5: aprender os princípios básicos do Dynamics 365 Project Operations'
---

Módulo 5: aprender os princípios básicos do Dynamics 365 Project Operations
========================

## Laboratório de prática 5.1: criar um lead baseado em projeto

## Cenário do laboratório

A empresa ABC é especializada na fabricação, venda, instalação e manutenção de equipamentos de segurança. Seus produtos incluem câmeras de segurança internas e externas, sensores de umidade e incêndio, serviços de monitoramento e muito mais. 

A empresa ABC usa aplicativos Dynamics 365 para interagir com todos os clientes em diferentes áreas da organização, de vendas até manutenção. 

**Vendas e Marketing**

A empresa ABC faz divulgação com seus clientes residenciais diretamente por meio de campanhas de marketing direcionadas. Os clientes são especificados com base na cidade e em outros fatores. Os materiais de marketing são enviados por email e são baseados na interação com o email direcionado correspondente. 

Embora alguns de seus produtos menores sejam vendidos por varejistas, a maioria é vendida diretamente para os consumidores por meio da equipe interna de vendas.

Internamente, eles focam em duas áreas principais: 

- **Clientes residenciais:** Geralmente, os clientes residenciais estão procurando seus componentes individuais ou estão procurando comprar uma solução totalmente caseira. Esses ciclos de vendas normalmente são mais curtos e são originados de mídias sociais, sites, referências ou contato direto de possíveis clientes. Como os clientes residenciais normalmente são mais focados em produtos específicos ou instalações menores, seus ciclos de vendas costumam durar alguns dias ou semanas. 

- **Clientes corporativos:** Os vendedores corporativos focam em clientes que precisam de soluções comerciais mais especializadas e personalizadas. As vendas corporativas abrangem vários locais com comunicação vinculada e frequentemente precisam de vários recursos para concluir o projeto. Esses ciclos de vendas costumam ser mais longos e têm muitas partes móveis. 

É importante que todos os vendedores da empresa ABC tenham as ferramentas, recursos e orientação necessários independentemente da área de foco durante as vendas aos clientes. 

**Instalação do sistema:**

o processo de instalação dos equipamentos de segurança adquiridos varia com base no tipo de cliente. 

- **Clientes residenciais:** como as instalações residenciais geralmente levam menos de um dia, elas são feitas por funcionários internos. Depois que a venda é realizada, uma ordem de serviço é criada e um técnico qualificado é identificado e designado para fazer a instalação. 

- **Clientes corporativos:** as implantações corporativas podem levar meses e precisam de um gerente de projeto para supervisionar as operações diárias. Isso inclui a criação de planos de projetos, a definição das equipes de projetos e a programação de recursos. 

**Manutenção e suporte:**

depois que os sistemas estiverem instalados, a empresa ABC fornece suporte após a venda. Se um cliente tiver algum problema, ele pode entrar em contato com o suporte ao cliente. Um agente tentará trabalhar com o cliente remotamente para resolver o problema. Se não for possível resolver o problema remotamente, o agente de suporte pode encaminhá-lo a uma ordem de serviço, que será programada e atendida por um técnico de campo qualificado. 
## Objetivos

Os vendedores da empresa ABC focam mais a atenção em clientes cujas necessidades de segurança exigem soluções comerciais mais especializadas e personalizadas. Por esse motivo, suas vendas corporativas normalmente abrangem vários locais com comunicação vinculada e frequentemente precisam de vários recursos para concluir o projeto. Os ciclos de vendas corporativas das empresas ABC podem levar muitos meses e precisam de várias partes móveis para a execução. 

Depois que um cliente corporativo compra um sistema, pode levar meses para implementar o projeto. Cada projeto é atribuído a um gerente, que supervisiona o planejamento do projeto e as operações diárias. Isso inclui a criação de planos de projetos, a definição das equipes de projetos e a programação de recursos. 

Como vendedor corporativo, você é responsável pela venda de soluções de segurança personalizadas de alta qualidade aos clientes. Recentemente, você recebeu uma ligação de uma empresa chamada Consolidated Sample. Ela gostaria de ter uma solução de segurança totalmente integrada que abrangesse todos os seus locais. Você inserirá o lead da Consolidated Sample no sistema, incluí-lo por meio do ciclo de vendas do projeto e criar um projeto correspondente. 

Após a conclusão do laboratório, você terá concluído o seguinte:

- Insira um lead de projeto no Dynamics 365 Sales

## Configuração do laboratório

  - **Tempo estimado**: 10 minutos

## Instruções

## Exercício 1: criar um lead baseado em projeto

### Tarefa 1: criar um novo Lead

1. Se necessário, abra um navegador InPrivate e navegue até [Https://home.Dynamics.com](https://home.dynamics.com/) 

2. Quando solicitado, faça login com as credenciais do usuário fornecidas a você pelo instrutor. 

3. Na lista de aplicativos exibida, selecione **Operações do Projeto**. **(Observação:** pode ser também Manutenção do Projeto)

4. Usando a navegação no lado esquerdo da tela, selecione a área **Projetos**. 

5. No menu exibido, selecione **Vendas**.

6. Usando a navegação, selecione **Leads**. 

7. Para exibir todos os leads de vendas atuais no sistema, selecione a seta para baixo próxima a **Meus leads em Aberto**; no menu exibido, selecione **Leads Ativos**. 

8. Para navegar de volta à sua lista de leads, selecione a seta para baixo próxima a Leads Ativos e, no menu exibido, selecione **Meus Leads em Aberto**. 

9. Em seguida, criaremos um novo lead para uma empresa chamada Consolidated Sample. Na exibição **Meus Leads em Aberto**, selecione o botão **Novo** na Barra de comandos.

10. Conclua seu novo registro de leads da seguinte maneira:

	- **Tópico:** implementação global completa – Suas iniciais

	- **Digite:** baseado no trabalho

	- **Nome:** Jean

	- **Sobrenome:** Anderson - Suas iniciais

	- **Telefone Comercial:** 888 555-8855

	- **Email:** jean@sample.com

	- **Empresa:** Consolidated Sample – Suas iniciais

	- **Rua 1:** 219 91<sup data-htmlnode="">st</sup> Ave N

	- **Cidade:** Seattle

	- **Estado/Província:** WA

	- **CEP/Código Postal:** 98001 

11. Selecione o botão **Salvar** na Barra de Comandos para salvar o novo lead e deixe-o aberto.

12. Observe o Fluxo do Processo Comercial do **Lead da Oportunidade** na parte superior do registro. Clique em **Qualificar Estágio** para selecioná-lo. Conclua o estágio da seguinte maneira:

	- **Cronograma de Compras:** este trimestre

	- **Orçamento Estimado:** 25000  

	- **Processo de Compra:** comissão

	- **Identificar o Tomador de Decisões:** concluído

13. Clique em **X** na janela do estágio para fechá-la. 

14. Acesse **Cronograma de Registro** no meio da tela e clique em **Ícone de sinal de adição** para adicionar uma nova atividade. 

15. No menu exibido, selecione **Ligação Telefônica**.

16. Na tela Criação Rápida da Ligação Telefônica, complete a ligação telefônica da seguinte maneira:

	- **Assunto:** chamada de qualificação inicial – Suas iniciais  

	- **Número de Telefone:** 888 555-8855

	- **Direção:** saída

	- **Descrição:** Conversa inicial com Jean para determinar a qualificação inicial. 

17. Clique no botão **Salvar e Fechar**.

18. Observe que a atividade **Chamada de Qualificação Inicial** agora é exibida no **Cronograma de Registro**. Passe o mouse sobre a atividade e selecione a atividade de fechamento **Ícone de Visto** para marcar a ligação telefônica como concluída. 

19. Na janela **Fechar Telefonema**, verifique se o estado está definido como **Concluído** e selecione o botão **Fechar**.

 

### Tarefa 2: qualificar o Lead e converter em Oportunidade para melhor qualificação

1. Na **Barra de Comandos**, selecione o botão **Qualificar**. 

2. Depois que o sistema qualificar o lead, um novo registro de Oportunidade será criado e o processo comercial passará para o estágio **Desenvolver**. Selecione o estágio **Qualificar** para exibir o registro de lead original. 

3. Selecione o estágio **Desenvolver** para retornar à oportunidade.

4. Clique no botão **Salvar e Fechar** para fechar o registro de Oportunidade que foi criado. 

