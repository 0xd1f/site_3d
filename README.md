# Forma — Estúdio 3D

Aplicação de modelagem 3D pessoal que roda no navegador. Para usar, abra `index.html` em um servidor estático. As bibliotecas são carregadas por CDN, então é necessária uma conexão com a internet.

## Recursos

- Cubo, esfera, cilindro, cone, toro e plano
- Seleção por clique, hierarquia da cena, duplicação e exclusão
- Transformações de mover, girar e escalar com gizmo
- Ajuste de posição, rotação, escala, cor, metallic e roughness
- Aplicação de imagens PNG, JPEG e WebP como textura
- Importação de modelos OBJ
- Exportação de `.obj`, `.mtl` e imagens de textura reunidos em um ZIP
- Salvar e reabrir projetos em `.forma.json`

## Controles

- Arraste no fundo: orbitar a câmera
- Roda do mouse: zoom
- Clique no modelo: selecionar
- `W`, `E`, `R`: mover, girar, escalar
- `Ctrl+D`: duplicar
- `Delete`: excluir

## Exportação e texturas

O botão **Exportar OBJ** baixa `forma-modelo.zip`, com `cena.obj`, `cena.mtl` e as imagens associadas. Extraia os arquivos juntos para manter os caminhos de textura do material. Os modelos OBJ importados são adicionados à cena como objetos editáveis.

