# E+ v25 — Projeto estático

Aplicação de estudos preparada para GitHub e Vercel, sem etapa de build.

## Publicação

1. Extraia a pasta do projeto em `C:\Users\atill\OneDrive\Desktop\SaaS`.
2. Crie um repositório no GitHub e envie **o conteúdo** desta pasta (incluindo `index.html`, `assets/` e `vercel.json`).
3. Na Vercel, clique em **Add New > Project**, importe o repositório.
4. Selecione **Framework Preset: Other**, deixe **Build Command** vazio e **Output Directory** sem configuração (raiz do projeto).
5. Clique em **Deploy**.

## Execução local

Abra `index.html` no navegador. Para testar com servidor local, execute `python -m http.server 8000` na pasta e abra `http://localhost:8000`.

## Persistência e limitações

Os dados ficam no `localStorage` do navegador e **não** são sincronizados entre aparelhos ou navegadores. O aplicativo não possui autenticação, API ou banco de dados. Utilize a aba Backup para exportar seus dados regularmente. A implantação pública não torna o protótipo um SaaS multiusuário.

## Arquivos

- `index.html`: estrutura da aplicação
- `assets/style.css`: estilos
- `assets/app.js`: funcionalidades do E+ v25
- `vercel.json`: configuração de publicação estática

## Observação

O código da versão 25 foi preservado na separação dos arquivos; não foi realizada auditoria funcional completa.
