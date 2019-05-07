# 概要
[エリック・エヴァンスのドメイン駆動設計](https://www.amazon.co.jp/dp/4798121967/ref=cm_sw_r_tw_dp_U_x_lx.ZCbSK76BAB)(通称：DDD)のまとめページです。  
輪読会で使用するために作成し、公開しています。  
内容はすべて[Wiki](https://github.com/team-ddd/ddd-book/wiki)に公開しています。  

# 記事の編集権限について
編集するには team-ddd の Organizations に属する必要があります。  
現状はクローズなチームなので、参加したい方は team-ddd のオーナのいずれかに声をかけてください。  

# 記事の編集方法について
GitHubの画面上から実施する方法と、 `git clone` してローカルで編集する方法があります。  
いずれもMarkdown形式で記載可能です。  

### 画面上でページを新規作成する
[Wiki](https://github.com/team-ddd/ddd-book/wiki)の右上にある `New Page` から新規ページを作成してください。  
新規ページを作成したら、[フッター](https://github.com/team-ddd/ddd-book/wiki/_Footer/_edit)と[サイドバー](https://github.com/team-ddd/ddd-book/wiki/_Sidebar/_edit)にも新規ページのリンクを追加してください。  

### 画面上でページを編集する
編集したいページの右上の `Edit` から修正してください。  

### git clone してローカルで新規作成・編集する
[Wiki](https://github.com/team-ddd/ddd-book/wiki)の右下にある `Clone this wiki locally` のURLをローカルに `git clone` して編集してください。  
```
$ git clone https://github.com/team-ddd/ddd-book.wiki.git
```  
特にブランチ運用のルールは作っていないので、masterブランチに push してOKです。

新規ページを作成した場合は、 `_Footer.md` と `_Sidebar.md` にも新規ページのリンクを追加してください。  

# Tips
各ページに目次を作成する際に外部のツールを利用すると便利です。  
Visual Studio Code を使用して編集する場合は[Markdown TOC プラグイン](https://marketplace.visualstudio.com/items?itemName=AlanWalk.markdown-toc)が便利です。  
下記のサイトに使い方が記載されています。  
[GitHub Tips: Markdown に対して目次を作る方法](https://github.com/sakura-editor/sakura/wiki/GitHub-Tips:-Markdown-%E3%81%AB%E5%AF%BE%E3%81%97%E3%81%A6%E7%9B%AE%E6%AC%A1%E3%82%92%E4%BD%9C%E3%82%8B%E6%96%B9%E6%B3%95)
