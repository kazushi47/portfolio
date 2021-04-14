# ポートフォリオ
このリポジトリでは私の公開可能な範囲で成果物をまとめており、それぞれ簡単ではありますが説明しております。  
短い説明で伝わりにくいところもあるかと思い大変恐縮ですが、最後までご覧頂けたら幸いです。

## 買ったものSNS - Webサービス
![](https://user-images.githubusercontent.com/61966044/114744554-c6b81d00-9d88-11eb-9cb5-9bf9fb87988f.png)
Webサイト→https://kattamono-sns.an.r.appspot.com/  
GitHub→https://github.com/kazushi47/kattamono-sns  
  
### 概要
買ったものを共有することに特化したSNS。  
何かしらのSNSを試しに作ってみたいという気持ちから作成。  

### 使用技術

- 言語: TypeScript
- フレームワーク: Node.js, Expressなど
- プラットフォーム: GCP(GAE, Firestore, CloudStorage)
- 開発期間: 2ヶ月程度

### 工夫した点

- GCPの無料枠内で構築できた
- Passportを使用してログイン機構をスムーズに実現できた

  > Passport ・・・ ExpressベースのWebアプリで利用できる認証機能を提供するミドルウェア

- パスワードはハッシュ化して保存・セッションなどセキュリティに注力した
- 非同期処理の振る舞いを頑張った

### 反省点

- インタフェースを書かなかった。後回しにせず設計段階から定義する型を決めておくことが大事だと思った
- 個人開発でもGitHubのプルリクベースの開発にするべきだった
- 例えばTypeScriptの素晴らしさなどの開発中に感銘を受けることが多々あったので記事にまとめてアウトプットしていきたかった

以上の反省点を踏まえて、次回の開発に活かしたいと思っている。

## GitHubの使い方を解説 - GitHub Wiki
![](https://user-images.githubusercontent.com/61966044/114750158-a12e1200-9d8e-11eb-89dd-d6f0cb4ec14e.png)
GitHub→https://github.com/kazushi47/HowToGitHub  

### 概要
友達にGitHubを布教するために書いたGitHubの使い方をGitHub Wikiにまとめたもの。  
環境構築〜プルリクエストまでを解説している。  

### 振り返り
実際に友達に使ってもらうことができたのでよかった。  
解説の際には初心者ということを考慮し自らの経験からGitコマンドを使わないGitHub Desktopを採用したのがよかった。  
他のプログラミング言語などの技術でも、経験して自分の意見がまとまれば積極的に記事にして公開していきたいと思った。  

