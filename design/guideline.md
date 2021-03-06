# ガイドライン

## [ガイドラインの重要性](https://uxmilk.jp/73433)  

- **ユーザーの混乱**：同じアクションなのにさまざまなパターンがあると、ユーザーは混乱してしまいます。
- **遅いデザインプロセス**：再利用可能なデザインアセットがない場合、ゼロからすべてを作る必要があるため、デザイナーのスピードを落とします。
- **遅い開発**：再利用可能なコンポーネントが少ないため、開発を遅らせてしまいます。
- **難しいオンボーディング**：新しく入社したデザイナーや開発者に文書化されていない「システム」を教えることは非常に困難です。

## [Apple, Googleガイドライン比較記事](https://baigie.me/sogitani/2015/07/apple-google-design-guideline/)

[Appleとgoogleのデザインガイドライン比較](https://www.slideshare.net/arasunatomoyuki/applegoogleweb-50201232?ref=https://baigie.me/sogitani/2015/07/apple-google-design-guideline/)  

### 1. 文字
#### 1-1. 最小サイズ
欧文＝11pt、和文＝13pt  

Apple、Googleともに文字の最小サイズに関する具体的な指定があります。双方を判断し、欧文は11pt相当、和文は13pt相当を最小サイズとするのが良いでしょう。  
１ｐｔ＝１.３３ｐｘ   

[16px 未満でフォーム入力時に拡大される。](http://cly7796.net/wp/css/the-screen-zooms-when-filling-out-forms-on-ios/)

### 2. ボタン
#### 2-1. サイズ
横96px×縦96px以上（物理サイズ9mm×9mm以上）  
> Apple  

```
Provide ample touch targets for interactive elements. Try to maintain a minimum tappable area of 44pt x 44pt for all controls.
```

> マテリアルデザイン

```
For most platforms, consider making touch targets at least 48 x 48 dp
```

#### 2-4. マージン
ボタン同士は16px以上離す  
#### 2-6. 配置
目的を達成するボタンを右、行動を取り消すボタンを左に  

行動を選択させるボタンを左右のどちらに配置するか、ということについて、Appleでは破壊的かどうか、Googleでは肯定的かどうかを基準としています。UXに従って考えるべきで、通り一辺倒のルール化は禁物ですが、多くの場合、目的を達成するボタン（「確認」、「実行」など）を右側、行動を取り消すボタン（「キャンセル」「クリア」など）を左側に置くのが基本と捉えておくのがよいでしょう。  
