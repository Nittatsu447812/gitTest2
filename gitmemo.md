# Git学習メモ
## Gitコマンド
### <mark>初期設定</mark>
- **Gitの初期設定を確認**  
$ `git config --list`  
- **ユーザー名の登録**  
$ `git config --global user.name ...`  
- **メールアドレスの登録**  
$ `git config --global user.email ...`  
- **コミットコメント入力エディタをvsCodeに指定**  
$ `git config --global core.editor "code --wait"`  
- **デフォルトブラント名を<u>masterではなくmain</u>に設定**  
$ `git config --global init.defaultBranch main`  
- **Git初期設定を削除する方法**  
$ `git config --global --unset ...`  