# 李白 聖羅 LP / GitHub Pages用

## 入っているもの

- `index.html`：LP本体
- `styles.css`：デザイン
- `images/main.jpg`：LPトップ用メイン画像
- `images/sub-1.jpg` / `images/sub-2.jpg`：予備画像

## 使い方

1. GitHubのリポジトリに `index.html` と `styles.css` をアップロード
2. Settings → Pages → Branch を `main` / root に設定
3. 表示URLを店ブログ・シティヘブン・SelectTypeなどに貼る

## 差し替える場所

### 写真
`index.html` のこの部分を画像に差し替えます。

```html
<div class="photo-placeholder">
  <span>写真を入れる場合は<br>ここを差し替え</span>
</div>
```

例：

```html
<img class="hero-photo" src="images/main.jpg" alt="聖羅">
```

その場合は `styles.css` に下を追加します。

```css
.hero-photo{width:100%;aspect-ratio:4/5;object-fit:cover;border-radius:26px;display:block;}
```

### 検索に出したくない場合
`index.html` の以下の行のコメントを外してください。

```html
<!-- <meta name="robots" content="noindex, nofollow"> -->
```

### 予約リンク
現在は以下を設定済みです。

- Web予約：`https://seiraripo-reserve.com/`
- LINE：`https://lin.ee/zeVn5rB`
- 李白公式HP：`https://www.ripo-chiba.com/cast/8306/`
- シティヘブン：`https://www.cityheaven.net/chiba/A1201/A120101/ripo_tr/girlid-30041998/?mypage_flg=1`

## 方針

SelectTypeは予約フォームとして使い、GitHub Pages側は「聖羅に会いたくなるためのLP」として使う構成です。


## 今回の更新

LPトップに、既出感が少ない花柄チャイナの別カットを設定済みです。
