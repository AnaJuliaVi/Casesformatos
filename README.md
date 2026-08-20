# Cases de Formatos

Portal React + TypeScript + Vite com busca, filtros, galeria, múltiplas imagens, edição, exclusão, tela cheia e persistência local.

## Rodar localmente

```bash
npm install
npm run dev
```

## Publicar no Vercel

1. Envie esta pasta para um repositório no GitHub.
2. Importe o repositório no Vercel.
3. Framework: Vite.
4. Build command: `npm run build`.
5. Output directory: `dist`.

## Dados

A versão atual usa `localStorage`. Imagens enviadas também ficam localmente no navegador. Para uso compartilhado, substitua a persistência por Supabase, SharePoint ou API corporativa.

## Segurança

Não há credenciais fixas no frontend. Use `.env` somente para endereços/configurações públicas. Segredos devem ficar no backend.
