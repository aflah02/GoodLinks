# GoodLinks

## Pytorch
- [Weight Tying LSTM Encoder Decoder](https://discuss.pytorch.org/t/best-way-to-tie-lstm-weights/12504/8)

## HuggingFace
- [Model Internal Layer Outputs Explanation](https://medium.com/@dhartidhami/understanding-bert-word-embeddings-7dc4d2ea54ca#:~:text=hidden_states%20has%20four%20dimensions%2C%20in,22%20tokens%20in%20our%20sentence)
- [Hidden States](https://github.com/huggingface/transformers/issues/1827)

## Nested Dict to df

- https://stackoverflow.com/a/54300940/13858953

## List all dirs in a dir with size

- du -skh * | sort -hr 
- https://stackoverflow.com/questions/1019116/using-ls-to-list-directories-and-their-total-sizes

## Identify in which screen instance a process is running

```
To find the screen instance in which PID 351 is running, search the PID 351 environment for the string "STY=":

$ grep -z '^STY=' /proc/351/environ
```

https://unix.stackexchange.com/a/181102/492831

## Kill all screen sessions
```
pkill screen 
```
Ref - https://unix.stackexchange.com/questions/94527/how-do-i-kill-all-screens
