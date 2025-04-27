# JF-cloudflared

Run Cloudflare Tunnel Client (formerly Argo Tunnel) on your JF.

`cloudflared` is tunneling daemon that proxies traffic from the Cloudflare network to your origins. This daemon sits between Cloudflare network and your origin (e.g. a webserver). Cloudflare attracts client requests and sends them to you via this daemon, without requiring you to poke holes on your firewall --- your origin can remain as closed as possible.

Extensive documentation can be found in the [Cloudflare Tunnel section](https://developers.cloudflare.com/cloudflare-one/connections/connect-networks/) of the Cloudflare Docs.
