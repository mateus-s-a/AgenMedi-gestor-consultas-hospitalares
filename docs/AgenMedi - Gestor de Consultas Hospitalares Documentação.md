# Visão do Produto

Para hospitais e clínicas de pequeno e médio porte que buscam otimizar o agendamento e a gestão de consultas, reduzindo filas e melhorando a experiência do paciente, o **MediAgenda** é um sistema web intuitivo e eficiente para gerenciamento de consultas hospitalares. Ao contrário de sistemas complexos e caros que exigem grande infraestrutura e treinamento, nosso produto oferece uma solução simplificada e acessível, focada na facilidade de uso para secretárias e pacientes, garantindo agendamentos rápidos, lembretes automáticos e uma visão clara da agenda médica.

# Concepção do Produto

O MediAgenda será um sistema web com duas interfaces principais: uma para a equipe administrativa (secretárias/recepcionistas) e outra para os pacientes. A interface administrativa permitirá o cadastro de médicos, especialidades, horários de atendimento e a gestão completa da agenda (agendamento, reagendamento, cancelamento de consultas). A interface do paciente será simplificada, permitindo a busca por médicos/especialidades, visualização de horários disponíveis e solicitação de agendamento. O sistema enviará lembretes automáticos de consulta via e-mail ou SMS (se houver integração futura). O foco será na usabilidade e na automação de tarefas repetitivas para a equipe administrativa, liberando tempo para outras atividades. A arquitetura será baseada em tecnologias web comuns (frontend com HTML/CSS/JavaScript e um framework leve, backend com Python/Flask ou Node.js/Express e um banco de dados relacional simples como SQLite ou PostgreSQL), tornando-o acessível para uma equipe de desenvolvedores amadores. Não haverá funcionalidades complexas como prontuário eletrônico completo, faturamento ou integração com sistemas de convênio inicialmente, mantendo o escopo focado na gestão de agendamentos.

# Elevator Pitch

Para hospitais e clínicas que buscam uma gestão de consultas mais eficiente e menos burocrática, o **MediAgenda** é um sistema web intuitivo que simplifica o agendamento, reagendamento e cancelamento de consultas. Ao contrário de softwares complexos e caros, o MediAgenda oferece uma solução acessível e fácil de usar, otimizando o tempo da equipe administrativa e melhorando a experiência do paciente com lembretes automáticos e uma agenda clara.

# Product Backlog

## Épicos

*   **EPIC-001: Gestão de Agendamentos**
    *   Descrição: Funcionalidades para agendar, reagendar, cancelar, confirmar e bloquear horários de consultas.

*   **EPIC-002: Gestão de Cadastros**
    *   Descrição: Funcionalidades para cadastrar, buscar e gerenciar médicos, pacientes e especialidades.

*   **EPIC-003: Interface do Paciente**
    *   Descrição: Funcionalidades para o paciente buscar horários, solicitar, visualizar e cancelar agendamentos.

*   **EPIC-004: Notificações e Lembretes**
    *   Descrição: Funcionalidades para enviar lembretes e confirmações automáticas.

*   **EPIC-005: Relatórios Básicos**
    *   Descrição: Funcionalidades para gerar relatórios simples sobre as consultas.

## Histórias de Usuário (User Stories)

### EPIC-001: Gestão de Agendamentos

*   **US-001: Agendar Nova Consulta**
    *   Como uma secretária, desejo agendar uma nova consulta para um paciente, para que ele seja atendido no horário correto.

*   **US-002: Reagendar Consulta**
    *   Como uma secretária, desejo reagendar uma consulta existente, para ajustar a agenda do paciente ou do médico.

*   **US-003: Cancelar Consulta**
    *   Como uma secretária, desejo cancelar uma consulta, para liberar o horário na agenda.

*   **US-004: Visualizar Agenda do Médico**
    *   Como uma secretária, desejo visualizar a agenda de um médico, para verificar a disponibilidade de horários.

*   **US-012: Confirmar Consulta Solicitada**
    *   Como uma secretária, desejo confirmar uma solicitação de agendamento feita pelo paciente, para oficializar a consulta.

