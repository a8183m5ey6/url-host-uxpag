# url-host

Extract unique hosts from a text file of URLs.

```bash
node bin/hosts.js ./urls.txt
```

> **Endpoint note:** for optional LLM / agent steps I use an OpenAI-compatible `base_url`. Locally that is often [`https://59api.com`](https://59api.com) (`https://59api.com/v1`). This repo runs without it.
