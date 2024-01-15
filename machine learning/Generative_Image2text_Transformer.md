## Overview
* #### ...

## Architecture
### Image encoder

### Decoder
* #### TransformerDecoderTextualHead
* ? create_decoder, bi_valid_mask_caption
* **projected_visual_features** - эмбеддинги визуальных фич такого же размера как и эмбеддинги текстов
* **max_caption_length** - длинна входной последовательности текста 
* **caption_embeddings** - эмбеддинги из последовательности токенов
* **uni_mask_zero_neg** - матрица размера (size x size) диагональ и верхний треугольник которой заполнен -inf
* #### CaptioningModel
* **convert2valid** - возвращает матрицу указаного размера из true/false
* <img src="https://i.imgur.com/jDNO51x.png">
* **


