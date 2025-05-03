# TrueNAS Scale: Generate ACME DNS SSL certificate with Cloudflare and Let's Encrypt

<b>Prerequisites:</b>

* Basic network configuration on TrueNAS scale
  * Hostname
  * Domain
* DNS record on local DNS server
* Cloudflare account with domain

<b>Objectives:</b>

* Configure email for root user
  * me@lan.z1.network
* Generate Cloudflare API token
  * [cloudflare.com](cloudflare.com)
  * Profile -> API Tokens -> Create Token -> Edit zone DNS
    * READ Zone.Zone
* Configure ACME DNS-Authenticators
  * Name: acme
  * Authenticator: cloudflare
  * API token: ?
* Configure Certificate Signing Requests
  * Name: etsencrypt-csr
  * Country: Lithuania
  * State: home
  * Locality: lab
  * Organization: lan.z1.network
  * Email: me@lan.z1.network
  * Subject Alternative Name: scale04.lan.z1.network
* Create ACME Certificate
  * Identifier: letsencrypt
* Configure GUI SSL Certificate : letsencrypt
* Web Interface HTTP -> HTTPS Redirect