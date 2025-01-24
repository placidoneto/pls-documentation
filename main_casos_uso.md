# Especificação de Casos de Uso do Sistema

## Sumário
- [Introdução](#introdução)
- [Casos de Uso Funcionais](#casos-de-uso-funcionais)
- [Casos de Uso Não Funcionais](#casos-de-uso-não-funcionais)
- [Pré-condições e Pós-condições](#pré-condições-e-pós-condições)
- [Regras de Negócio](#regras-de-negócio)
- [Exceções](#exceções)

## Introdução
Bem-vindo à especificação de casos de uso do sistema. Este documento descreve os casos de uso funcionais e não funcionais para orientar o desenvolvimento e a implementação do sistema.

## Casos de Uso Funcionais
| Código  | Nome                    | Descrição                                                | Link                                         |
|---------|-------------------------|----------------------------------------------------------|----------------------------------------------|
| CU001   | Registrar Usuário       | Permitir que um visitante crie uma conta no sistema.     | [Registrar Usuário](#caso-de-uso-registrar-usuário) |
| CU002   | Fazer Login             | Autenticar um usuário com e-mail e senha.                | [Fazer Login](#caso-de-uso-fazer-login)      |
| CU003   | Recuperar Senha         | Permitir que um usuário recupere a senha esquecida.      | [Recuperar Senha](#caso-de-uso-recuperar-senha) |
| CU004   | Atualizar Perfil        | Permitir que um usuário atualize suas informações.       | [Atualizar Perfil](#caso-de-uso-atualizar-perfil) |

## Casos de Uso Não Funcionais
| Código  | Nome                    | Descrição                                                | Link                                         |
|---------|-------------------------|----------------------------------------------------------|----------------------------------------------|
| CUF001  | Tempo de Resposta       | Definir o tempo máximo de resposta do sistema.           | [Tempo de Resposta](#caso-de-uso-tempo-de-resposta) |
| CUF002  | Segurança de Dados      | Estabelecer as diretrizes para a segurança de dados.     | [Segurança de Dados](#caso-de-uso-segurança-de-dados) |
| CUF003  | Escalabilidade          | Definir os requisitos de escalabilidade do sistema.      | [Escalabilidade](#caso-de-uso-escalabilidade) |

## Pré-condições e Pós-condições
### Pré-condições
- O sistema deve estar em funcionamento.
- O usuário deve estar conectado à internet.

### Pós-condições
- Os dados do usuário são armazenados com sucesso.
- O usuário recebe notificações pertinentes.

## Regras de Negócio
- Cada e-mail deve ser único no sistema.
- As senhas devem atender aos critérios de segurança definidos.

## Exceções
- Falha na conexão com o servidor.
- Entrada de dados inválida ou incompleta.

## Casos de Uso Detalhados

### Caso de Uso: Registrar Usuário
**Código do Caso de Uso:** CU001  
[Ver Especificação Detalhada](#registrar-usuário)

### Caso de Uso: Fazer Login
**Código do Caso de Uso:** CU002  
[Ver Especificação Detalhada](#fazer-login)

### Caso de Uso: Recuperar Senha
**Código do Caso de Uso:** CU003  
[Ver Especificação Detalhada](#recuperar-senha)

### Caso de Uso: Atualizar Perfil
**Código do Caso de Uso:** CU004  
[Ver Especificação Detalhada](#atualizar-perfil)

### Caso de Uso: Tempo de Resposta
**Código do Caso de Uso:** CUF001  
[Ver Especificação Detalhada](#tempo-de-resposta)

### Caso de Uso: Segurança de Dados
**Código do Caso de Uso:** CUF002  
[Ver Especificação Detalhada](#segurança-de-dados)

### Caso de Uso: Escalabilidade
**Código do Caso de Uso:** CUF003  
[Ver Especificação Detalhada](#escalabilidade)
