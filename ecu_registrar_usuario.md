# Caso de Uso: Registrar Usuário

## 1. Identificação
**Nome do Caso de Uso:** Registrar Usuário  
**Código do Caso de Uso:** ECU001  
**Ator Principal:** Novo Usuário do Sistema

## 2. Descrição
Permitir que um novo usuario possa criar uma conta no sistema, fornecendo informações pessoais e de autenticação.

## 3. Fluxo Principal
1. O novo usuário acessa a página de registro.
2. O sistema exibe o formulário de registro.
3. O novo usuário preenche o formulário com as informações necessárias (nome, e-mail, senha, perfil, etc.).
4. O novo usuário envia o formulário.
5. O sistema valida as informações fornecidas.
6. O sistema cria uma nova conta para o novo usuário.
7. O novo usuário deve esperar a validação da sua conta.

## 4. Fluxos Alternativos
### 4.1. Fluxo Alternativo 1: Falha na Validação das Informações
- 5a. O sistema detecta que as informações fornecidas são inválidas ou incompletas.
- 5b. O sistema exibe uma mensagem de erro e solicita a correção das informações.
- 5c. O novo usuário corrige as informações e reenvia o formulário.

### 4.2. Fluxo Alternativo 2: E-mail Já Cadastrado
- 5a. O sistema detecta que o e-mail fornecido já está cadastrado.
- 5b. O sistema exibe uma mensagem informando que o e-mail já está em uso e solicita um novo e-mail.
- 5c. O visitante fornece um novo e-mail e reenvia o formulário.

## 5. Pré-condições
- O novo usuário não deve estar logado no sistema.
- O sistema deve estar funcionando corretamente.

## 6. Pós-condições
- O novo usuário tem uma nova conta registrada no sistema.
- O novo usuário pode fazer login utilizando as credenciais fornecidas após a validação da sua conta.

## 7. Regras de Negócio
- O e-mail fornecido deve ser único no sistema.
- A senha deve atender aos critérios de segurança definidos pelo sistema.

## 8. Exceções
- Falha na criação da conta devido a erros internos do sistema.

