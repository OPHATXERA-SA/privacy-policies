# Políticas de Privacidade — OPHATXERA

Site estático com as políticas de privacidade das apps publicadas na Google Play.

## Publicar (GitHub Pages)

1. `git push` para `OPHATXERA-SA/privacy-policies`.
2. No GitHub: **Settings → Pages → Source: Deploy from a branch → `main` / `(root)`**.
3. O site fica em `https://ophatxera-sa.github.io/privacy-policies/`.
   (Opcional: domínio próprio, ex. `privacy.ophatxera.com`, com um ficheiro `CNAME`.)

URL a colocar no Play Console (*Conteúdo da app → Política de privacidade*):

| App  | URL |
|------|-----|
| YPOS | `https://ophatxera-sa.github.io/privacy-policies/ypos/` |

## Adicionar uma nova app

1. Copie a pasta `_modelo/` para `nome-da-app/`.
2. Substitua `NOME_APP`, `PACOTE`, `DATA` e preencha as secções 1–4 conforme o que a app realmente faz.
   O conteúdo tem de corresponder ao formulário **Segurança dos dados** do Play Console.
3. Remova a linha `<meta name="robots" content="noindex">`.
4. Acrescente um `<li>` em `index.html` e uma linha na tabela acima.
