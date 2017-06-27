# word2vec
[word2vec](https://code.google.com/archive/p/word2vec/) computes continuous distributed representations of words.

# Trouble Shooting

1. distance.c:18:20: fatal error: malloc.h: No such file or directory

```
cd src
make 
distance.c:18:20: fatal error: malloc.h: No such file or directory
```

solution: changing include malloc.h to include malloc/malloc.h