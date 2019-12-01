# voice-analysis
[PyWorld](https://github.com/JeremyCCHsu/Python-Wrapper-for-World-Vocoder/blob/master/README.md) and [pyreaper](https://github.com/r9y9/pyreaper) implementation of voice analysis.

## Dependencies
**You must not use Anaconda as a python environmet !**  
[Does not work in Anaconda #12](https://github.com/JeremyCCHsu/Python-Wrapper-for-World-Vocoder/issues/12)  

## Install
### PyWorld
**You must install scipy first.**
```
$ pip install scipy
$ pip install pyworld
```

### pyreaper
**You must not install pyreaper by usin pip.**
```
$ git clone https://github.com/r9y9/pyreaper
$ cd pyreaper
$ git submodule update --init --recursive
$ python setup.py develop
$ pip install pysptk
```

## Results
### PyWorld
- Raw Data

![pyworld_rpw.png](https://qiita-image-store.s3.amazonaws.com/0/324488/4fe6f5eb-160d-af44-b342-2ceeafba5493.png)

- F0 Counter

![pyworld_f0.png](https://qiita-image-store.s3.amazonaws.com/0/324488/1eeb297b-d898-9e78-74bf-242610f7d037.png)

- Calculate Time

![pyworld_time.png](https://qiita-image-store.s3.amazonaws.com/0/324488/f2bfcf95-7752-28dc-8b0c-036a916d8344.png)

### pyreaper
- Raw Data

![reaper_1.png](https://qiita-image-store.s3.amazonaws.com/0/279783/13f70ed1-2c32-e868-87bc-bf6d523f8cc0.png)


- Pitch Mark

![reaper_2.png](https://qiita-image-store.s3.amazonaws.com/0/279783/2a2f1f68-2d11-ba40-ec13-6831253f3dd5.png)

- F0 Counter

![reaper_3.png](https://qiita-image-store.s3.amazonaws.com/0/279783/e4487091-6f34-9074-52c6-a86ab4541d05.png)

- Correlations

![reaper_4.png](https://qiita-image-store.s3.amazonaws.com/0/279783/dbd01465-ebf0-c777-a429-1cd09aba8326.png)

- Calculate Time

![calc_pyreaper.png](https://qiita-image-store.s3.amazonaws.com/0/279783/b3c34ada-e7f6-a2f2-dc29-e8a934fccc79.png)
