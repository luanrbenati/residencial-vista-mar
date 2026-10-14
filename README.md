# Residencial Vista Mar — Landing Page Imobiliária

Landing page **demonstrativa** de lançamento imobiliário, desenvolvida para portfólio. Empreendimento, localização, metragens, plantas e contatos são **fictícios**. Fotografias ilustrativas carregadas do Unsplash.

## Recursos
- Design premium, mobile-first e responsivo
- Navegação com menu mobile e âncoras
- Galeria de fotos interativa
- Alternância entre duas plantas **esquemáticas, sem escala**
- Formulário com validação HTML e consentimento, que prepara uma mensagem no WhatsApp
- CTA flutuante de WhatsApp
- Metadados básicos de SEO, labels acessíveis e suporte a redução de movimento

## Como executar

Requisitos: Node.js 20.19+ ou 22.12+.

```bash
npm install
npm run dev
```

Abra o endereço exibido no terminal. Para compilar:

```bash
npm run build
npm run preview
```

## Personalização antes de publicar para um cliente
1. Em `src/App.tsx`, substitua `WA_NUMBER` pelo telefone real com DDI e DDD, somente números.
2. Substitua textos, imagens, metragens, plantas e localização por materiais oficiais do empreendimento.
3. As plantas atuais são apenas diagramas demonstrativos; **não** representam projetos arquitetônicos.
4. O formulário **não armazena dados nem envia e-mail**: ele abre o WhatsApp com uma mensagem preenchida. Se o cliente exigir captura de leads, implemente backend/CRM ou um provedor de formulários e política de privacidade adequada.
5. Troque as fotos ilustrativas por imagens com licença apropriada e autorização de uso comercial.
6. Atualize SEO, domínio, redes sociais e informações legais.

## Publicação na Vercel
Faça push do projeto no GitHub, importe o repositório na Vercel, selecione o framework **Vite**, comando `npm run build` e diretório de saída `dist`.

## Stack
React, TypeScript, Vite, CSS responsivo, Lucide React.

> Este é um estudo de design e desenvolvimento. Não há empreendimento à venda, preços ou oferta comercial real.
