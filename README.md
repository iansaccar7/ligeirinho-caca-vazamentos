# Ligeirinho Caça Vazamentos

Site estático com layout responsivo, animações ao rolar e formulário de contato pelo WhatsApp.

## Executar localmente

Abra `index.html` ou sirva esta pasta:

```sh
python3 -m http.server 8000
```

Acesse http://localhost:8000. Não há instalação de dependências nem etapa de build.

## Arquivos

- `index.html`: conteúdo e formulário.
- `style.css`: layout, tipografia e responsividade.
- `script.js`: validação, mensagem do WhatsApp e ano do rodapé.
- `motion.css` e `motion.js`: animações progressivas, com suporte a movimento reduzido. Sem JavaScript, o conteúdo continua visível.
- Fontes locais DM Sans e Barlow Condensed, acompanhadas de suas licenças OFL.

Contato: (11) 95927-2852. O formulário prepara uma mensagem para https://wa.me/5511959272852; o envio final acontece no WhatsApp. Nenhum dado é armazenado pelo site.

## Hospedagem

Publique o conteúdo desta pasta na raiz de qualquer hospedagem estática. Para GitHub Pages, selecione a branch `main` e a pasta `/ (root)` nas configurações de Pages.

## Verificação

Versão conferida em Chrome em 320, 390, 768 e 1440 px: responsividade, rótulos, navegação, formulário, destino do WhatsApp e animações. Conteúdo comercial fornecido pelo usuário.
