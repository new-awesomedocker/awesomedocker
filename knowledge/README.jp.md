


この記事は「docker-knowledge」のReadme.mdを参考としております。

from https://github.com/support-project/docker-knowledge

# docker-knowledge

この記事はナレッジ蓄積システム**knowledge**のシステムをdocker-composeを使用して構築する方法を紹介します。

- これは[Knowledge](https://github.com/support-project/knowledge)を構築することができるDockerfileです。


## Knowledgeとは何か
- 無料のナレッジ蓄積システムです。

- [デモンストレーション](https://support-project.org/knowledge/index)

- [開発ページ](https://support-project.org/knowledge_info/index)



## 起動方法

このソースコードを入手し、`docker-compose up`でシステムを起動するだけです。

以下のソースコードをペーストしましょう。

```sh
git clone https://github.com/minegishirei/docker-knowledge.git
cd docker-knowledge
docker-compose up
```

