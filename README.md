# vim
## vim command
### 移動系(Normal Mode)
- 上 / 下 / 左 / 右  
`j` / `k` / `h` / `l`  
- 先頭へ / 終わりに   
`gg` / `G`  
 
- 画面単位  
`Ctrl + b` / `Ctrl + f`   

- 表示している画面上の移動  
`H`: Home / `M`: Middle / `L`: Last  

- 単語単位  
`w` / `b`  

- 行頭 / 行末  
`^` / `$`  

- 文字までジャンプ  
`f(文字)` `;`で次の文字に  

- 対応する{}にジャンプ: `%`  

- *行目にジャンプ: `**G`  

#### 操作
- 直前の操作を繰り返し: `.`  

### 選択系(visual mode) :`v`  
- 行単位  : `V`  
- 矩形単位: `Ctrl + v  `

### カット、コピー、貼付け
- カット : `x` / `dd` / `*dd`  
- コピー : `yy` / `*yy`  
- 貼付け: `p`  

### 検索: `/`
#### `esc`で複数検索  
- 下方向 / 上方向  
`n` / `N`  
- 今カーソルがある位置の単語検索  
`*` / `#`  

### コマンドラインモード: `:`
#### 置換
##### カーソルがある行
- 1つだけ: `:s/[変更前の文字]/[変更後の文字]`  
- 複数  : `:s/[変更前の文字]/[変更後の文字]/g`  
##### 全体
- `:%s/[変更前の文字]/[変更後の文字]/g`  
- 確認を求める  
`:%s/[変更前の文字]/[変更後の文字]/gc` c :comfirm  
### ウィンドウの分割
- 縦 / 横
`:sp` / `:vs` sp:split  
- ウィンドウ間の移動: `Cntl + w`  
- 閉じる: `:close`  
### タブ
- 新しいタブを開く: `:tabnew`  
- ファイルを開く: `:tabe [ファイル名]` e:edit  
- タブ間の移動: `gt`  
- タブを閉じる: `tabclose`  
