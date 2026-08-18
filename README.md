# movimentar-erp-docs

Documentação pública do **Movimentar ERP**, servida por
[docs.page](https://docs.page/devjotaduo/movimentar-erp-docs).

O código do ERP e o material de cliente ficam no repositório **privado**
`devjotaduo/movimentar-erp`. Este repositório é público: nada que não possa ser
lido por qualquer pessoa entra aqui.

- `docs.json` — configuração do site (sidebar, tema, MCP)
- `docs/**/*.mdx` — as páginas

Publicar é empurrar para `main`; não há build.

```bash
npx @docs.page/cli check      # lint de links, assets e metadados
npx @docs.page/cli preview    # preview local
```
