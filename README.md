# word2vec
[word2vec](https://code.google.com/archive/p/word2vec/) computes continuous distributed representations of words.

## Welcome
```
cd src
make
```
Then, you get ```src/compute-accuracy,src/distance,src/word-analogy,src/word2phrase,src/word2vec```.

## Usage

* add commands to PATH

```
. ./word2vec_rc
```

* test
```
word2vec
```


# Trouble Shooting

1. distance.c:18:20: fatal error: malloc.h: No such file or directory

```
cd src
make 
distance.c:18:20: fatal error: malloc.h: No such file or directory
```

solution1: changing include malloc.h to include malloc/malloc.h

solution2: https://github.com/byzhang/word2vec/issues/17