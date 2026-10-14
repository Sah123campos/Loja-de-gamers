# Núcleo Meridiano: jornada 3D

Site em uma página só, com cena 3D em Three.js. A câmera percorre o ambiente conforme você rola a página: começa na fábrica de hardware **Núcleo**, segue o caminhão até o armazém **Meridiano** e termina com a entrega na casa do cliente, em primeira pessoa, diante do setup gamer.

As marcas Núcleo Hardware e Meridiano Logística são fictícias. Este é um site de demonstração.

## Páginas

| Arquivo | O que é |
| --- | --- |
| `index.html` | Jornada completa (fábrica → estrada → armazém → entrega), 14 paradas |
| `fabrica-gamer.html` | Versão só da fábrica gamer |
| `armazem.html` | Versão só do armazém logístico |

## Repositórios separados

- Fábrica gamer: https://github.com/Sah123campos/fabrica-gamer-3d
- Armazém: https://github.com/Sah123campos/armazem-3d

## Como abrir

Abra `index.html` no navegador. É preciso estar conectado à internet, porque o Three.js e as fontes vêm de CDN.

Para publicar no **GitHub Pages**, vá em *Settings → Pages* e escolha a branch `main`, pasta `/ (root)`.

## Tecnologia

- Three.js r128 (com bloom via `UnrealBloomPass` no desktop)
- Texturas geradas em canvas, sem arquivos de imagem
- HTML, CSS e JavaScript puros, sem build

## Contato

- Telefone: (19) 98950-7788
- E-mail: samuspcampos@gmail.com
