# SICA v3.0 Cloud Base

Versão inicial da migração para Supabase.

## Incluído
- Supabase Auth (cadastro, login, sessão e logout)
- Perfis, aprovação e papéis via tabela `profiles`
- Preservação integral dos dados existentes no localStorage
- Exportação preventiva de backup JSON após o primeiro login

## Próxima etapa
Migrar os módulos acadêmicos do localStorage para as tabelas Supabase já criadas.
