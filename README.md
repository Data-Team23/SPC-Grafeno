# SPC-Grafeno



# Summary
* [Context](#contexto)
* [Team](#team)
* [Product Backlog](#product-backlog)
* [Sprint 01](#sprint-01)
* [Sprint 02](#sprint-02)
* [Sprint 03](#sprint-03)
* [Technologies Used](#technologies-used)
  
# Contexto
[SPC Grafeno](https://spcgrafeno.com.br/)
 You've been hired by a financial asset registrar to create innovative new financial products using machine learning techniques. The company will provide a diverse database, containing historical information on a variety of financial assets, transactions and market behaviors. Its challenge is to explore this database, identify patterns and opportunities, and develop one or more financial products that can add value to both the company and its customers.
 You will be expected to use machine learning techniques to predict trends, identify risks or even propose methods for qualifying assets. Your solution must be implemented in a proof of concept that demonstrates the viability of the proposed feasibility of the proposed product, including a description of the model used, justification for the techniques used and an evaluation of the model's performance.
 At the end, you must present your results in a report, accompanied by a presentation that explains clearly and objectively how your solution can be used by the company and what benefits it can bring to the registrar and its customers.

# Team

> _Product Owner_ - [Alan Morato](https://www.linkedin.com/in/alan-morato-37b214154/)

> _Scrum Master_ - [Lucas Emanoel](https://www.linkedin.com/in/lucas-emanoel-teixeira-engracio-da-silva-ab5611234/)

> _Dev. Team_ - [Ariane Cristina](https://www.linkedin.com/in/ariane-sousa77/)

> _Dev. Team_ - [Elizabeth Cristina Alves Leite](https://www.linkedin.com/in/elizabeth-cristina-alves-leite-176a9416a)

> _Dev. Team_ - [Tobias Fernandes Bezerra Sousa](https://www.linkedin.com/in/tobias-sousa-23bba822a)

> _Dev. Team_ - [Julia Quitério](https://www.linkedin.com/in/j%C3%BAlia-quit%C3%A9rio-934894205/)

> _Dev. Team_ - [Murilo Junior](https://www.linkedin.com/in/murilo-jos%C3%A9-de-brito-junior-32403b157/)

> _Dev. Team_ - [Silas Prado](https://www.linkedin.com/in/silasprd/)

# Product Backlog
<div> <table> <tr> <td><b>Priority</b></td> <td><b>Backlog</b></td> <td><b>Estimate in days</b></td> <td><b>Sprint</b></td> </tr> <tr> <td>High</td> <td>Creation of initial dashboards for data analysis</td> <td>5</td> <td>1</td> </tr> <tr> <td>High</td> <td>Application of statistical analysis to data</td> <td>5</td> <td>1</td> </tr> <tr> <td>High</td> <td>Creation of user CRUD operations</td> <td>5</td> <td>1</td> </tr> <tr> <td>High</td> <td>Preparation of the database for model training</td> <td>10</td> <td>1</td> </tr> <tr> <td>High</td> <td>Implementation of user profile</td> <td>10</td> <td>1</td> </tr> <tr> <td>High</td> <td>Development of the machine learning model</td> <td>15</td> <td>2</td> </tr> <tr> <td>High</td> <td>Development of a place for dataset visualization</td> <td>5</td> <td>2</td> </tr> <tr> <td>Medium</td> <td>Development of health indicators for the machine learning model</td> <td>5</td> <td>3</td> </tr> <tr> <td>Medium</td> <td>User data exportation</td> <td>5</td> <td>3</td> </tr> </table> </div>

# Backlog Sprint 01
<div> <table> <tr> <td><b>Priority</b></td> <td><b>Backlog</b></td> <td><b>Estimate in days</b></td> </tr> <tr> <td>High</td> <td>Creation of initial dashboards for data analysis</td> <td>5</td> </tr> <tr> <td>High</td> <td>Application of statistical analysis to data</td> <td>5</td> </tr> <tr> <td>High</td> <td>Creation of user CRUD operations</td> <td>5</td> </tr> <tr> <td>High</td> <td>Preparation of the database for model training</td> <td>10</td> </tr> <tr> <td>High</td> <td>Implementation of user profile</td> <td>10</td> </tr> </table> </div>

# Backlog Sprint 02
<div> <table> <tr> <td><b>Priority</b></td> <td><b>Backlog</b></td> <td><b>Estimate in days</b></td> </tr> <tr> <td>High</td> <td>Development of the machine learning model</td> <td>15</td> </tr> <tr> <td>High</td> <td>Development of a place for dataset visualization</td> <td>5</td> </tr> </table> </div>


# Backlog Sprint 03
<div> <table> <tr> <td><b>Priority</b></td> <td><b>Backlog</b></td> <td><b>Estimate in days</b></td> </tr> <tr> <td>Medium</td> <td>Development of health indicators for the machine learning model</td> <td>5</td> </tr> <tr> <td>Medium</td> <td>User data exportation</td> <td>5</td> </tr> </table> </div>

# Technologies Used
- ``Python``
- ``JavaScript``
- ``Vue``
- ``HTML``
- ``CSS``
- ``Mongo DB``
- ``Postgres``

# Sprint 01
## User Stories
<div>
    <table border="1" cellpadding="5" cellspacing="0">
        <tr>
            <td><b>User Story</b></td>
            <td><b>Critério de Aceitação</b></td>
            <td><b>DoD</b></td>
            <td><b>Priority</b></td>
            <td><b>Backlog</b></td>
            <td><b>Estimate in days</b></td>
        </tr>
        <tr>
            <td>Como Front-end Developer, quero criar uma interface de edição de dados de usuário para que administradores possam facilmente atualizar informações de usuários.</td>
            <td>- A interface deve permitir a edição de todos os campos de dados do usuário.<br>- Deve haver validação para entradas obrigatórias.<br>- Interface amigável e intuitiva.</td>
            <td>- Interface de edição testada e validada.<br>- Funcionalidades de validação verificadas.<br>- Feedback visual para erros de entrada implementado.</td>
            <td>High</td>
            <td>Creation of user CRUD operations</td>
            <td>5</td>
        </tr>
        <tr>
            <td>Como Front-end Developer, quero criar uma interface para cadastro de novos usuários no sistema para que administradores possam adicionar novos usuários de forma intuitiva e segura.</td>
            <td>- Interface de cadastro deve incluir todos os campos obrigatórios.<br>- Validação de dados com mensagens de erro amigáveis.<br>- Confirmação de cadastro ao final do processo.</td>
            <td>- Interface de cadastro implementada e testada.<br>- Todas as validações de campo funcionais.<br>- Testes de experiência do usuário realizados.</td>
            <td>High</td>
            <td>Creation of user CRUD operations</td>
            <td>5</td>
        </tr>
        <tr>
            <td>Como Back-end Developer, quero implementar a operação de exclusão de usuário no sistema para que seja possível remover perfis de usuários que não devem mais estar no sistema.</td>
            <td>- API deve permitir exclusão de usuários de forma segura.<br>- Deleção deve estar restrita a usuários com permissão.<br>- Exclusão deve ser confirmada antes da ação final.</td>
            <td>- Endpoint de exclusão de usuário implementado e documentado.<br>- Permissões e restrições testadas.<br>- Log de atividade de exclusão gerado.</td>
            <td>High</td>
            <td>Creation of user CRUD operations</td>
            <td>5</td>
        </tr>
        <tr>
            <td>Como Back-end Developer, quero implementar a operação de criação de usuário no sistema para que usuários possam ser registrados corretamente com todas as validações necessárias, permitindo a inclusão de novos perfis no sistema.</td>
            <td>- Endpoint de criação deve validar todos os campos obrigatórios.<br>- Deve gerar um erro se os dados estiverem ausentes ou incorretos.<br>- Criação deve ser confirmada com sucesso.</td>
            <td>- Endpoint de criação implementado e documentado.<br>- Testes de validação concluídos.<br>- Logs de criação registrados.</td>
            <td>High</td>
            <td>Creation of user CRUD operations</td>
            <td>5</td>
        </tr>
        <tr>
            <td>Como Front-end Developer, quero implementar a funcionalidade de exclusão de usuário no sistema para que administradores possam remover perfis de usuário que não são mais necessários.</td>
            <td>- A interface de exclusão deve exibir uma confirmação antes da exclusão.<br>- Deleção deve ser restrita a administradores.<br>- Feedback visual após exclusão com mensagem de sucesso.</td>
            <td>- Funcionalidade de exclusão implementada na interface.<br>- Mensagens de confirmação e sucesso exibidas.<br>- Testes de funcionalidade e permissão realizados.</td>
            <td>High</td>
            <td>Creation of user CRUD operations</td>
            <td>5</td>
        </tr>
        <tr>
            <td>Como Front-end Developer, quero criar uma interface que liste todos os usuários no sistema com funcionalidades de filtro e busca para que administradores possam visualizar e gerenciar perfis de usuário existentes.</td>
            <td>- A interface deve listar todos os usuários cadastrados.<br>- Deve permitir filtrar e buscar usuários por atributos.<br>- Interface responsiva e fácil de navegar.</td>
            <td>- Funcionalidade de listagem e filtro testada.<br>- Pesquisa de usuário funcional.<br>- Interface responsiva e validada em diferentes resoluções.</td>
            <td>High</td>
            <td>Creation of user CRUD operations</td>
            <td>5</td>
        </tr>
        <tr>
            <td>Como Back-end Developer, quero implementar a operação de leitura de usuários para que seja possível listar, visualizar e obter detalhes dos perfis de usuários cadastrados no sistema.</td>
            <td>- Endpoint de leitura deve retornar lista de usuários com detalhes completos.<br>- Deve permitir busca por identificadores.<br>- Respostas rápidas e consistentes.</td>
            <td>- Endpoint de leitura implementado e documentado.<br>- Testes de busca e desempenho realizados.<br>- Logs de acesso e busca ativados.</td>
            <td>High</td>
            <td>Creation of user CRUD operations</td>
            <td>5</td>
        </tr>
        <tr>
            <td>Como usuário do SPC, quero ter o tratamento adequado do meu banco de dados para que seja possível aumentar a probabilidade de sucesso do meu modelo de machine learning.</td>
            <td>- O banco de dados deve estar otimizado para armazenamento de dados grandes.<br>- A estrutura de dados deve ser compatível com os requisitos do modelo.<br>- Deve permitir fácil recuperação de dados.</td>
            <td>- Banco de dados otimizado e revisado.<br>- Validação de compatibilidade com o modelo de machine learning.<br>- Testes de recuperação e desempenho realizados.</td>
            <td>High</td>
            <td>Preparation of the database for model training</td>
            <td>10</td>
        </tr>
        <tr>
            <td>Como usuário do SPC, quero ter um dashboard para análise de dados que inclua a análise de clientes para que seja possível entender como estão as métricas das nossas transações.</td>
            <td>- O dashboard deve exibir métricas transacionais em tempo real.<br>- Deve permitir segmentação e análise detalhada de clientes.<br>- Visualizações gráficas intuitivas.</td>
            <td>- Dashboard implementado e testado.<br>- Visualizações e filtros funcionais.<br>- Acessível e otimizado para desempenho.</td>
            <td>High</td>
            <td>Creation of initial dashboards for data analysis</td>
            <td>5</td>
        </tr>
    </table>
</div>


## Burndown

![image](https://github.com/user-attachments/assets/b0fe6471-e82f-4e0a-ae3c-f2b298fdefa7)



# Sprint 02
## User Stories
<table border="1" cellpadding="5" cellspacing="0"> <tr> <td><b>User Story</b></td> <td><b>Critério de Aceitação</b></td> <td><b>DoD</b></td> <td><b>Prioridade</b></td> <td><b>Estimativa (dias)</b></td> </tr> <tr> <td>Como engenheiro de backend, quero integrar o banco de dados com a aplicação, para que os datasets sejam armazenados de forma persistente e possam ser usados pelo modelo de machine learning.</td> <td> - O banco de dados deve permitir armazenamento e consulta eficiente de datasets.<br> - Deve suportar dados de grande volume.<br> - A integração deve permitir atualização e remoção de dados. </td> <td> - A conexão com o banco está configurada e funcional.<br> - As operações de CRUD estão testadas e funcionais.<br> - Testes de carga no banco de dados estão validados. </td> <td>High</td> <td>5</td> </tr> <tr> <td>Como engenheiro de machine learning, quero implementar a versão final do modelo em produção, para que ele esteja disponível para uso através da API de backend.</td> <td> - O modelo deve ser convertido em um formato adequado para produção (e.g., pickle, TensorFlow SavedModel).<br> - O modelo deve ser carregado rapidamente.<br> - A versão em produção deve ser monitorada quanto à performance. </td> <td> - O modelo está rodando em um ambiente de produção com sucesso.<br> - Performance monitorada e validada sob diferentes condições de carga.<br> - Logs de execução configurados para rastrear falhas. </td> <td>High</td> <td>4</td> </tr> <tr> <td>Como desenvolvedor ou engenheiro de machine learning, quero documentar o modelo de machine learning e o software que o suporta, para que outros membros da equipe e futuros desenvolvedores possam entender, manter e evoluir o sistema com clareza.</td> <td> - A arquitetura do sistema deve ser descrita com diagramas claros.<br> - Os principais componentes do código devem ser documentados.<br> - Deve haver uma explicação detalhada sobre o funcionamento do modelo de ML.<br> - Instruções para instalação, configuração e uso do software devem estar presentes. </td> <td> - A documentação técnica está em formato claro e padronizado.<br> - Diagramas atualizados estão incluídos.<br> - Todos os endpoints da API estão documentados com exemplos.<br> - A documentação foi revisada e está acessível no repositório do projeto. </td> <td>High</td> <td>6</td> </tr> <tr> <td>Como engenheiro de machine learning, quero treinar e ajustar o modelo de machine learning, para que ele possa fornecer previsões precisas com base nos datasets fornecidos.</td> <td> - O modelo deve ter uma precisão mínima de X%.<br> - O overfitting e underfitting devem ser evitados.<br> - Logs de treinamento e métricas de performance devem estar disponíveis. </td> <td> - O modelo foi testado e ajustado em um ambiente de desenvolvimento.<br> - A precisão atingiu o valor definido.<br> - Os resultados do modelo foram validados com dados de teste. </td> <td>High</td> <td>7</td> </tr> <tr> <td>Como desenvolvedor backend, quero criar a tabela de usuário e a tabela de termos de LGPD no banco de dados, para que o sistema armazene de forma segura as informações dos usuários e o consentimento dos termos, atendendo aos requisitos legais de proteção de dados.</td> <td> - A Tabela de Usuário deve conter campos essenciais com restrições de integridade.<br> - A Tabela de Termos de LGPD deve ser preparada para múltiplas versões do termo.<br> - A relação entre tabelas deve garantir associação à versão mais recente do termo. </td> <td> - As tabelas foram criadas no banco de dados com restrições de integridade.<br> - Relacionamentos entre tabelas foram implementados corretamente.<br> - Estrutura documentada e revisada quanto à conformidade com a LGPD. </td> <td>High</td> <td>8</td> </tr> <tr> <td>Como desenvolvedor frontend, quero criar uma interface de usuário para visualização dos datasets, para que o usuário possa visualizar, filtrar e explorar os dados carregados.</td> <td> - A interface deve listar os datasets disponíveis.<br> - Deve permitir filtros e ordenação de dados.<br> - Deve ser responsiva e fácil de navegar. </td> <td> - Interface testada em diferentes resoluções.<br> - Funcionalidades de filtragem e ordenação validadas.<br> - Feedback visual sobre erros ou resultados vazios. </td> <td>High</td> <td>3</td> </tr> <tr> <td>Como desenvolvedor frontend, quero criar uma interface para o CRUD de usuários com conformidade à LGPD, para que o sistema permita a gestão eficiente dos dados dos usuários, garantindo que todos os processos atendam aos requisitos legais de proteção de dados.</td> <td> - A interface de cadastro deve permitir o registro de novos usuários com campos obrigatórios.<br> - Edição e consulta de dados dos usuários devem ser permitidas.<br> - A exclusão de usuário deve garantir anonimização conforme LGPD. </td> <td> - A view de CRUD foi implementada.<br> - A lógica de aceite da LGPD está integrada.<br> - Testes de funcionalidade foram realizados e as rotas de backend documentadas. </td> <td>High</td> <td>2</td> </tr> <tr> <td>Como desenvolvedor backend/frontend, quero implementar a funcionalidade de termos de condição e revogação no sistema, para que o usuário possa aceitar ou revogar termos de uso e consentimento em conformidade com a LGPD.</td> <td> - Interface clara para exibir e aceitar o termo.<br> - Histórico de termos aceitos registrado.<br> - Interface para revogação de consentimento visível.<br> - Gestão de termos na administração disponível. </td> <td> - Funcionalidade de aceite e revogação implementada e testada.<br> - Documentação completa com exemplos e diagramas de fluxo.<br> - Revisão quanto à conformidade com a LGPD. </td> <td>High</td> <td>5</td> </tr> <tr> <td>Como engenheiro de machine learning, quero estudar e comparar diferentes algoritmos de machine learning, para selecionar o modelo que oferece a melhor performance e precisão para o problema.</td> <td> - Testar pelo menos 3 algoritmos diferentes.<br> - Avaliar modelos com as mesmas métricas.<br> - Selecionar o modelo com base em performance e complexidade. </td> <td> - Relatório comparativo dos modelos foi produzido.<br> - Melhor modelo validado com dados de teste.<br> - Logs de experimentação gerados para cada modelo. </td> <td>High</td> <td>4</td> </tr> </table>


![image](https://github.com/user-attachments/assets/aea70066-2a2b-4a71-918a-91cdcd86d89e)



### Tools Used
Tool   | Description
--------- | ------
Notion | Brainstorming notes and feature definition  
Miro | Journey mapping, information flow, and feature prioritization  
Figma | Low and high-fidelity prototyping  
Hotjar | Usability testing and data analysis  
VSCode | Feature programming  
Postgres | Database creation and programming  
MongoDB | Database creation and programming  


## Data Model
### DER
![modelo_logico_api_spc](https://github.com/user-attachments/assets/7aef590f-efc9-4a80-ba2b-22118d91f195)


