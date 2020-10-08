## I wish to be an Dev. engineer:fire:

<a href="https://twitter.com/Naokit_dev">
<img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/Naokit_dev?color=%231DA1F2&label=%40Naokit_dev&logo=Twitter&style=for-the-badge">
</a>

[![My Qiita posts](https://qiita-badge.apiapi.app/s/naokit-dev/posts.svg)](http://qiita.com/naokit-dev)
[![My Qiita contributions](https://qiita-badge.apiapi.app/s/naokit-dev/contributions.svg)](http://qiita.com/naokit-dev)
[![My Qiita followers](https://qiita-badge.apiapi.app/s/naokit-dev/followers.svg)](http://qiita.com/naokit-dev)

----

## Skil

### Programing Languages
<img src="https://img.shields.io/badge/ruby-%23CC342D.svg?&style=for-the-badge&logo=ruby&logoColor=white"> <img src="https://img.shields.io/badge/rails%20-%23CC0000.svg?&style=for-the-badge&logo=ruby-on-rails&logoColor=white"> <img src="https://img.shields.io/badge/html5%20-%23E34F26.svg?&style=for-the-badge&logo=html5&logoColor=white"> <img src="https://img.shields.io/badge/css3%20-%231572B6.svg?&style=for-the-badge&logo=css3&logoColor=white">

### Tools
<img src="https://devicons.github.io/devicon/devicon.git/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="50" height="50"/>　<img height="50" width="50" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/docker/docker.png" />　<img height="50" width="50"  src="https://simpleicons.org/icons/circleci.svg">　<img src="https://devicons.github.io/devicon/devicon.git/icons/linux/linux-original.svg" alt="linux" width="50" height="50"/>　<img src="https://devicons.github.io/devicon/devicon.git/icons/nginx/nginx-original.svg" alt="nginx" width="50" height="50"/>　<img src="https://devicons.github.io/devicon/devicon.git/icons/github/github-original.svg" alt="linux" width="50" height="50"/>

----

## Activity
<a href="https://github.com/anuraghazra/github-readme-stats">
  <img align="center" src="https://github-readme-stats.vercel.app/api?username=naokit-dev&show_icons=true&theme=gruvbox" height="180"/>
</a>
<a href="https://github.com/anuraghazra/convoychat">
  <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=naokit-dev&layout=compact&theme=gruvbox"  height="180"/>
</a>




# 学習経歴・やってみた内容(2020.5月〜)

## AWS

### Topic

直近ではAWSサービスのイベント内容を取得してSlackに通知する、簡易なサーバーレスアプリケーションの設計と構築という課題に取り組んでいます

**使用技術:** AWS [EC2, SES, SNS, **Lambda**, **Chalice**], **Slack API**, Docker, Rails

**設計概要:** EC2上のフォームからSESでメールを送信、送信イベントをSNSに転送、SNSでLambdaをキック、Lambda(python)でイベント内容をSlack APIのJSONフォーマットに整形してHTTPリクエストを生成、Slackに通知

**関連:**
- [AWS Chaliceの開発環境をdockerで構築し、超高速でサーバーレスアプリケーションをデプロイしてみた - Qiita](https://qiita.com/naokit-dev/items/3840ed216221a2c49379)
- [[Rails6対応, 公式SDK] AWS SESを使ってRailsから送信元が独自ドメインのメールを送ってみた - Qiita](https://qiita.com/naokit-dev/items/4668ec379fbe6dcb45cd)

**Interest:** Lambda, CodeDeploy(CI/CD), CloudFormation(IaC)

### その他

- 2020/09/15 [AWS ALBにWAFを設定して海外からのアクセスを遮断してみる - Qiita](https://qiita.com/naokit-dev/items/c0c1931e0bfd891a9a1b)
- 2020/08/18 [HTTP -> HTTPSのリダイレクトはELBで行う方がスマートかもしれない　(Nginxでリダイレクトを行う方法あり) - Qiita](https://qiita.com/naokit-dev/items/c62bdf1d1656c4dba091)
- 2020/07/03 [EC2、RDSを利用してRailsアプリをデプロイする [NGINX + puma + PostgreSQL + Rails 6] - Qiita](https://qiita.com/naokit-dev/items/808744a371a7154318ad)

## Docker

### Topic

普段はVS CodeのRemote Containerという拡張機能を用いて、ホストからコンテナに接続しホスト側のVS Codeのインターフェースを利用して開発を行っています

**関連:** [コマンドひとつ、5分でRails6の開発環境構築 on Docker - Rails6 + Nginx + PostgreSQL + Webpack (Bootstrap install済) - Qiita](https://qiita.com/naokit-dev/items/96cb41361ebc4b7716c0)

### その他:

- 2020/09/28 [とりあえずのdocker-compose upから入って、Web server(Nginx)の基礎設計を学びながら、Dockerを学ぶ① - Qiita](https://qiita.com/naokit-dev/items/a9a44310a055aa50ccff)
- 2020/09/05 [”Docker Compose、チョットわかる”になるために知っておきたい頻出オプション - Compose file version 3(3.8) reference - - Qiita](https://qiita.com/naokit-dev/items/26b6a542571639e975ee)
- 2020/08/06 [DockerでRailsチュートリアルのローカル開発環境構築（Rails 6 + PostgreSQL + Webpack) - Qiita](https://qiita.com/naokit-dev/items/99225bf3d8665ecfdec2)

##  Rails - オンラインマークダウンエディタの個人開発

**Motivation:** プログラミング初学者が、Twitter 上でスクリーンショットを使ってコードを共有しているのを見て考案。
見る側、見せる側にとって、もっと効果的な方法を検討した結果、共有用 URL を生成可能なオンライン Markdown エディタの制作、公開に至りました（2020.7月）

**Source:** [naokit-dev/myapp](https://github.com/naokit-dev/myapp)

**URL:** [New Article | mdClip - Fun with Code](https://mdclip.xyz/)

**使用技術:** AWS(EC2, RDS), CircleCI(CI), Capistrano(CD), Docker, Ruby on Rails 6

**機能要件:** リアルタイムプレビューが可能な markdown エディタ / 多言語対応のシンタックスハイライト / ログイン不要で記事の作成が可能 / 生成した記事は固有の URL を割り当て共有可能 / シェアボタンで Twitter に URL を投稿 / URL 削除用の記事固有パスワードを自動生成

**非機能要件:** SSL 対応 / *CI/CDを導入し、**自動テストおよび開発段階からデプロイとほぼ同じ環境での動作検証が可能であること**

# エンジニアを志す以前の背景(〜2020.4月)

## 理学療法士 - 臨床リハビリテーション

- 大学卒業後、”理学療法士国家資格”取得
- 大学病院、介護施設、終末期医療、様々な領域で業務経験を得る
- 常に、**よく生きるとはを考えさせられる**
- **高機能  ≠ 幸福で豊かであること**への気付き

## 理学療法士 - 修士取得・教育・研究領域

- **脳科学（より専門的には認知神経科学）**の研究室に所属
- 初めてプログラミングに触れる(MatLab, R)
- 実験を設計する過程、計測が好き、機械が好き
- 実験が好きすぎて、研究室にある機材はすべて扱えるようになる
- **人の行動を体系的にデータ化することが得意 (行動 - 心理実験)**
- **ヒトの活動を電気的に捉え、可視化することが得意 (電気生理, 筋電図, 脳電位ほか)**

## 最後に自己紹介

- **サイエンスとアート:** 論理的な側面と情緒的な側面、双方を大切にしたいと考えています
- **いつも新しい何かを探している:** いまはない、よりよい仕組みに関心があります
- **死ぬ直前までアップデートしたい:** エンジニアを志す一番の動機がこれかもしれません







<!--
**naokit-dev/naokit-dev** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->


