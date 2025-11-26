# Nova Wika HP

A Nova Wika HP é uma enciclopédia estática feita em HTML e CSS que apresenta, de forma simples e organizada, os principais personagens e livros do universo de Harry Potter. A ideia é criar um pequeno portal temático, quase como uma mini biblioteca de Hogwarts, onde cada página concentra informações e ilustrações em estilo artesanal que deixam o projeto com uma identidade própria.

É um site leve, totalmente navegável a partir do arquivo inicial `home.html`, e pensado para funcionar em qualquer navegador sem necessidade de instalação ou servidores externos.

## Proposta do projeto

O foco é treinar estruturação de páginas, organização de arquivos, padronização visual e navegação entre conteúdos estáticos. É também uma forma divertida de aplicar fundamentos de HTML e CSS enquanto se explora um universo conhecido e cheio de referências.

Cada página apresenta um personagem ou um livro específico, sempre mantendo consistência no layout e nas cores. As imagens dão o toque final, já que foram escolhidas por terem um estilo de ilustração que combina com o tema da saga.

## Estrutura de pastas

A organização do projeto dentro da pasta `src` segue uma lógica simples. Primeiro vêm os estilos e recursos visuais, depois as páginas HTML. A árvore completa fica assim:

```
src/
├── assets/
│   ├── css/
│   │   └── style.css
│   └── images/
│       ├── albus_dumbledore.jpg
│       ├── capa_hp1.jpg
│       ├── capa_hp2.jpg
│       ├── capa_hp3.jpg
│       ├── capa_hp4.jpg
│       ├── capa_hp5.jpg
│       ├── capa_hp6.jpg
│       ├── capa_hp7.jpg
│       ├── drago_malfoy.jpg
│       ├── gina_weasley.jpg
│       ├── harry_potter.jpg
│       ├── hermione_granger.jpg
│       ├── lord_voldemort.jpg
│       ├── principal.webp
│       ├── remus_lupin.jpg
│       ├── ron_weasley.jpg
│       ├── rubeus_hagrid.jpg
│       ├── severus_snape.jpg
│       ├── sirius_black.jpg
│       └── logo.png
│
├── calice_de_fogo.html
├── camara_secreta.html
├── dumbledore.html
├── enigma_do_principe.html
├── gina_weasley.html
├── hagrid.html
├── harry_potter.html
├── hermione_granger.html
├── home.html
├── license
├── malfoy.html
├── ordem_da_fenix.html
├── pedra_filosofal.html
├── prisioneiro_de_azkaban.html
├── reliquias_da_morte.html
├── remo_lupin.html
├── ron_weasley.html
├── sirius_black.html
├── snape.html
└── voldemort.html
```

Essa estrutura facilita futuras expansões, porque mantém os arquivos visuais isolados dentro de `assets` e deixa todas as páginas visíveis para edição rápida.

## Conteúdo disponível

Ao abrir o site, o visitante encontra um menu inicial com links para todos os livros e personagens. Cada página tem um pequeno texto descritivo e uma imagem correspondente, criando uma experiência de consulta rápida semelhante a um pequeno almanaque mágico.

Os livros incluem desde a Pedra Filosofal até as Relíquias da Morte. Os personagens trazem nomes conhecidos como Harry, Hermione, Ron, Sirius, Snape, Hagrid, Dumbledore e outros que marcam presença na saga.

## Possibilidades de expansão

Mesmo sendo um projeto simples, ele abre muitas portas para melhorias futuras. Uma camada de responsividade deixaria a experiência mais confortável em celulares. Efeitos básicos usando JavaScript poderiam trazer vida ao site, criando pequenas interações temáticas. Um modo noturno inspirado em Hogwarts também cairia bem, assim como uma barra de busca capaz de encontrar qualquer página rapidamente.

Outra possibilidade seria integrar uma folha de estilos mais consistente, criando uma paleta própria para o site. Também é possível transformar tudo em um mini portal interativo com animações leves e transições suaves entre páginas.

## Licença

Este projeto inclui um arquivo de licença que detalha as condições de uso e distribuição do conteúdo. Recomenda-se consultar o texto antes de reutilizar qualquer parte do material.