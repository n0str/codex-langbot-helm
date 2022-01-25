# Helm Chart for CodeX Lang Bot

https://github.com/codex-team/codex.langbot

You need to get Telegram access token for your bot and apply it via `set`.

Install:
```
helm install codex-langbot langbot --values ./langbot/values.yaml --set token=<...>
```

Uninstall:
```
helm uninstall codex-langbot
```