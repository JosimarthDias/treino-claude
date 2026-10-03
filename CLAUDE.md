# CLAUDE.md

Regras para o Claude seguir ao trabalhar neste repositório.

## Sobre o projeto

- É o site de artista do Josimarth, feito em um único arquivo: `index.html`.
- O CSS (o estilo da página) fica dentro do próprio `index.html`, num bloco `<style>`. Não crie arquivos separados de CSS.
- As exceções são as fotos, que ficam na pasta `imagens/`, e os arquivos para baixar (como o PDF da ficha técnica e o QR Code), que ficam na pasta `arquivos/`. Colocá-los dentro do HTML deixaria a página pesada.
- Também ficam na raiz do projeto: `404.html` (a página de "não encontrada", com o CSS dentro dela, como no `index.html`), `robots.txt` e `sitemap.xml` (arquivos que ajudam o Google a encontrar o site) e `CNAME` (o domínio).

## Regras

1. **Idioma e jeito de falar:** sempre responda em português do Brasil, de forma simples. Quando usar um termo técnico, explique o que ele significa.
2. **Antes de mudar algo:** diga em uma frase o que você vai fazer.
3. **Segurança:** nunca coloque dados pessoais, senhas ou chaves (de API, de acesso etc.) no código. A única exceção é o WhatsApp de contato profissional, que o Josimarth autorizou a deixar público no site.
4. **Ao terminar:** resuma o que mudou em poucas linhas.
