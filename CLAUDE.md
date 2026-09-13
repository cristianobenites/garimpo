# Garimpo (bootcamp)

> Responda sempre em português brasileiro (pt-BR).

## Publicação automática

Este projeto publica pela integração GitHub → Vercel: **push na `main` = site no ar**.

- Ao terminar QUALQUER mudança pedida pelo usuário: `git add -A`, commit (Conventional Commits, em pt-BR) e `git push origin main`. Não pergunte, é o fluxo padrão deste projeto.
- Depois do push, confirme o deploy com `npx vercel ls` (ou aguarde ~1 min) e entregue o link do site no ar.
- Se o build falhar na Vercel, leia o erro com `npx vercel logs` / `npx vercel inspect`, corrija e faça push de novo.
- Segredos (chaves de API, senhas) nunca vão para o código: use `npx vercel env add` e arquivos `.env*` (já no .gitignore).

## Serviços

- GitHub: repositório `garimpo` (conta cristianobenites)
- Vercel: projeto `garimpo` (conta cristianobenites)
- Supabase: projeto `garimpo` (ver `~/.garimpo/` para a senha do banco)
