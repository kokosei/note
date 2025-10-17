# Gitの認証でエラーが出る
```
Username for 'https://github.com': 「ユーザー名」
Password for 'https://「ユーザー名」@github.com': 
remote: Invalid username or token. Password authentication is not supported for Git operations.
```
の解決法。

1. 右上アイコンをクリック
2. {歯車} Settings
3. {<>} Developer settings　メニューの一番下
4. {鍵} Personal access tokens {v}
5. Tokens (classic)
6. Generate new token {v}
7. Generate new token (classic)
8. Note を適当に埋める
9. Expiration も適当に変える
10. repo を全体チェック
11. Generate token
12. 生成されたキーを確実にコピーし、Passwordの欄に貼り付ける（表示されないので注意）
