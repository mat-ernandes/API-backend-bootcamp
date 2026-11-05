# API-backend-bootcamp

## Sobre o projeto

API backend segura para lembrete e confirmação de sessões de um consultório de psicologia. 24h antes da sessão, o paciente recebe um e-mail com link de uso único para confirmar, cancelar ou pedir remarcação, e a psicóloga acompanha o status de cada sessão.

Projeto da disciplina de Backend (Bootcamp Web com Backend Integrado), com foco em segurança.

## Tecnologias previstas

- PHP
- Laravel
- Laravel Sanctum
- MySQL
- Mailpit

## Segurança prevista

- Hash de senha (argon2id)
- Autenticação por token (Sanctum)
- Controle de acesso
- Tokens de uso único guardados como hash e com expiração
- Criptografia dos dados de contato dos pacientes
- Rate limit
- Validação de entrada
