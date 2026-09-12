# Tokuinfo — Informações sobre Tokusatsus

**Aluno:** Henrique Simões Izabel  
**Disciplina:** Desenvolvimento Web III 
**Atividade:** 01 — Mini Portal Responsivo

Portal de informações sobre tokusatsus, com apresentação de seis séries, galeria de imagens e detalhes dos heróis. Projeto acadêmico estático, construído com HTML5, Bootstrap 5.3.8 via CDN e um arquivo CSS para ajustes visuais, sem template pronto.

## Como abrir

Abra `index.html` diretamente em um navegador. É necessário estar conectado à internet para carregar o CSS e o JavaScript do Bootstrap pelo CDN. As imagens estão na pasta `img/`. Não é necessário instalar dependências ou executar servidor, Node.js, API ou banco de dados.

## Organização

```text
index.html       # Página, cards, carousel e modais
css/style.css    # Cores, tipografia e ajustes das imagens
img/             # Imagens locais dos personagens
README.md        # Apresentação e instruções
```

## Requisitos da atividade

- Navbar com marca e quatro opções de navegação, recolhida em telas menores.
- Hero abaixo do menu com título, texto e botão.
- Grid Bootstrap com `container`, `row`, `col-12`, `col-md-6` e `col-lg-4`.
- Seis cards com título, texto e botão: uma coluna no celular, duas no tablet e três em telas grandes.
- Carousel Bootstrap com três imagens e controles anterior/próximo. A troca é manual para permitir a leitura no próprio ritmo.
- Seis modais Bootstrap com informações específicas das séries, acessíveis pelos cards e pelo carousel.
- Seção adicional explicando o que é tokusatsu.
- Rodapé com identificação do projeto, do aluno e da disciplina.
- Bootstrap 5 via CDN, incluindo o bundle JavaScript para menu, carousel e modais. Sem JavaScript próprio.

## Fontes e imagens

Textos resumidos em português para apresentação acadêmica. As imagens pertencem aos titulares das franquias; este projeto não é oficial e não atribui licença livre a esses materiais.

- [Ultraman — Tsuburaya Productions](https://tsuburaya-prod.com/heroes/ultraman)
- [Ultraseven — Tsuburaya Productions](https://tsuburaya-prod.com/heroes/ultraseven)
- [Ultraman Tiga — Tsuburaya Productions](https://tsuburaya-prod.com/heroes/ultraman-tiga)
- [Kamen Rider MY-TH — Toei](https://www.kamen-rider-official.com/)
- [Arte promocional de Kamen Rider MY-TH — TV Asahi](https://www.tv-asahi.co.jp/zeztz/news/0031/)
- [Ultraman Dyna — Tsuburaya Productions](https://tsuburaya-prod.com/heroes/ultraman-dyna)
- [Ultraman Mebius — Tsuburaya Productions](https://tsuburaya-prod.com/heroes/ultraman-mebius)
- [Documentação oficial do Bootstrap](https://getbootstrap.com/docs/5.3/getting-started/introduction/)