*   **US-013: Bloquear Horários na Agenda**
    *   Como uma secretária, desejo bloquear horários específicos na agenda de um médico (ex: para reuniões, imprevistos), para evitar agendamentos indevidos.

### EPIC-002: Gestão de Cadastros

*   **US-005: Cadastrar Novo Médico**
    *   Como uma secretária, desejo cadastrar um novo médico, para que ele possa ter sua agenda gerenciada no sistema.

*   **US-006: Cadastrar Novo Paciente**
    *   Como uma secretária, desejo cadastrar um novo paciente, para que ele possa agendar consultas.

*   **US-007: Gerenciar Especialidades**
    *   Como uma secretária, desejo gerenciar as especialidades médicas, para associá-las aos médicos e facilitar a busca.

*   **US-014: Buscar Paciente Cadastrado**
    *   Como uma secretária, desejo buscar um paciente já cadastrado, para agilizar o agendamento ou a consulta de dados.

*   **US-015: Buscar Médico Cadastrado**
    *   Como uma secretária, desejo buscar um médico já cadastrado, para visualizar sua agenda ou editar seus dados.

*   **US-016: Editar Dados de Paciente**
    *   Como uma secretária, desejo editar os dados de um paciente, para manter as informações atualizadas.

*   **US-017: Editar Dados de Médico**
    *   Como uma secretária, desejo editar os dados de um médico, para manter as informações atualizadas.

### EPIC-003: Interface do Paciente

*   **US-008: Buscar Horários Disponíveis**
    *   Como um paciente, desejo buscar horários disponíveis por médico ou especialidade, para encontrar uma consulta que se encaixe na minha disponibilidade.

*   **US-009: Solicitar Agendamento**
    *   Como um paciente, desejo solicitar um agendamento de consulta, para marcar meu atendimento de forma online.

*   **US-010: Visualizar Minhas Consultas Agendadas**
    *   Como um paciente, desejo visualizar minhas consultas agendadas, para não esquecer os compromissos.

*   **US-018: Receber Confirmação de Agendamento**
    *   Como um paciente, desejo receber uma confirmação da minha solicitação de agendamento, para ter certeza que foi recebida.

*   **US-019: Cancelar Agendamento (Paciente)**
    *   Como um paciente, desejo poder cancelar meu próprio agendamento online, para liberar o horário e evitar faltas.

### EPIC-004: Notificações e Lembretes

*   **US-011: Enviar Lembrete de Consulta**
    *   Como o sistema, desejo enviar lembretes automáticos de consulta para os pacientes, para reduzir o número de faltas.

### EPIC-005: Relatórios Básicos

*   **US-020: Gerar Relatório de Consultas Diárias**
    *   Como uma secretária, desejo gerar um relatório das consultas agendadas para um dia específico, para ter um resumo das atividades.

*   **US-021: Gerar Relatório de Consultas por Médico**
    *   Como uma secretária, desejo gerar um relatório das consultas realizadas por um médico em um período, para acompanhar sua produtividade.

## Níveis de Granularidade

### Exemplo de Épico, História e Tarefa para EPIC-001: Gestão de Agendamentos

*   **ÉPICO:** Gestão de Agendamentos

    *   **HISTÓRIA:** US-001: Agendar Nova Consulta
        *   **TAREFA:** Criar formulário de agendamento (paciente, médico, data, hora).
        *   **TAREFA:** Implementar validação de horário disponível na agenda do médico.
        *   **TAREFA:** Salvar dados da consulta no banco de dados.
        *   **TAREFA:** Exibir confirmação de agendamento.

    *   **HISTÓRIA:** US-004: Visualizar Agenda do Médico
        *   **TAREFA:** Desenvolver interface de calendário para exibição da agenda.
        *   **TAREFA:** Carregar consultas do médico selecionado por data.
        *   **TAREFA:** Exibir status do horário (ocupado, livre).

    *   **HISTÓRIA:** US-012: Confirmar Consulta Solicitada
        *   **TAREFA:** Desenvolver interface para secretária visualizar solicitações pendentes.
        *   **TAREFA:** Implementar botão de "Confirmar" para a secretária.
        *   **TAREFA:** Atualizar status da consulta para "Confirmada" no banco de dados.

    *   **HISTÓRIA:** US-013: Bloquear Horários na Agenda
        *   **TAREFA:** Criar funcionalidade para secretária selecionar horários e marcar como "bloqueado".
        *   **TAREFA:** Impedir agendamentos em horários bloqueados.
        *   **TAREFA:** Exibir horários bloqueados de forma clara na agenda do médico.

