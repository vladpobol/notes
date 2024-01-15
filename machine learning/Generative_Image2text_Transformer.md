## Overview
* #### ...

## Architecture
### Image encoder
* #### create_projecton_layer - возвращает линейный слой in=размер фич картинок, out=размер эмбеддингов текста
* #### 

### Text decoder
* #### uni_mask_zero_neg - матрица размера (size x size) диагональ и верхний треугольник которой заполнен -inf


### Decoder
* #### TransformerDecoderTextualHead
* ? mask_future_positions, create_decoder
* projected_visual_features - эмбеддинги визуальных фич такого же размера как и эмбеддинги текстов
* max_caption_length - длинна входной последовательности текста 
* caption_embeddings - эмбеддинги из последовательности токенов
* uni_mask_zero_neg - матрица размера (size x size) диагональ и верхний треугольник которой заполнен -inf


