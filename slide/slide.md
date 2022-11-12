---
marp: true
title: 最強に怠惰なターミナルを作ろう 
theme: terminal
footer: @nac-39
---

<!--_class: title-->

<h1 class="title">最高に怠惰なターミナルを作ろう </h1>

---

おしながき

<div class="terminal-timeline">
<div class="terminal-card">

### 1. iterm(ターミナル)

</div>

<div class="terminal-card">

### 2. fig(ターミナル補完)

</div>
<div class="terminal-card">

### 3. zsh(シェル)

</div>
<div class="terminal-card">

### 4. z, fzf コマンド

</div>

<div class="terminal-card">

### 5. dotfiles(設定ファイル)

</div>

---

<!-- class: slide terminal-->

## 1. iterm

- 画面が分けれる
- 上からにょっ
- テーマを変える

![bg right w:500](./img/iterm2.png)

---

## 1. iterm

- 画面が分けれる
- ⌘D
  ![bg right:65% h:400](./img/iterm_uekara.png)

---

## 1. iterm

- 上からにょっ
- Hotkey 機能
- control ダブルタップで出せる
- [https://amateur-engineer-blog.com/iterm2-hotkey/](https://amateur-engineer-blog.com/iterm2-hotkey/)

---

## 2. fig

- ターミナルのコマンドをサジェスト
- よく使うコマンドが上に出てくる

![bg right:45% w:500](./img/fig.png)

---

## 2. fig

- ターミナルのコマンドをサジェスト
- よく使うコマンドが上に出てくる
- docker や git などサブコマンドも出てくる

![bg right:45% w:500](./img/fig_doc.png)

---

## 3. .zshrc

- zshの設定ファイル
- プロンプトを変える
- git-prompt とか
- [https://zenn.dev/kaityo256/articles/zsh-vcs-prompt](https://zenn.dev/kaityo256/articles/zsh-vcs-prompt)

![bg right 100%](./img/prompt_color.png)

---

## 3. .zshrc

- プロンプトを変える
- powerlevel10k とか
- [https://github.com/romkatv/powerlevel10k](https://github.com/romkatv/powerlevel10k)

![bg right 100%](./img/prompt_cool.png)

---

## 3. .zshrc

- プロンプトを変える
- starship とか(powershell でも使える)
- [https://starship.rs/ja-jp/](https://starship.rs/ja-jp/)

![bg right 100%](./img/prompt_starship.png)

---

## 4. z

- ディレクトリに飛べるコマンド
- [https://qiita.com/ucan-lab/items/6cd64e5bec6c3c50e7dc](https://qiita.com/ucan-lab/items/6cd64e5bec6c3c50e7dc)

---

## 4. fzf

- あいまい検索ツール
- [https://qiita.com/kamykn/items/aa9920f07487559c0c7e](https://qiita.com/kamykn/items/aa9920f07487559c0c7e)

---

## 5. dotfiles

- 設定ファイルを集めるもの
- シンボリックリンクを貼って使う

---
