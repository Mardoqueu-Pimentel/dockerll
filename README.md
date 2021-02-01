# dockerll
Docker layer labeler - put tags on the intermediary stages of a multistage docker build

Usage
```shellscript
$ docker build . | dockerll -r repo_name -t stage -t stage:rename_stage -v
```