### Exemplo de Épico, História e Tarefa para EPIC-002: Gestão de Cadastros

*   **ÉPICO:** Gestão de Cadastros

    *   **HISTÓRIA:** US-005: Cadastrar Novo Médico
        *   **TAREFA:** Criar formulário de cadastro de médico (nome, CRM, especialidade).
        *   **TAREFA:** Implementar validação dos campos.
        *   **TAREFA:** Salvar dados do médico no banco de dados.

    *   **HISTÓRIA:** US-006: Cadastrar Novo Paciente
        *   **TAREFA:** Criar formulário de cadastro de paciente (nome, CPF, telefone, e-mail).
        *   **TAREFA:** Implementar validação dos campos.
        *   **TAREFA:** Salvar dados do paciente no banco de dados.

    *   **HISTÓRIA:** US-014: Buscar Paciente Cadastrado
        *   **TAREFA:** Implementar campo de busca por nome ou CPF na lista de pacientes.
        *   **TAREFA:** Desenvolver lógica de filtro para exibir resultados da busca.

    *   **HISTÓRIA:** US-016: Editar Dados de Paciente
        *   **TAREFA:** Criar formulário de edição pré-preenchido com dados do paciente.
        *   **TAREFA:** Implementar funcionalidade de atualização dos dados no banco de dados.

### Exemplo de Épico, História e Tarefa para EPIC-003: Interface do Paciente

*   **ÉPICO:** Interface do Paciente

    *   **HISTÓRIA:** US-019: Cancelar Agendamento (Paciente)
        *   **TAREFA:** Adicionar botão de "Cancelar" na visualização de consultas agendadas do paciente.
        *   **TAREFA:** Implementar confirmação de cancelamento para o paciente.
        *   **TAREFA:** Atualizar status da consulta para "Cancelada" e liberar horário no banco de dados.

### Exemplo de Épico, História e Tarefa para EPIC-005: Relatórios Básicos

*   **ÉPICO:** Relatórios Básicos

    *   **HISTÓRIA:** US-020: Gerar Relatório de Consultas Diárias
        *   **TAREFA:** Criar interface para seleção de data para o relatório.
        *   **TAREFA:** Consultar banco de dados para todas as consultas do dia selecionado.
        *   **TAREFA:** Exibir relatório em formato de tabela na tela.

    *   **HISTÓRIA:** US-021: Gerar Relatório de Consultas por Médico
        *   **TAREFA:** Criar interface para seleção de médico e período.
        *   **TAREFA:** Consultar banco de dados para consultas do médico no período.
        *   **TAREFA:** Exibir relatório com total de consultas e detalhes.

## Histórias de Usuários (User Stories) - Detalhamento

*   **US-001: Agendar Nova Consulta**
    *   **Como um:** Secretária
    *   **Desejo:** Agendar uma nova consulta para um paciente
    *   **Para que:** Ele seja atendido no horário correto e a agenda do médico seja preenchida.
    *   **Critérios de Aceitação:**
        *   A secretária deve poder selecionar um paciente existente ou cadastrar um novo.
        *   A secretária deve poder selecionar um médico e uma especialidade.
        *   O sistema deve exibir os horários disponíveis para o médico na data selecionada.
        *   Após a seleção do horário, a consulta deve ser registrada na agenda do médico e do paciente.
        *   O sistema deve exibir uma confirmação de agendamento.

*   **US-002: Reagendar Consulta**
    *   **Como um:** Secretária
    *   **Desejo:** Reagendar uma consulta existente
    *   **Para que:** Eu possa ajustar a agenda do paciente ou do médico sem perder o registro.
    *   **Critérios de Aceitação:**
        *   A secretária deve poder buscar uma consulta existente pelo nome do paciente ou médico.
        *   O sistema deve permitir a alteração da data e/ou horário da consulta.
        *   O sistema deve validar a disponibilidade do novo horário.
        *   Após o reagendamento, a consulta deve ser atualizada na agenda do médico e do paciente.

