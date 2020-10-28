# Atom
- Atomとは，GitHubが開発したオープンソースのテキストエディタである．
- インストールしたパッケージのリスト：[atom_installed_packages.txt](atom_installed_packages.txt)

## インストール
```
apm install --packages-file atom_installed_packages.txt
```

## 更新方法
```
apm list -bi > atom_installed_packages.txt
```

## パッケージ

### [atom-beautify](https://atom.io/packages/atom-beautify)
- コードを整形する．多数のプログラミング言語に対応している．
- Shortcut Key : ctrl + alt + B

### atom-html-preview
- HTMLをリアルタイムにプレビューする．
- Shortcut Key : ctrl + shift + H

### auto-encoding
- 文字コードを自動で判別する．
- Setting : 項目[Disallow some encoding types]に以下の文字コードを設定する．
  ```
  windows1252,iso88591
  ```

### [autocomplete-clang](https://atom.io/packages/autocomplete-clang)
- Clangによるコード補完．C, C++, Objective-Cに対応している．

### autocomplete-cmake
- CMakeのコード補完．

### autocomplete-paths
- ディレクトリの入力補完．

### [docblockr](https://atom.io/packages/docblockr)
- コメントの入力補完．Pythonには対応していない．

### emmet
- HTML/CSSを[Cheat Sheet](https://docs.emmet.io/cheat-sheet/)のように省略して記述できる．

### [git-plus](https://atom.io/packages/git-plus)
- gitコマンドをAtomで操作する．
- Shortcut Key : cmd + shift + H
- よく使うコマンド：Git Add All and Commit, Push

### git-time-machine
- gitのログをグラフで表示して差分を確認する．
- Shortcut Key : alt + T

### gpp-compiler
- C/C++のコンパイルと実行．
- Shortcut Key : F5 (Compile and Run), F6 (Compile and Debug)
- Install : gccを以下のコマンドでインストールする．
  ```
  brew install gcc
  ```
- Setting :項目[C Compiler], [C++ Compiler]にgccのパスを通す．

### highlight-selected
- 選択した文字をハイライトする．

### markdown-preview-plus
- Markdownをリアルタイムにプレビューする．
- Shortcut Key :ctrl + shift + M

### markdown-toc
- 階層構造から目次を生成する．

### markdown-to-pdf
- MarkdownファイルをPDFに変換する．

### minimap
- スクロールしたときにソースコードの全体を表示する．

### minimap-autohide
- スクロールの終了時にminimapを非表示する．

### minimap-git-diff
- minimapに差分をハイライトで表示する．

### minimap-highlight-selected
- 選択中の文字・行をハイライトで表示する．

### platformio-ide-terminal
- Terminalを操作する．
- Shortcut Key :ctrl + `

### project-manager
- プロジェクトとして管理する．
- Shortcut Key :ctrl + cmd + P

### wordcount
- 単語数と文字数を表示する．
