# Slide 1

## 見出し2

### 見出し3

#### 見出し4

##### 見出し5

###### 見出し6

<!-- 「---」で次のページに移動する -->

---

# Slide 2

2ページ目。

_アンダースコア斜体_、*アスタリスク斜体*。  
__アンダースコア太字__、**アスタリスク太字**。  

`span` 要素で<span style="color: #f00;">赤色に</span>。

---

# Slide 3-1

<!-- リストの種類に関わらず2スペースでネストできる -->

- リスト
  - ネスト
    - さらにネスト
  - ネスト
    1. 番号付き
    2. 番号付き
      1. 番号ネスト
  - ネスト
- リスト

<!-- 「>>>」で下に移動する -->

>>>

# Slide 3-2

| Heading 1 | Heading 2 | Heading 3 |
|:----------|:---------:|----------:|
| Data 1-1  | Data 1-2  | Data 1-3  |
| Data 2-1  | Data 2-2  | Data 2-3  |
| Data 3-1  | Data 3-2  | Data 3-3  |

---

# Slide 4

<!-- ↓実際は「｀」を半角の「`」に直す -->

```html
<DOCTYPE html>
<html lang="ja">
  <head>
    <meta charset="UTF-8">
    <title>Reveal.js Example</title>
  </head>
  <body>
    <script src="reveal.js"></script>
  </body>
</html>
```