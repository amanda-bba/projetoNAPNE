### **Caso de Uso 1 — Login do Usuário**

**Ator:** Usuário do sistema  
**Objetivo:** Realizar login no sistema  
**Descrição:** O usuário insere seu e-mail e senha para acessar a plataforma.  

**Fluxo Principal:**
1. O usuário acessa a tela de login.  
2. Digita e-mail e senha.  
3. Clica em “Entrar”.  
4. O sistema valida as credenciais e redireciona o usuário para a página inicial.  

**Fluxos Alternativos:**
- Credenciais incorretas: o sistema exibe uma mensagem de erro e solicita nova tentativa.  

---

### **Caso de Uso 2 — Selecionar ou Cadastrar Condição do Aluno**

**Ator:** Usuário do sistema  
**Objetivo:** Selecionar ou cadastrar a condição do aluno  
**Descrição:** O usuário informa sua condição (como deficiência visual, auditiva ou motora) para que o sistema adapte a interface e os recursos conforme a necessidade.  

**Fluxo Principal:**
1. O usuário acessa a área de perfil.  
2. Seleciona ou cadastra sua condição.  
3. O sistema adapta automaticamente as configurações de interface e recursos.  

**Fluxos Alternativos:**
- Caso o usuário não selecione nenhuma condição, o sistema mantém a interface padrão.  

---

### **Caso de Uso 3 — Enviar Notas e Avisos**

**Ator:** Professor  
**Objetivo:** Enviar notas e avisos aos alunos  
**Descrição:** O professor acessa o espaço dedicado no sistema para publicar avisos e notas.  

**Fluxo Principal:**
1. O professor realiza login.  
2. Acessa a área de “Avisos e Notas”.  
3. Cria uma nova mensagem e insere o conteúdo.  
4. Clica em “Publicar”.  
5. O sistema envia o aviso aos alunos e responsáveis.  

**Fluxos Alternativos:**
- Caso o campo de mensagem esteja vazio, o sistema exibe um aviso de preenchimento obrigatório.  

---

### **Caso de Uso 4 — Criar, Editar e Excluir Cronogramas**

**Ator:** Professor  
**Objetivo:** Gerenciar cronogramas de atividades  
**Descrição:** O professor cria, edita e exclui cronogramas de provas, atividades e compromissos para manter os alunos informados.  

**Fluxo Principal:**
1. O professor acessa a área de cronogramas.  
2. Cria ou edita um cronograma.  
3. Define datas, horários e descrições.  
4. Salva as alterações.  
5. O sistema atualiza automaticamente as informações para os alunos.  

**Fluxos Alternativos:**
- Caso ocorra erro de conexão, o sistema informa que o cronograma não pôde ser salvo.  

---

### **Caso de Uso 5 — Compartilhar Cronogramas**

**Ator:** Professor  
**Objetivo:** Compartilhar cronogramas com o NAPNE e responsáveis autorizados  
**Descrição:** O professor envia cronogramas de atividades ao NAPNE e responsáveis para acompanhamento dos alunos.  

**Fluxo Principal:**
1. O professor seleciona o cronograma.  
2. Clica na opção “Compartilhar”.  
3. Escolhe enviar para NAPNE e/ou responsáveis.  
4. O sistema disponibiliza o cronograma para visualização.  

**Fluxos Alternativos:**
- Caso o compartilhamento falhe, o sistema exibe uma mensagem de erro.  

---

### **Caso de Uso 6 — Acessibilidade Personalizada**

**Ator:** Aluno com deficiência  
**Objetivo:** Usar recursos personalizados conforme sua necessidade  
**Descrição:** O aluno acessa o sistema com recursos específicos de acessibilidade adaptados à sua condição.  

**Fluxo Principal:**
1. O aluno realiza login.  
2. O sistema identifica sua condição cadastrada.  
3. Ativa automaticamente os recursos personalizados:  
   - Leitor de tela e navegação por toque (para alunos cegos).  
   - Legendas e narração de ícones (para alunos surdos).  
   - Controle por voz (para alunos com dificuldades motoras).  

**Fluxos Alternativos:**
- Caso o recurso de acessibilidade falhe, o sistema oferece modo padrão com suporte técnico.  
