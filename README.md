# TSG Github Pages

## 運用方針

各分科会にGithub Pagesが必要な場合は，当該分科会のリポジトリをtsg-ut内に作成し，[GithubのHelp](https://help.github.com/articles/user-organization-and-project-pages/#project-pages)に従ってgh-pagesブランチを切る．
gh-pagesブランチの中で(jekyll等を用いて)Webサイトを構築すると，

``
http://sig.tsg.ne.jp/<repository name>
``

というURLで当該分科会のリポジトリにアクセスすることができるようになる．

### jekyllを用いる場合

_config.ymlに以下の項目を設定する．

```
baseurl: "/<repository name>"
url: "http://sig.tsg.ne.jp"
```

わからない場合は既存の分科会のGithub Pagesを参照するとよい．

## tsg-ut Github Pages 一覧

+ [2015年度 機械学習分科会](http://sig.tsg.ne.jp/ml2015/)
