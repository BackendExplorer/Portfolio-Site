# Portfolio Site

![EC2](https://img.shields.io/badge/Host-AWS_EC2-FF9900?logo=amazonaws&logoColor=white)
![Nginx](https://img.shields.io/badge/Reverse_Proxy-Nginx-009639?logo=nginx&logoColor=white)
![GitHub](https://img.shields.io/badge/Repo-GitHub-181717?logo=github&logoColor=white)
![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?logo=tailwindcss&logoColor=white)

<br>

### EC2とNginxで構築・公開された、開発成果と自身の活動を紹介するポートフォリオサイト

<br>

[ポートフォリオサイトを開く](http://portfolio.tenshin.site/)


<br>

## ⭐ デモ動画

<br>

### ポートフォリオサイトの閲覧デモ

<br>

<img src="https://github.com/user-attachments/assets/13eb215e-b8be-4c0c-a5c9-c5b8059d2ac5" width="800" />




<br>


## **📝 サービス紹介と技術構成**
- [サービスの特徴・開発の目的](#サービスの特徴・開発の目的)

- [システム全体の構成図](#システム全体の構成図)

- [使用技術](#使用技術)

<br>

## **💡 開発の振り返りと展望**
- [設計上のこだわり](#設計上のこだわり)

- [苦労した点](#苦労した点)

- [さらに追加したい機能](#さらに追加したい機能)

<br>

## **📚 出典・ライセンス**

- [参考文献](#参考文献)

- [ライセンス情報](#ライセンス)

<br>

---

## <a id="サービスの特徴・開発の目的"></a> 📝 サービスの特徴・開発の目的

<br>

###  サービスの全体像

- このプロジェクトは、自己紹介と開発成果を掲載する**ポートフォリオサイト**です。

- ユーザーはブラウザからアクセスし、プロフィールや制作実績を閲覧できます。

<br>

### できること

- **自己紹介の掲載**
  
  名前・背景・エンジニアとしての目標を明示

- **技術スタックの提示**
  
  使用技術を分野別に整理し、視覚的にわかりやすく表示

- **プロジェクトの一覧表示**
  
  開発したWebアプリやツールの概要・技術スタック・READMEリンクを整理して紹介

- **演奏実績の紹介**
  
  チュニジア大統領官邸や、日本武道館などでの演奏実績を掲載


<br>

### 作成のきっかけ

1. **課題意識**

   Webアプリを開発するだけでなく、自分で公開・運用できる力を身につけたかった。

2. **解決アプローチ**

   EC2にSSHで接続し、GitHubからコードを取得。
   
   Nginxを用いて静的サイトを公開し、ドメインやパーミッションも設定。

4. **得られた学び**

   サーバ構築・SSH接続・Nginx設定・Web公開の流れを一通り習得できた。

<br>

---

## <a id="システム全体の構成図"></a>🔄 システム全体の構成図

<br>

<img width="767" alt="Image" src="https://github.com/user-attachments/assets/0d537a44-e18e-490a-a000-473511780b0b" />


<br>

---

## <a id="使用技術"></a>🧰 使用技術

<br>


### 技術選定の理由

- **`EC2`**
  
  自分の手でサーバを立ち上げて、Linux操作や公開設定を実践的に学びたかったから

- **`Nginx`**
  
  シンプルな構成でサイトを高速に公開できて、設定の仕組みもわかりやすいから

- **`HTML / CSS / JavaScript`**

  自由にカスタマイズできて、構造・デザイン・動きを細かく調整しやすいから

- **`Tailwind CSS`**
  
  細かいCSSを書かなくても、すぐにデザインを作れるから

- **`Git / GitHub`**
  
  変更履歴を管理しながら、EC2と安全に連携してコードを更新したかったから

- **`テンプレート`**

  ウェブサイトを効率的に実装するために利用

  [HTML5 UP! Responsive HTML5 and CSS3 Site Templates](https://html5up.net/)

  


<br><br>

| カテゴリ       | 技術スタック                                                                 |
|----------------|------------------------------------------------------------------------------|
| サーバー       | ![EC2](https://img.shields.io/badge/Host-AWS_EC2-FF9900?logo=amazonaws&logoColor=white) |
| Webサーバ      | ![Nginx](https://img.shields.io/badge/Reverse_Proxy-Nginx-009639?logo=nginx&logoColor=white) |
| フロントエンド | ![HTML](https://img.shields.io/badge/HTML-5-orange?logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS-3-blue?logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow?logo=javascript&logoColor=black) |
| CSSフレームワーク | ![TailwindCSS](https://img.shields.io/badge/Style-Tailwind_CSS-38B2AC?logo=tailwindcss&logoColor=white) |
| エディタ       | ![VSCode](https://img.shields.io/badge/Editor-VSCode-blue?logo=visualstudiocode&logoColor=white) |
| バージョン管理 | ![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white) |
| デプロイ方法   | ![SSH](https://img.shields.io/badge/Deploy-SSH-green?logo=gnuprivacyguard&logoColor=white) |

<br>

---


## <a id="設計上のこだわり"></a>🌟 設計上のこだわり



<br>

### サイトデザインのこだわり

<br>

- **課題点**

  ユーザーに見やすく使いやすいデザインを提供したい一方で、<br>
  
  手軽に保守・変更できる構造にする必要がありました。

<br>

- **解決アプローチ**

  Tailwind CSSを使い、クラスを組み合わせるだけで柔軟にデザインを調整。<br>
  
  シンプルで統一感のあるスタイルを心がけました。

<br>

- **得られた成果**

  デザインの変更がしやすく、軽量で高速なサイト表示を実現しています。

<br>


---

## <a id="苦労した点"></a>⚠️ 苦労した点

<br>

### EC2とNginxを使った静的サイト公開と運用

<br>

- **課題点**
  
  ポートフォリオサイトを自分で開発するだけでなく、実際に公開・運用するために、<br>
  
  EC2上にコードを配置し、NginxでWebサーバを立てる一連の流れを学ぶ必要がありました。<br>
  
  また、SSH接続の設定やファイルのパーミッション管理、ドメイン設定など、<br>
  
  サーバ運用に関する知識も不足していたため、設定作業に苦労しました。

<br>

- **解決アプローチ**

  EC2インスタンスを立ち上げ、SSHキーペアを使って安全に接続。<br>
  
  GitHubからリモートリポジトリのコードをpullし、Nginxの設定ファイルを編集してWebサイトを公開。
  
  また、ファイルの所有権やアクセス権を適切に設定し、ドメインの紐付けも行いました。

<br>

- **得られた成果**

  自分でWebアプリの開発からサーバ公開まで一貫して行う経験ができ、<br>
  
  インフラ構築・運用に関する理解が大きく深まりました。<br>
  

<br>


---

## <a id="さらに追加したい機能"></a>🔥 さらに追加したい機能


<br>

### GitHub Actionsによる自動デプロイ

<br>

- **課題点**
  
  今は手動でサーバにコードを反映しているため、ミスや時間がかかっています。<br>
  
  自動でデプロイできる仕組みを作りたいと考えています。

<br>

- **実装方針**

  GitHub Actionsでコードをプッシュしたときに自動でサーバに反映できるようにします。<br>
  
  SSH接続を使って安全に更新できる仕組みを目指します。

<br>

- **期待される効果**

  作業ミスや時間のロスを減らせて、すぐに最新の状態にできます。

<br>

---

## <a id="参考文献"></a>📗 参考文献

<br>

### 公式ドキュメント

- [Amazon EC2](https://docs.aws.amazon.com/ec2/)

- [Nginx](https://nginx.org/en/docs/)

- [Tailwind CSS](https://tailwindcss.com/docs/installation)


<br>

### 参考にしたサイト

- [EC2にnginxをセットアップする](https://qiita.com/Hide-Zaemon/items/f4a0599b7c8cb3559ca0)




<br>


---

## <a id="ライセンス"></a>📜 ライセンス情報

<br>

<ul>
  <li>
    本プロジェクトの全コード・構成・図・UIなどの著作権は、制作者である Tenshin Noji に帰属します。<br><br>
    採用選考や個人的な学習を目的とした閲覧・参照は歓迎しますが、<br><br>
    無断転載・複製・商用利用・二次配布は禁止とさせていただきます。<br><br>
    ライセンス全文はリポジトリ内の <a href="./LICENSE.md" target="_blank">LICENSEファイル</a>をご覧ください。
  </li>
</ul>

<br>
