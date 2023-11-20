# Projeto de Desenvolvimento da Interface do Sistema

Este repositório contém os protótipos da interface do sistema desenvolvidos pelo grupo, conforme especificado nos diagramas de caso de uso da primeira fase do projeto. Os protótipos foram criados com o objetivo de representar as seguintes jornadas:

1. **[Cadastro de Pessoa Física](#cadastro-de-pessoa-física)**
2. **[Cadastro de Pessoa Jurídica](#cadastro-de-pessoa-jurídica)**
3. **[Cadastro de Professores](#cadastro-de-professores)**
4. **[Cadastro de Fornecedores](#cadastro-de-fornecedores)**
5. **[Cadastro de Alunos](#cadastro-de-alunos)**

<div>
  
  
![banner](https://github.com/Jessicacintra-eng/uni-24/blob/dbb7e706291b7cd4366aeedc9b9b53214770a64c/figma.png)


</div>


## Protótipos Funcionais

Os [protótipos](https://github.com/Jessicacintra-eng/uni-24/tree/9ee350cbba2e699241932982cd117016a6b99185/Prot%C3%B3tipos) funcionais foram desenvolvidos utilizando ferramentas como Miro ou Figma, refletindo fielmente o que foi modelado anteriormente na fase 1 do projeto.

**Todos os protótipos e telas podem ser conferidos no [figma do projeto](https://www.figma.com/file/8SE0CtkvsntEzb3vBdtiln/PI---3%C2%BA-Semestre?type=design&node-id=60%3A19766&mode=design&t=0m3G8i4BRks16atA-1)**

![Login](https://github.com/Jessicacintra-eng/uni-24/blob/966c91148511453a9d0081191f3e5e10c739e689/Prot%C3%B3tipos/login.png)


## Diagramas

Os diagramas criados na fase 1 do projeto estão disponíveis na pasta [diagramas](https://github.com/Jessicacintra-eng/uni-24/tree/9ee350cbba2e699241932982cd117016a6b99185/Diagramas)


![Diagramas](https://github.com/Jessicacintra-eng/uni-24/raw/9ee350cbba2e699241932982cd117016a6b99185/Diagramas/Diagramas.png)


## Descrição dos Cenários

### [Cadastro de Pessoa Física](#cadastro-de-pessoa-física)

**Cenário Principal: Cadastro de Pessoa Física**
- **Ator Principal:** Pessoa Física
- **Pré-condição:** Cadastro no sistema.
- **Pós-condição:** Pessoa Física cadastrada com sucesso.

**Fluxo Principal:**
1. Acesso à funcionalidade de cadastro.
2. Preenchimento do formulário.
3. Confirmação e solicitação do cadastro.
4. Verificação e cadastro pelo sistema.
5. Notificação de conclusão.

**Alternativas:**
1. Dados Inválidos.
2. Cancelamento do Cadastro.

### [Cadastro de Pessoa Jurídica](#cadastro-de-pessoa-jurídica)

**Cenário Principal: Cadastro de Pessoa Jurídica**
- **Ator Principal:** Pessoa Jurídica
- **Pré-condição:** Cadastro no sistema.
- **Pós-condição:** Pessoa Jurídica cadastrada com sucesso.

**Fluxo Principal:**
1. Acesso à funcionalidade de cadastro.
2. Preenchimento do formulário.
3. Confirmação e solicitação do cadastro.
4. Verificação e cadastro pelo sistema.
5. Notificação de sucesso.

**Alternativas:**
1. Dados Incompletos.
2. Cancelamento do Cadastro.

### [Cadastro de Fornecedores](#cadastro-de-fornecedores)

**Cenário Principal: Cadastro de Fornecedores**
- **Ator Principal:** Fornecedor
- **Pré-condição:** Cadastro no sistema.
- **Pós-condição:** Fornecedor cadastrado com sucesso.

**Fluxo Principal:**
1. Acesso à funcionalidade de cadastro.
2. Preenchimento do formulário.
3. Confirmação e solicitação do cadastro.
4. Verificação de campos preenchidos.
5. Notificação de finalização.

**Alternativas:**
1. Dado não aceito.
2. Dado já cadastrado.

### [Cadastro de Professores](#cadastro-de-professores)

**Cenário Principal: Cadastro de Professores**
- **Ator Principal:** Professores
- **Pré-condição:** Cadastro no sistema.
- **Pós-condição:** Professor cadastrado com sucesso.

**Fluxo Principal:**
1. Acesso à funcionalidade de cadastro.
2. Preenchimento do formulário.
3. Confirmação e solicitação do cadastro.
4. Verificação de campos preenchidos e análise de cpf.
5. Notificação de finalização.

**Alternativas:**
1. Professor não cadastrado na base.
2. Professor possui cadastro.


### [Cadastro de Alunos](#cadastro-de-alunos)

**Cenário Principal: Cadastro de Alunos**
- **Ator Principal:** Alunos
- **Pré-condição:** Cadastro no sistema.
- **Pós-condição:** Aluno cadastrado com sucesso.

**Fluxo Principal:**
1. Acesso à funcionalidade de cadastro.
2. Preenchimento do formulário.
3. Confirmação e solicitação do cadastro.
4. Verificação de campos preenchidos e análise de matrícula.
5. Notificação de finalização.

**Fluxo Alternativo 1: Matrícula Incorreta**
1. O Aluno digita uma matrícula incorreta.
2. Recebe uma mensagem informando que a informação está incorreta.
3. O sistema indica que o aluno deve tentar novamente.
4. Ao errar novamente, o sistema oferece a opção de entrar em contato com a secretária da universidade.
5. Uma opção de voltar à página principal é disponibilizada.

**Fluxo Alternativo 2: Dado Incompleto**
1. O Aluno não informa a matrícula no cadastro.
2. O sistema exibe uma mensagem de erro indicando que o cadastro está incompleto, apontando os campos a serem preenchidos.
3. O sistema oferece a opção para o aluno entrar em contato com a secretária da universidade.
4. Uma opção de voltar à página principal é apresentada.
---

## Contribuições

Contribuições para a melhoria dos protótipos ou qualquer outra parte do projeto são bem-vindas. Sinta-se à vontade para abrir problemas (issues) ou enviar pull requests.

Obrigado por contribuir para o desenvolvimento deste projeto!

---
