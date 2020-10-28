# ligrafe

## 起動手順

```bash
# DockerComposeのビルド
$ docker-compose build

# コンテナの起動 → localhost:3000でアクセス可能
$ docker-compose up

# コンテナの停止
$ docker-compose down

# コンテナ内でコマンドを実行
$ docker-compose run nuxt 実行コマンド

```

## VSCodeの設定（Lint)
```json
    "editor.codeActionsOnSave": {
        "source.fixAll.eslint": true,
        "source.organizeImports": true,
        "source.fixAll": true
    },
    "editor.formatOnPaste": false,
    "editor.formatOnSave": false,
    "editor.formatOnType": true,    "eslint.validate": [
        "javascript",
        "javascriptreact",
        "vue",
        "typescript"
    ],
    "javascript.format.enable": false,
    "eslint.workingDirectories": [
		"./front"
  ]
```