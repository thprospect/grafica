# Gráfica MCR - Site estático para GitHub + Vercel

## Estrutura

```txt
public/
  index.html
  assets/
package.json
vercel.json
.gitignore
```

## Como subir no GitHub

1. Crie um repositório no GitHub.
2. Envie todos os arquivos desta pasta para a raiz do repositório.
3. Confirme que a pasta `public` está na raiz e contém o `index.html`.

## Como publicar na Vercel

1. Importe o repositório na Vercel.
2. Framework Preset: `Other`.
3. Build Command: `npm run build` ou deixe vazio.
4. Output Directory: `public`.
5. Deploy.

Este pacote já inclui `vercel.json` com `outputDirectory: "public"` para evitar o erro de diretório de saída.
