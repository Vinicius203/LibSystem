```markdown
# Canvas do Product Backlog Building (PBB) - LibSystem

Este canvas descreve o backlog inicial do produto **LibSystem**, focando nas funcionalidades essenciais para a primeira onda de entrega, conforme o modelo PBB.

---

## 1. Produto

| Atributo              | Descrição                                                                 |
|-----------------------|---------------------------------------------------------------------------|
| **Nome do Produto**   | LibSystem                                                                 |
| **Visão / Proposta**  | Um sistema para gerenciar o acervo e as operações de uma biblioteca, facilitando o controle de livros, usuários e empréstimos online. |

---

## 2. Problemas (Estado Atual)

| Problema / Dor                | Descrição                                                                 |
|------------------------------|---------------------------------------------------------------------------|
| Controle Manual de Empréstimos | O registro é feito em papel ou planilhas, sujeito a erros, perdas e inconsistências. |
| Falta de Visibilidade do Acervo | Membros não conseguem saber se um livro está disponível sem ir à biblioteca. |
| Gestão de Usuários Ineficiente | Dificuldade para manter os dados dos membros atualizados e controlar quem está com livros. |
| Processo Lento e Burocrático   | Cadastrar um livro novo ou realizar um empréstimo manualmente toma muito tempo do bibliotecário. |

---

## 3. Expectativas (Estado Desejado)

| Expectativa / Ganho           | Descrição                                                                 |
|------------------------------|---------------------------------------------------------------------------|
| Controle Automatizado e Confiável | Ter um histórico seguro de todos os empréstimos, com datas e responsáveis claros. |
| Consulta Online ao Acervo    | Permitir que qualquer membro possa verificar a disponibilidade dos livros remotamente. |
| Base de Usuários Centralizada | Gerenciar facilmente os membros, seus históricos e status (ex: com ou sem pendências). |
| Agilidade nas Operações      | Reduzir drasticamente o tempo gasto em tarefas operacionais, como cadastros e empréstimos. |

---

## 4. Personas

| Persona                     | Perfil / Papel                                                                 | Necessidades / Objetivos                                                                 |
|----------------------------|----------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------|
| **Bibliotecário(a)**       | Responsável por gerenciar o acervo, cadastrar novos membros e operar o sistema no dia a dia. | Superar a lentidão do processo manual, ter controle e organização do acervo e dos empréstimos. |
| **Membro da Biblioteca**   | Usuário final que pega livros emprestados.                                     | Saber quais livros estão disponíveis e realizar empréstimos de forma simples e rápida.    |

---

## 5. Funcionalidades (1ª Onda)

| ID   | Nome da Funcionalidade  | Descrição Breve                                                                 | Resultado Esperado / Meta                                                                 |
|------|--------------------------|----------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------|
| F01  | Cadastro de Livros       | Permite que o bibliotecário adicione novos livros ao acervo do sistema.         | O acervo da biblioteca pode ser digitalizado e gerenciado pelo sistema, atacando o problema da falta de visibilidade. |
| F02  | Cadastro de Usuários     | Permite que o bibliotecário cadastre novos membros na biblioteca.               | Os leitores são formalmente registrados para um controle eficiente e centralizado.         |
| F03  | Empréstimo de Livros     | Permite registrar a saída de um livro para um membro específico.                | Automatizar e controlar quais livros estão emprestados, para quem e a data de devolução.   |

---

## 6. Itens do Backlog (Mapeamento Funcionalidade → Ação → Item)

| Persona         | Funcionalidade         | Ação / Passo da Jornada            | Item do Backlog (História de Usuário)                                                                                  |
|-----------------|------------------------|------------------------------------|------------------------------------------------------------------------------------------------------------------------|
| Bibliotecário(a) | F01 - Cadastro de Livros | Adicionar um novo livro            | Como um(a) Bibliotecário(a), eu quero cadastrar um novo livro informando Título, Autor, ISBN e Quantidade, para que ele passe a fazer parte do acervo disponível para empréstimo. |
| Bibliotecário(a) | F01 - Cadastro de Livros | Editar um livro existente          | Como um(a) Bibliotecário(a), eu quero editar as informações de um livro já cadastrado, para que eu possa corrigir ou atualizar seus dados. |
| Bibliotecário(a) | F01 - Cadastro de Livros | Visualizar lista de livros         | Como um(a) Bibliotecário(a), eu quero visualizar a lista de todos os livros cadastrados, para que eu tenha uma visão geral do acervo. |
| Bibliotecário(a) | F02 - Cadastro de Usuários | Adicionar um novo membro          | Como um(a) Bibliotecário(a), eu quero cadastrar um novo membro (leitor) informando Nome, CPF e Contato, para que ele esteja apto a realizar empréstimos. |
| Bibliotecário(a) | F03 - Empréstimo de Livros | Registrar um empréstimo           | Como um(a) Bibliotecário(a), eu quero registrar um empréstimo de um livro para um membro, para que o sistema controle o item emprestado e a data de devolução. |
| Bibliotecário(a) | F03 - Empréstimo de Livros | Validar disponibilidade            | Como um(a) Bibliotecário(a), ao tentar realizar um empréstimo, eu quero que o sistema verifique a disponibilidade do livro, para evitar emprestar um item que não está no acervo. |

---
```
