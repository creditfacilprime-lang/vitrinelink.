# VitrineLink — MVP demonstrativo

Projeto inicial de uma vitrine de produtos com links individuais por publicação e carrinho próprio.

## Tecnologias
- React + Vite
- React Router
- Lucide React
- CSS responsivo

## Rodar localmente
1. Instale Node.js (versão LTS).
2. Abra o terminal nesta pasta.
3. Execute `npm install`.
4. Execute `npm run dev`.
5. Abra o endereço local indicado pelo Vite.

## Publicar no GitHub
1. Crie um repositório vazio chamado `vitrinelink` no GitHub.
2. Envie todos os arquivos desta pasta (não envie `node_modules`).
3. Para clonar e enviar pelo terminal:

```bash
git init
git add .
git commit -m "Primeira versão do VitrineLink"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/vitrinelink.git
git push -u origin main
```

## Verificar com Wappalyzer
Depois de publicar o projeto em um domínio público, abra o domínio e use a extensão Wappalyzer. Ela deverá reconhecer React e outras tecnologias detectáveis. Wappalyzer apenas identifica tecnologias; não cria o site.

## O que é apenas demonstração nesta versão
- Produtos e imagens são exemplos.
- O carrinho funciona no navegador durante a sessão, mas não salva pedidos em banco de dados.
- O botão de checkout é demonstrativo: nenhum pagamento é cobrado.
- Não há login, painel administrativo, estoque, cálculo de frete, emissão fiscal ou integração real de pagamento.

## Próximas etapas para produção
1. Backend e banco de dados (por exemplo, Supabase).
2. Cadastro/autenticação de lojistas e catálogo persistente.
3. Pedidos, estoque, frete, políticas de troca e privacidade.
4. Integração com um PSP/gateway autorizado, com webhooks e validação de pagamento no servidor.
5. Analytics e atribuição de vendas por link, com consentimento e política de privacidade.
6. Revisão de segurança e testes antes de aceitar pagamentos reais.

**Importante:** links externos podem ser compartilhados em espaços permitidos pelo TikTok, mas não podem ser inseridos como um botão de compra arbitrário na legenda nativa nem substituir o checkout do TikTok Shop.
