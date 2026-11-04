# Refúgio Cachoeira Guaibim

Site de hospedagem por temporada na Praia de Guaibim, em Valença, Bahia.

HTML, CSS e JavaScript, sem etapa de build. Inclui galeria com 24 fotos reais, comodidades e consulta de datas pelo WhatsApp, além de links para Booking e Airbnb.

## Prévia local

```sh
python -m http.server 8769 --directory dist
```

Abra http://localhost:8769 no navegador.

## Publicação

O projeto usa Vercel com `framework: null` e diretório de saída `dist`. A branch de produção é `main`.

## Bibliotecas e conteúdo

- [PhotoSwipe 5.4.4](https://github.com/dimsemenov/PhotoSwipe): galeria com zoom e navegação por toque e teclado.
- [Lucide](https://github.com/lucide-icons/lucide): ícones SVG.
- As licenças das bibliotecas estão preservadas em `dist/vendor`.
- Fotografias e identidade pertencem aos respectivos titulares e não recebem uma licença de redistribuição por estarem neste repositório.
- Consulte [REFERENCES.md](REFERENCES.md) para fontes e versões.
