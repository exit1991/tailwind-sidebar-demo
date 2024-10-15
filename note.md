
## Tailwind CSS について
[TailwindCSS入門！メリットと使い方をやさしく解説 \| エンジニアBLOG](https://blog.cloudsmith.co.jp/2023/02/330/)

### 使用サンプル・テンプレート
#### サイドバー
https://www.creative-tim.com/twcomponents/component/responsive-sidebar-tailwindcss

#### フォーム
https://flowbite.com/docs/components/forms/

## Font Awesome 参考
- [CDNでFont Awesome 6をで利用する \#CSS \- Qiita](https://qiita.com/day_u/items/cc6dbf7456f122283a96)


## 変え方
### デザイン（色など）を変える時
下記のチートシートを参考にしながら、 `bg-gray-900` や `text-gray-200` などの部分を変更する
- [Tailwind CSS Cheat Sheet](https://www.creative-tim.com/twcomponents/cheatsheet/)

### アイコンを変える時
下記を参考に、FontAwesome でアイコンを探して、`<i>` 要素を置き換える。
- [CDNでFont Awesome 6をで利用する \#CSS \- Qiita](https://qiita.com/day_u/items/cc6dbf7456f122283a96)
- [Font Awesome](https://fontawesome.com/search?o=r&m=free)

### フォントを変える時
Google Font から好きなフォントを見つけてstyleタグ内を変更する。
- [ページにWebフォント（Google Fonts）を使用する方法 \| 記事一覧 \| SPIRAL ナレッジサイト](https://knowledge.spirers.jp/article/development/detail/3636)
- [Browse Fonts \- Google Fonts](https://fonts.google.com/)

```html
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@100..900&display=swap');
        body {
            font-family: 'Noto Sans JP', sans-serif;
        }
    </style>
```

