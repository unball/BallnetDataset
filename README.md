# Ballnet Dataset
Dataset com imagens 640 x 640 e anotações de partidas disputadas pela UnBall na IRONCup 2020.

<p align="center">
  <img style="height: 440px" src="https://github.com/user-attachments/assets/f30c9ef4-4675-42f9-8736-ca095a7c00f1" />
</p>


## Formato
Formato das anotações compatível com modelos YOLOv8.
```
classe x_bbox y_bbox largura_bbox altura_bbox x_frente y_frente conf_frente x_tras y_tras conf_tras
```

## Tamanho das amostras

Amostra   | Tamanho
--------- | ------------
train     | 437 imagens
valid     | 131 imagens
test      | 85 imagens
