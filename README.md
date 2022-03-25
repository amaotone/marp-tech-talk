---
marp: true
theme: yutori
size: 16:9
paginate: true
headingDivider: 2
---

# Yutori

<!-- _class: center -->

"Yutori" は日本語もコードも綺麗に表示される Marp テーマです。

本文には [M PLUS 2](https://mplusfonts.github.io/) 、ソースコードには [Fira Mono](http://mozilla.github.io/Fira/) を採用しています。

## Usage

`.vscode/settings.json` に `markdown.marp.themes` の項目を追加してください。

```json
{
  "markdown.marp.themes": [
    "https://raw.githubusercontent.com/amaotone/marp-theme-yutori/main/theme/yutori.css"
  ]
}
```

`.md` ファイルのヘッダー部分に `theme: yutori` を追加してください。

```yaml
---
marp: true
theme: yutori
---
```

## Additional Classes

|名前|使いみち|
|:--|:--|
|center|中央揃えになります（表紙やアイキャッチに使います）|
|outline|スライドの縁を塗ります（付録ページに使います）|

## Contribution

<!-- _class: outline -->

Issue もしくは Pull Request を出してください