*   **US-003: Cancelar Consulta**
    *   **Como um:** Secretária
    *   **Desejo:** Cancelar uma consulta
    *   **Para que:** Eu possa liberar o horário na agenda do médico e registrar o cancelamento.
    *   **Critérios de Aceitação:**
        *   A secretária deve poder buscar e selecionar uma consulta para cancelamento.
        *   O sistema deve solicitar uma confirmação antes de cancelar a consulta.
        *   Após o cancelamento, o horário deve ser liberado na agenda do médico.
        *   O status da consulta deve ser alterado para "Cancelada" no histórico do paciente.

*   **US-004: Visualizar Agenda do Médico**
    *   **Como um:** Secretária
    *   **Desejo:** Visualizar a agenda de um médico
    *   **Para que:** Eu possa verificar a disponibilidade de horários e gerenciar os agendamentos.
    *   **Critérios de Aceitação:**
        *   A secretária deve poder selecionar um médico para visualizar sua agenda.
        *   A agenda deve exibir os horários ocupados e livres para o dia selecionado.
        *   Deve ser possível navegar entre os dias e semanas na agenda.
        *   Ao clicar em um horário ocupado, os detalhes da consulta devem ser exibidos.

*   **US-005: Cadastrar Novo Médico**
    *   **Como um:** Secretária
    *   **Desejo:** Cadastrar um novo médico
    *   **Para que:** Ele possa ter sua agenda gerenciada no sistema e atender pacientes.
    *   **Critérios de Aceitação:**
        *   A secretária deve preencher um formulário com nome, CRM, especialidade e horários de atendimento do médico.
        *   O sistema deve validar o formato do CRM e garantir que a especialidade seja válida.
        *   Após o cadastro, o médico deve estar disponível para seleção nos agendamentos.

*   **US-006: Cadastrar Novo Paciente**
    *   **Como um:** Secretária
    *   **Desejo:** Cadastrar um novo paciente
    *   **Para que:** Ele possa agendar consultas e ter seu histórico de atendimentos registrado.
    *   **Critérios de Aceitação:**
        *   A secretária deve preencher um formulário com nome, CPF, telefone e e-mail do paciente.
        *   O sistema deve validar o formato do CPF e e-mail.
        *   Após o cadastro, o paciente deve estar disponível para seleção nos agendamentos.

*   **US-007: Gerenciar Especialidades**
    *   **Como um:** Secretária
    *   **Desejo:** Gerenciar as especialidades médicas
    *   **Para que:** Eu possa associá-las aos médicos e facilitar a busca por especialidade.
    *   **Critérios de Aceitação:**
        *   A secretária deve poder adicionar novas especialidades ao sistema.
        *   A secretária deve poder editar ou remover especialidades existentes (se não estiverem em uso).
        *   As especialidades cadastradas devem aparecer como opção ao cadastrar um médico ou buscar uma consulta.

*   **US-008: Buscar Horários Disponíveis**
    *   **Como um:** Paciente
    *   **Desejo:** Buscar horários disponíveis por médico ou especialidade
    *   **Para que:** Eu possa encontrar uma consulta que se encaixe na minha disponibilidade.
    *   **Critérios de Aceitação:**
        *   O paciente deve poder selecionar um médico ou uma especialidade.
        *   O sistema deve exibir os dias e horários disponíveis para agendamento.
        *   Deve ser possível filtrar por período do dia (manhã, tarde, noite).

*   **US-009: Solicitar Agendamento**
    *   **Como um:** Paciente
    *   **Desejo:** Solicitar um agendamento de consulta
    *   **Para que:** Eu possa marcar meu atendimento de forma online e conveniente.
    *   **Critérios de Aceitação:**
        *   Após selecionar um horário disponível, o paciente deve preencher um formulário com seus dados (nome, telefone, e-mail).
        *   O sistema deve enviar uma solicitação de agendamento para a secretária.
        *   O paciente deve receber uma confirmação de que sua solicitação foi enviada.

