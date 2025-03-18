![We only build the decoder aspect](https://heidloff.net/assets/img/2023/02/transformers.png)

# TransformerDecoder
Decoder only component of Transformer Architecture from Scratch

## Steps:

### Setup Vocabulary
### Position Encoding

Uses a sequence of alternating sine and cosine waves

Example:

PE = sin(pos/10000)

PE = cos(pos/10000)

**Equations**:

PE = sin(pos/10000^(2i/d))

PE = cos(pos/10000&(2i/d))

Let i be the embedding position(changes every 2) and pos be the token position

### Self-Attention

Calculate: Query, Key, Value Matrices

**Query Weights**: Weights that were used to create Query Matrix

Word_Embedding + Position Encodings x **Query Weights**

**Key Weights**: Weights that were used to create Key Matrix

Word_Embedding + Position Encodings x **Key Weights**

**Value Weights**: Weights that were used to create Value Matrix

Word_Embedding + Position Encodings x **Value Weights**


### Foward Layer
### Softmax Layer



