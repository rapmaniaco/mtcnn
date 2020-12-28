TensorFlow v2.3 requires CUDA 10.1 and cuDNN 7.6. Whereas, for TensorFlow 2.4 you'll need CUDA 11 with cuDNN 8.

```
$ mkvirtualenv dl4cv -p python3
```

Ambiente virtual de nome dl4cv foi criado e nele serão instaladas as bibliotecas (incluindo TensorFlow 2.2).

```

$ pip install numpy
$ pip install tensorflow-gpu==2.4.0 #Excluir o termo '-gpu' caso seja feita para CPU
$ pip install opencv-contrib-python
$ pip install scikit-image
$ pip install pillow
$ pip install imutils
$ pip install scikit-learn
$ pip install matplotlib
$ pip install progressbar2
$ pip install beautifulsoup4
$ pip install pandas
```

Não continuei o teste porque 2.4.0 precisa de CUDA 11
