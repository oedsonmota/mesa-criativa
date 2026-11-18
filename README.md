# Mesa Criativa

Versão de teste da Mesa Criativa: o lugar único de trabalho do profissional criativo (projetos, documentos, notas, agenda, clientes, financeiro, kit de marca, segundo cérebro, IA e apps).

- Site: página única (`index.html`), publicada pelo GitHub Pages.
- Login e dados: Supabase (tabela `mesa_workspaces`, uma linha por pessoa, protegida por RLS; feedback em `mesa_feedback`).
- A chave usada no site é a chave pública (publishable) do Supabase.
