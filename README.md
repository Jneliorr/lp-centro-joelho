# Centro do Joelho e Coluna

Landing page em Vite + Tailwind CSS 4, JavaScript e WebGL nativo (GLSL).

## Executar

- `npm install`
- `npm run dev`
- `npm run build` gera a versão estática em `dist/`.
- `npm run preview` visualiza o build.

## Conteúdo e referências

Dados consultados em 22/10/2026:
- Instagram oficial: https://www.instagram.com/centrodojoelhoecoluna/
- Agendamentos e unidades: https://linktr.ee/centrodojoelhoecoluna
- Ficha Google: https://share.google/WjWp7yiZE4Fo3mVif

As 16 avaliações são transcrições públicas. Guilherme Rafael aparece como trecho identificado. Duas avaliações não possuem texto. O conteúdo é estático e não sincroniza automaticamente com Google ou Instagram. Fotos locais foram obtidas nas referências oficiais. Vídeos abrem os Reels originais, pois a plataforma restringiu o acesso sem login. Não são vídeos hospedados localmente.

Contatos, unidades, serviços, avaliações e galeria estão em `src/main.js`. O shader está em `src/mist.js`. O efeito pausa fora da tela e respeita a preferência por movimento reduzido. Sem WebGL, o fundo permanece estático. Há fontes de sistema de reserva caso o Google Fonts não esteja disponível.