*   **US-010: Visualizar Minhas Consultas Agendadas**
    *   **Como um:** Paciente
    *   **Desejo:** Visualizar minhas consultas agendadas
    *   **Para que:** Eu não esqueça os compromissos e possa me preparar para eles.
    *   **Critérios de Aceitação:**
        *   O paciente deve poder acessar uma área logada para ver suas consultas.
        *   A lista deve exibir a data, hora, médico e especialidade de cada consulta.
        *   Deve ser possível ver o status da consulta (confirmada, pendente, cancelada).

*   **US-011: Enviar Lembrete de Consulta**
    *   **Como o:** Sistema
    *   **Desejo:** Enviar lembretes automáticos de consulta para os pacientes
    *   **Para que:** Eu possa reduzir o número de faltas e otimizar a agenda dos médicos.
    *   **Critérios de Aceitação:**
        *   O sistema deve enviar um lembrete (e-mail ou SMS) 24 horas antes da consulta.
        *   O lembrete deve conter a data, hora, médico e local da consulta.
        *   O sistema deve registrar o envio do lembrete.

*   **US-012: Confirmar Consulta Solicitada**
    *   **Como um:** Secretária
    *   **Desejo:** Confirmar uma solicitação de agendamento feita pelo paciente
    *   **Para que:** A consulta seja oficializada e o paciente receba a confirmação.
    *   **Critérios de Aceitação:**
        *   A secretária deve ter uma lista de solicitações de agendamento pendentes.
        *   Para cada solicitação, deve haver uma opção para "Confirmar" ou "Rejeitar".
        *   Ao confirmar, o status da consulta deve mudar para "Confirmada" e o horário ser alocado.
        *   O paciente deve ser notificado da confirmação.

*   **US-013: Bloquear Horários na Agenda**
    *   **Como um:** Secretária
    *   **Desejo:** Bloquear horários específicos na agenda de um médico
    *   **Para que:** Eu possa gerenciar imprevistos, reuniões ou ausências do médico, evitando agendamentos indevidos.
    *   **Critérios de Aceitação:**
        *   A secretária deve poder selecionar um ou mais blocos de horários na agenda de um médico.
        *   Os horários bloqueados devem ser claramente visíveis na agenda e não devem permitir agendamentos.
        *   Deve ser possível adicionar uma breve descrição para o bloqueio (ex: "Reunião", "Férias").

*   **US-014: Buscar Paciente Cadastrado**
    *   **Como um:** Secretária
    *   **Desejo:** Buscar um paciente já cadastrado
    *   **Para que:** Eu possa agilizar o agendamento de novas consultas ou a consulta de seus dados.
    *   **Critérios de Aceitação:**
        *   Deve haver um campo de busca na interface de gestão de pacientes.
        *   A busca deve funcionar por nome completo ou CPF do paciente.
        *   Os resultados da busca devem ser exibidos em uma lista clara.

*   **US-015: Buscar Médico Cadastrado**
    *   **Como um:** Secretária
    *   **Desejo:** Buscar um médico já cadastrado
    *   **Para que:** Eu possa visualizar sua agenda ou editar seus dados de forma rápida.
    *   **Critérios de Aceitação:**
        *   Deve haver um campo de busca na interface de gestão de médicos.
        *   A busca deve funcionar por nome do médico ou CRM.
        *   Os resultados da busca devem ser exibidos em uma lista clara.

*   **US-016: Editar Dados de Paciente**
    *   **Como um:** Secretária
    *   **Desejo:** Editar os dados de um paciente
    *   **Para que:** Eu possa manter as informações de contato e cadastro sempre atualizadas.
    *   **Critérios de Aceitação:**
        *   A secretária deve poder selecionar um paciente e acessar um formulário de edição.
        *   Todos os campos editáveis devem ser pré-preenchidos com os dados atuais do paciente.
        *   As alterações devem ser salvas e refletidas no sistema.

*   **US-017: Editar Dados de Médico**
    *   **Como um:** Secretária
    *   **Desejo:** Editar os dados de um médico
    *   **Para que:** Eu possa manter as informações de contato, especialidade ou horários atualizadas.
    *   **Critérios de Aceitação:**
        *   A secretária deve poder selecionar um médico e acessar um formulário de edição.
        *   Todos os campos editáveis devem ser pré-preenchidos com os dados atuais do médico.
        *   As alterações devem ser salvas e refletidas no sistema.

