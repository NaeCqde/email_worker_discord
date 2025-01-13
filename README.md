# Cloudflare Email Worker(CF Workers)でDiscord Webhookにメール内容を送れるプログラム

最近互換性フラグがWebからでも設定できるようになったが、コードのコンパイルにWrangler Cliが必要

`wrangler.toml`
```toml
compatibility_flags = ["nodejs_compat"]
DISCORD_WEBHOOK = "https://URL"
```
