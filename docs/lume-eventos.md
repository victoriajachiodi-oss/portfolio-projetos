# Lume Eventos

## Visão geral

Prévia de uma plataforma para convites e controle de entrada em festas, com experiências previstas para convidados, organização e equipe de portaria.

## Tecnologias e ferramentas

- **Linguagem:** TypeScript.
- **Interface:** React e Vite.
- **Bibliotecas:** html5-qrcode, qrcode.react e lucide-react.
- **Backend planejado:** Supabase para autenticação e banco de dados privado.

## Estado do projeto

A interface disponível é uma prévia local. Os dados ficam apenas na memória do navegador e são perdidos ao recarregar. A autenticação, a integração com Supabase e WhatsApp e a consulta de identidade não estão conectadas. Testes locais usam provedores simulados; não enviam mensagens nem consultam serviços oficiais. Não usar dados pessoais reais nem operar um evento com esta prévia.

## Próximos passos

Integrar e auditar autenticação e permissões no servidor, aplicar e testar as migrações em um ambiente Supabase, conectar os serviços autorizados e validar o fluxo completo antes de qualquer uso real.