*   **US-018: Receber Confirmação de Agendamento**
    *   **Como um:** Paciente
    *   **Desejo:** Receber uma confirmação da minha solicitação de agendamento
    *   **Para que:** Eu tenha certeza que minha solicitação foi recebida e está sendo processada.
    *   **Critérios de Aceitação:**
        *   Após solicitar um agendamento, o paciente deve ver uma mensagem de sucesso na tela.
        *   O paciente deve receber um e-mail (ou SMS, se implementado) com os detalhes da solicitação e informando que aguarda confirmação.

*   **US-019: Cancelar Agendamento (Paciente)**
    *   **Como um:** Paciente
    *   **Desejo:** Poder cancelar meu próprio agendamento online
    *   **Para que:** Eu possa liberar o horário para outro paciente e evitar faltas, sem precisar ligar para a clínica.
    *   **Critérios de Aceitação:**
        *   O paciente deve poder acessar suas consultas agendadas e ter uma opção de "Cancelar".
        *   O sistema deve solicitar uma confirmação antes de efetivar o cancelamento.
        *   Após o cancelamento, o horário deve ser liberado na agenda do médico e o status da consulta atualizado.
        *   O paciente deve receber uma confirmação de cancelamento.

*   **US-020: Gerar Relatório de Consultas Diárias**
    *   **Como um:** Secretária
    *   **Desejo:** Gerar um relatório das consultas agendadas para um dia específico
    *   **Para que:** Eu possa ter um resumo rápido das atividades do dia e planejar a recepção.
    *   **Critérios de Aceitação:**
        *   A secretária deve poder selecionar uma data no calendário.
        *   O relatório deve exibir a lista de consultas para aquela data, incluindo paciente, médico, horário e status.
        *   O relatório deve ser visualizável na tela e, opcionalmente, exportável para um formato simples (ex: CSV).

*   **US-021: Gerar Relatório de Consultas por Médico**
    *   **Como um:** Secretária
    *   **Desejo:** Gerar um relatório das consultas realizadas por um médico em um período
    *   **Para que:** Eu possa acompanhar sua produtividade e o volume de atendimentos.
    *   **Critérios de Aceitação:**
        *   A secretária deve poder selecionar um médico e um intervalo de datas.
        *   O relatório deve listar todas as consultas do médico no período, com detalhes relevantes.
        *   O relatório deve incluir um total de consultas para o médico no período selecionado.

# Tecnologias Sugeridas

Para o desenvolvimento do MediAgenda, considerando uma equipe de desenvolvedores amadores, sugerimos as seguintes tecnologias, que são amplamente documentadas e possuem comunidades ativas:

*   **Frontend:**
    *   **HTML5, CSS3, JavaScript:** Fundamentais para a estrutura, estilo e interatividade da interface web.
    *   **Framework CSS (Opcional, para agilizar):** Bootstrap ou Bulma para um design responsivo e componentes pré-construídos, facilitando a criação da interface sem a necessidade de muito conhecimento em design.
    *   **Framework JavaScript (Opcional, para organização):** Vue.js (com sua abordagem progressiva e curva de aprendizado suave) ou React (com vasta documentação e comunidade) para organizar o código do frontend, embora um JavaScript puro bem estruturado também seja viável para começar.

*   **Backend:**
    *   **Python com Flask:** Flask é um microframework web em Python, leve e fácil de aprender, ideal para construir APIs RESTful que o frontend consumirá. É menos complexo que Django, tornando-o mais adequado para iniciantes.
    *   **Node.js com Express (Alternativa):** Se a equipe tiver preferência por JavaScript no backend, Node.js com Express é uma excelente alternativa, também leve e com grande comunidade.

*   **Banco de Dados:**
    *   **SQLite:** Para o desenvolvimento inicial e testes, é um banco de dados baseado em arquivo, sem a necessidade de um servidor de banco de dados separado, o que simplifica muito a configuração.
    *   **PostgreSQL:** Para uma fase posterior ou se a equipe desejar um banco de dados mais robusto e escalável desde o início, PostgreSQL é uma ótima escolha, gratuito e poderoso.

