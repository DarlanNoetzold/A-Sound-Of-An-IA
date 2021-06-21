# A Sound Of An IA

Este projeto permite que você treine uma rede neural para gerar música apartir de arquivos midi de instrumentos únicos.

## Requerimentos

* Python 3.x
* Instalar os seguintes pacotes:
	* Music21
	* Keras
	* Tensorflow
	* h5py

## Treinando

Para treinar o modelo **lstm.py**.

E.g.

```
python lstm.py
```

O modelo vai usar os arquivos ./midi_songs para ser treinado. Esses arquivos devem conter apenas instrumentos únicos.

## Gerando Música

Após treinar o modelo você pode rodar o medelo de predição: **predict.py**

E.g.

```
python predict.py
```

Você pode roda também pelo arquivo: **weights.hdf5**

---
