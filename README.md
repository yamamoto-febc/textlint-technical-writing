
# textlint with 技術文書を書くためのtextlint校正ルールセット

[技術文書を書くためのtextlint校正ルールセット](http://efcl.info/2016/07/13/textlint-rule-preset-ja-technical-writing/)を利用するためのコンテナです。

## `Dockerfile` links

[`latest`](https://github.com/yamamoto-febc/textlint-technical-writing/tree/master/)[(Dockerfile)](https://github.com/yamamoto-febc/textlint-technical-writing/tree/master/Dockerfile)


## 使い方



### 起動コマンド書式

```bash
docker run -it --rm -v $PWD:/work \
                    textlint/technical-writing textlint引数
```

#### 起動例
```bash
docker run -it --rm -v $PWD:/work \
                    textlint/technical-writing README.md
```
