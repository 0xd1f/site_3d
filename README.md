# Forma — Estúdio 3D

Editor 3D pessoal no navegador, feito com Three.js e Vite.

## Rodar localmente

1. Instale Node.js 20 ou superior.
2. Na pasta do projeto, rode `npm install`.
3. Rode `npm run dev` e abra o endereço local mostrado no terminal.
4. Para gerar os arquivos de publicação, rode `npm run build`.

## O que dá para fazer

- Criar cubo, esfera, cilindro, cone, toro e plano
- Importar arquivos `.obj` e selecionar os objetos na cena
- Mover, girar e escalar pelo gizmo ou editando os valores
- Ajustar cor, metalness, roughness e textura de imagem (PNG, JPG, WebP)
- Duplicar, excluir e renomear objetos
- Salvar e abrir projetos `.forma.json`
- Exportar geometria em OBJ, com material MTL e textura empacotados em ZIP

## Atalhos

- `W`, `E`, `R`: mover, girar, escalar
- `Ctrl+D`: duplicar seleção
- `Delete`: remover seleção
- Arraste no espaço vazio para orbitar; use a roda para zoom

As texturas enviadas são incorporadas no modelo exportado. Ao abrir no Blender ou outro programa, mantenha o `.obj`, o `.mtl` e a imagem no mesmo local (ou extraia o ZIP inteiro).

