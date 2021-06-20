# A Sound Of An IA

This project allows you to train a neural network to generate midi music files that make use of a single instrument

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
