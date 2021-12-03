DockerでPython公式イメージ + MeCab + NEologd辞書
===

※ 概要については [Qiitaブログ]() を参照ください

<br />

## Usage

Dockerデーモンを起動し、コンテナ内に入ればそこでMeCab(with NEologd)が使用可能です

```shell
$ git pull
$ cd
$ docker-compose up --build -d

# コンテナ内部へ
$ docker exec -it mecab-python-neologd bash
```
