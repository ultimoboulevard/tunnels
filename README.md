# tunnels

Stable redirect pages → ephemeral cloudflared quick tunnels.

Each `<name>.html` here is a meta-refresh page pointing to whatever
`*.trycloudflare.com` URL the tunnel currently has. Managed by
[`sctl`](https://github.com/ultimoboulevard/) on the host machine — when a
tunnel restarts and gets a new URL, sctl rewrites the file and pushes.

Share `https://ultimoboulevard.github.io/tunnels/<name>` — that link
stays stable.