*   **Controle de Versão:**
    *   **Git:** Essencial para o trabalho em equipe, permitindo que os desenvolvedores colaborem no código de forma organizada e segura. Plataformas como GitHub ou GitLab podem ser usadas para hospedar o repositório.

Esta pilha tecnológica oferece um bom equilíbrio entre simplicidade para aprendizado e poder para construir uma aplicação web funcional e escalável no futuro.

# Considerações de Escalabilidade Futura

Embora o foco inicial do MediAgenda seja a simplicidade e a funcionalidade básica de gestão de consultas, é importante ter em mente algumas possibilidades de evolução para o futuro, que poderiam ser exploradas à medida que a equipe ganha experiência e o projeto amadurece:

*   **Integração com Prontuário Eletrônico (PEP):** Uma evolução natural seria a integração com um sistema de prontuário eletrônico simplificado, permitindo que os médicos registrem informações básicas da consulta diretamente no sistema.
*   **Módulo Financeiro Básico:** Adicionar funcionalidades para registro de pagamentos de consultas e geração de relatórios financeiros simples.
*   **Telemedicina:** Com a crescente demanda, a integração de ferramentas de videochamada para consultas online poderia ser um diferencial.
*   **Integração com Convênios:** Automatizar o processo de verificação de elegibilidade e faturamento com planos de saúde.
*   **Aplicativo Móvel para Pacientes:** Desenvolver um aplicativo nativo para iOS/Android para melhorar a experiência do paciente, com notificações push e acesso mais rápido às consultas.
*   **Inteligência Artificial para Otimização de Agenda:** Em um estágio mais avançado, algoritmos de IA poderiam sugerir otimizações na agenda para reduzir o tempo ocioso dos médicos ou minimizar o tempo de espera dos pacientes.

É crucial ressaltar que essas são apenas ideias para o futuro e não devem ser consideradas no escopo inicial para manter a simplicidade e a viabilidade do projeto para uma equipe amadora.

# Glossário de Termos

Para facilitar a compreensão de todos os envolvidos no projeto, especialmente para desenvolvedores amadores que podem não estar familiarizados com a terminologia da área da saúde ou de desenvolvimento de software, apresentamos um glossário de termos:

*   **Agendamento:** Ato de marcar uma consulta ou procedimento em uma data e hora específicas.
*   **Backlog do Produto:** Lista priorizada de tudo o que pode ser necessário no produto. É dinâmico e nunca está completo.
*   **Backend:** A parte do sistema que lida com a lógica de negócios, banco de dados e comunicação com o servidor, invisível para o usuário final.
*   **CRM (Conselho Regional de Medicina):** Registro profissional de médicos no Brasil.
*   **Épico:** Uma grande funcionalidade ou requisito que é muito amplo para ser concluído em uma única iteração e que pode ser dividido em várias Histórias de Usuário.
*   **Frontend:** A parte do sistema com a qual o usuário interage diretamente, incluindo a interface gráfica (UI) e a experiência do usuário (UX).
*   **História de Usuário (User Story):** Uma descrição informal e de alto nível de uma funcionalidade do sistema do ponto de vista do usuário, seguindo o formato "Como um <tipo de usuário>, desejo <uma funcionalidade>, para que <um benefício>."
*   **Múltipla Escolha:** Tipo de pergunta em que o respondente escolhe uma ou mais opções de uma lista predefinida.
*   **Product Owner:** Membro da equipe Scrum responsável por maximizar o valor do produto resultante do trabalho da Equipe de Desenvolvimento.
*   **Reagendamento:** Alteração da data e/ou hora de uma consulta previamente agendada.
*   **SQLite:** Um sistema de gerenciamento de banco de dados relacional que é contido em uma pequena biblioteca C. É embutido em aplicações e não requer um processo de servidor separado.
*   **Tarefa (Task):** Uma atividade específica e concreta que deve ser realizada para atender a um requisito ou concluir uma história de usuário. Geralmente, é pequena e detalhada.
*   **UI (User Interface):** Interface do Usuário. Refere-se aos elementos visuais e interativos de um software.
*   **UX (User Experience):** Experiência do Usuário. Refere-se à forma como o usuário se sente ao interagir com um software.
*   **Validação:** Processo de verificar se os dados inseridos estão corretos e seguem as regras definidas pelo sistema.


