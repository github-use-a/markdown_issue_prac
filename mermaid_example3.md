# Mermaid記法の練習

## ③mermaidで記述できるダイアグラムのチュートリアル（７つのダイアグラムから１つを選択して記述）

## フローチャート（チュートリアル）

1. vscodeの拡張機能である、Markdown All in Oneをインストールします。
2. 左側の拡張機能タブを選択し、検索します。
3. このような画面になります。

![画像](/image/mermaid_4.png)

4. インストールします。
5. flowchart.mdファイルを作成します。
6. 以下のコードを記述します。

```
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

7. ctrl+k,vでレビューし、このような画面になればOKです。

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
下記のサイトを引用致しました。<br>
https://mermaid.js.org/intro/


