#Caso de Uso 1 — Login do Usuário

Ator: Usuário do sistema

Objetivo: Realizar login no sistema

Descrição: O usuário acessa a plataforma por meio da tela de login.

- Fluxo Principal:

O usuário acessa a tela inicial do sistema.

O usuário informa o e-mail.

O usuário informa a senha.

O usuário clica em “Entrar”.

O sistema valida os dados e direciona o usuário para a próxima tela.

- Fluxos Alternativos:

Dados incorretos: o sistema exibe uma mensagem de erro e solicita nova tentativa.

#Caso de Uso 2 — Selecionar Condição do Aluno

Ator: Usuário do sistema

Objetivo: Selecionar a condição do aluno

Descrição: O usuário seleciona sua condição conforme apresentado na tela do sistema.

- Fluxo Principal:

O usuário acessa a tela de condição.

O usuário seleciona uma das opções disponíveis.

O usuário confirma a seleção.

O sistema salva a condição escolhida.

- Fluxos Alternativos:

Caso nenhuma condição seja selecionada, o sistema mantém a configuração padrão.

#Caso de Uso 3 — Enviar Avisos

Ator: Professor

Objetivo: Enviar avisos aos alunos

Descrição: O professor publica avisos por meio da funcionalidade disponível no sistema.

- Fluxo Principal:

O professor realiza login.

O professor acessa a opção de avisos.

O professor escreve o aviso.

O professor clica em “Publicar”.

O sistema disponibiliza o aviso aos alunos.

- Fluxos Alternativos:

Caso o aviso esteja vazio, o sistema solicita o preenchimento do conteúdo.

#Caso de Uso 4 — Criar e Editar Cronogramas

Ator: Professor

Objetivo: Criar e editar cronogramas

Descrição: O professor gerencia cronogramas conforme apresentado no sistema.

- Fluxo Principal:

O professor acessa a área de cronogramas.

O professor cria ou edita um cronograma.

O professor define as informações solicitadas.

O professor salva o cronograma.

O sistema atualiza o cronograma para os alunos.

- Fluxos Alternativos:

Caso ocorra erro ao salvar, o sistema informa a falha.

#Caso de Uso 5 — Acessibilidade Personalizada

Ator: Aluno

Objetivo: Utilizar acessibilidade personalizada

Descrição: O aluno utiliza o sistema com recursos adaptados à condição selecionada.

- Fluxo Principal:

O aluno realiza login.

O sistema reconhece a condição cadastrada.

O sistema aplica automaticamente as configurações de acessibilidade.

- Fluxos Alternativos:

Caso a adaptação não seja aplicada, o sistema mantém a interface padrão.

#Caso de Uso 6 — Elaborar Relatório do Aluno (NAPNE)

Ator: Servidor do NAPNE

Objetivo: Elaborar relatório de acompanhamento do aluno

Descrição: O servidor do NAPNE registra o acompanhamento do aluno conforme suas necessidades.

- Fluxo Principal:

O servidor do NAPNE realiza login no sistema.

O servidor acessa a área de alunos.

O servidor seleciona um aluno.

O servidor preenche o relatório com as necessidades e acompanhamentos do aluno.

O servidor salva o relatório.

- Fluxos Alternativos:

Caso algum campo obrigatório não seja preenchido, o sistema solicita a correção.

#Caso de Uso 7 — Publicar Relatório do Aluno (NAPNE)

Ator: Servidor do NAPNE

Objetivo: Publicar relatório de acompanhamento

Descrição: O servidor do NAPNE publica o relatório no sistema para consulta.

- Fluxo Principal:

O servidor do NAPNE acessa um relatório criado.

O servidor seleciona a opção “Publicar”.

O sistema disponibiliza o relatório no ambiente do NAPNE.

- Fluxos Alternativos:

Caso a publicação falhe, o sistema exibe uma mensagem de erro.

#Caso de Uso 8 — Visualizar Acompanhamento do Aluno (NAPNE)

Ator: Servidor do NAPNE

Objetivo: Visualizar o acompanhamento do aluno

Descrição: O servidor do NAPNE visualiza os relatórios e informações registradas do aluno.

- Fluxo Principal:

O servidor do NAPNE acessa a área do aluno.

O sistema exibe os relatórios e registros de acompanhamento.

- Fluxos Alternativos:

Caso não existam relatórios, o sistema informa que não há registros disponíveis.