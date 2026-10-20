# Kaiky Concept. — Site de portfólio

Site de portfólio que desenvolvi para o **Kaiky Concept.** (Kaiky Barreto), designer gráfico, videomaker e diretor de arte de Ribeirão Pires, SP.

🔗 **Site no ar:** https://projectcampos.github.io/kaiky-concept/

| | |
|---|---|
| **Cliente** | Kaiky Concept. — [Behance](https://www.behance.net/kaikyconcept) · [Instagram](https://www.instagram.com/kaikyconcept/) |
| **Desenvolvimento** | Giovana Campos — [@ProjectCampos](https://github.com/ProjectCampos) |
| **Tipo** | Site institucional / portfólio, one-page, responsivo |
| **Stack** | HTML, CSS e JavaScript puro · hospedado no GitHub Pages |

## O projeto

O objetivo foi criar um site que reunisse os trabalhos do Kaiky em um só lugar, com a cara da marca dele:

- **Identidade visual da marca** — laranja e preto do logo da caveira em chamas, tipografia condensada (Anton) com detalhes em letra de pincel (Permanent Marker).
- **Referências dos pôsteres autorais** — textura granulada, vermelho, retícula e tipografia editorial inspirados na série *Concept Frames* do Instagram.
- **Responsivo** — layout pensado para funcionar bem no celular, com menu mobile.
- **Leve e sem dependências** — um único `index.html`, sem frameworks nem build.

### Seções

- **Trabalhos** — 8 identidades visuais (Master Churrascaria, akta®, nutrisolo®, KAOS®, oros., Alexandre Álvaro, Fluxo Ubuntu, MBA Soluções Financeiras), com link para cada case no Behance
- **Pôsteres & experimentos** — série *Concept Frames* e pôsteres tipográficos, com link para os posts
- **Serviços**, **Sobre** e **Contato**

### Detalhes técnicos

- Animações de entrada com `IntersectionObserver` e faixa animada em CSS
- Respeita `prefers-reduced-motion` (desliga animações para quem prefere)
- Lista de projetos gerada a partir de um array em JavaScript, fácil de atualizar
- Também foi gerada uma versão em PDF interativa (com links clicáveis) para envio a clientes

## Estrutura

```
kaiky-concept/
├── index.html   # site completo (HTML, CSS e JS em um único arquivo)
├── img/         # banner e capas dos projetos
└── README.md
```

## Como editar

- **Textos, contato e links:** direto no `index.html`.
- **Projetos:** constante `projects` no `<script>` no fim do `index.html` (título, categoria, imagem e link do Behance).
- **Imagens:** coloque o arquivo em `img/` e use o mesmo nome na lista de projetos.

O site atualiza sozinho em 1–2 minutos depois de cada alteração na branch `main`.

---

Todos os trabalhos, imagens e a marca Kaiky Concept. pertencem a Kaiky Barreto. Design e desenvolvimento do site por Giovana Campos.
