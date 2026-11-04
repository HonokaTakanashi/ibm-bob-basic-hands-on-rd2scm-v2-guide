# Bob の画面内でハンズオンガイドを表示する手順

## 目的

ハンズオンガイドを Bob の画面内で表示すると、ブラウザと Bob の 2 画面を行き来する必要がなくなります。
Bob の画面上で、そのままハンズオンガイドを見ながらハンズオンを進められます。

| | 開くウィンドウ | 数 |
|---|---|---|
| 別々に開く場合 | 講師の操作画面（Teams）<br>Bob の画面<br>ブラウザで開いたハンズオンガイドの画面 | 3 |
| **この手順（推奨）** | 講師の操作画面（Teams）<br>Bob の画面（ハンズオンガイドもこの中に表示） | **2** |

今回はウェビナーを見ながら作業していただくため、ウィンドウの切り替えを減らせるこの手順を推奨しています。
なお、別々に開いて進めても、ハンズオンは問題なく実施できます。

## 手順

### 1. URL をコピーします

```
https://github.com/HonokaTakanashi/ibm-bob-basic-hands-on-rd2scm-v2-guide
```

### 2. コマンドパレットを開きます

- Mac: `Cmd + Shift + P`
- Windows/Linux: `Ctrl + Shift + P`

### 3. コマンドを検索します

1. 入力欄に `Quick Open ブラウザー タブ` と入力します。「ブラウザー: Quick Open ブラウザー タブ...」が出たら選びます。

<img src="../Image/show-guide-in-bob-ide/image-1.png" alt="Quick Open ブラウザー タブを選択" width="600" style="border: 1px solid black;">

2. 「新しい統合ブラウザー タブ」が出たら選びます。

<img src="../Image/show-guide-in-bob-ide/image-2.png" alt="新しい統合ブラウザー タブを選択" width="600" style="border: 1px solid black;">

英語の候補が出ない場合は `ブラウザ` や `open browser` でも試してください。

### 4. URL を貼り付けます

1. 「URL を入力」の欄に、コピーした URL を貼り付けます。
2. `Enter` を押します。

### 5. 表示を確認します

Bob のエディタ領域に新しいタブが開き、ハンズオンガイドが表示されます。
ハンズオンガイドを見ながら、横の分割画面で作業できます。

<img src="../Image/show-guide-in-bob-ide/image-3.png" alt="Bob 内に表示されたハンズオンガイド" width="800" style="border: 1px solid black;">

## うまくいかない場合

Bob 内でハンズオンガイドを表示できなくても、ハンズオンの実施には影響しません。
通常のブラウザでハンズオンガイドを開き、Bob とブラウザの 2 画面で進めてください。

### コマンドの候補が出ない

1. `ブラウザ` や `open browser` で検索し直します。
2. それでも出ない場合は、通常のブラウザで URL を開きます。

### ページが表示されない

1. URL が正しいか確認します。
2. 改善しない場合は、通常のブラウザで URL を開きます。
