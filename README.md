# Keycloak Quickstart Workshop by @dasniko

![](https://img.shields.io/badge/Keycloak-26.4-blue)

## Voraussetzungen

* Texteditor (Notepad++, VS Code, etc.)
* [Docker](https://www.docker.com/) und [Docker Compose](https://docs.docker.com/compose/) V2 installiert und lauffähig unter `localhost` (ggf. lokale Admin-Rechte auf dem Rechner erteilen)  
  _(ggf. können Lizenzkosten für die Nutzung von Docker Desktop anfallen, bitte informieren! Docker Desktop ist je nach Plattform nicht unbedingt notwendig für den Betrieb von Docker. Support für Docker kann nicht im Rahmen des Trainings und der Vorbereitung dessen übernommen werden! U.U. funktioniert auch Podman, hierfür kann aber keinerlei Support bereitgestellt werden!)_
* Internetzugriff (ggf. Proxy-/Firewall-/VPN-Konfigurationen etc. überprüfen)
* Browser

_Dieses Repository clonen oder über den u.a. Download-Link runterladen und entpacken._

## Download Workshop-Material

👉 https://github.com/dasniko/keycloak-workshop-light/archive/refs/heads/main.zip

## Docker Images

Folgende Docker Images werden im Workshop verwendet und können (sollten!) bereits _vor_ dem Workshop (_aber nicht früher als 1 Woche davor!_) mit den folgenden Befehlen runtergeladen/gepullt werden:

```
docker pull quay.io/keycloak/keycloak:26.4
docker pull axllent/mailpit:latest
docker pull ghcr.io/dasniko/flintstones_ldap:latest
docker pull ghcr.io/dasniko/keycloak-bookshop-demo:0.0.9-snapshot
```

## Folien & Beispiele

* 📺 OAuth2, OIDC & JWT Basics:  
  https://speakerdeck.com/dasniko/oauth2-oidc-and-jwt-important-basics
* 📺 Status Quo of OAuth 2:  
  https://speakerdeck.com/dasniko/status-quo-of-oauth-2
* 📖 Smiling Bookshop (Verteilte Anwendung, Basis Quarkus, Sprint Boot & React.JS):  
https://github.com/dasniko/keycloak-bookshop-demo

## Links für die Workshop-Systeme

* Keycloak - http://localhost:8080
* Bookshop - http://localhost:8081
  * Checkout - http://localhost:3000
* Mailserver - http://localhost:8025

## Weitere Links

### Keycloak Dokumentationen

* Guides: https://www.keycloak.org/guides
* Docs: https://www.keycloak.org/documentation
* Benchmark: https://www.keycloak.org/keycloak-benchmark/
* Terraform Provider: https://registry.terraform.io/providers/keycloak/keycloak/latest/docs

### Allgemeine Beispiele, Erweiterungen & Links

* Niko's YouTube Kanal:
https://www.youtube.com/@dasniko
* Niko's GitHub Profil:
https://github.com/dasniko
* Keycloak Extensions Beispiele:
https://github.com/dasniko/keycloak-extensions-demo
* Testcontainer-Keycloak Projekt:
https://github.com/dasniko/testcontainers-keycloak
* Moderator @ Keycloak Community Forum:
https://forum.keycloak.org/

### Standards, Spezifikationen & BCP Guides

#### OAuth 2.0

* OAuth 2.0 Overview: https://oauth.net/2/
* OAuth Core, RFC 6749: https://datatracker.ietf.org/doc/html/rfc6749
* OAuth 2.0 Threat Model and Security Considerations, RFC 6819: https://datatracker.ietf.org/doc/html/rfc6819
* OAuth 2.0 Token Revocation, RFC 7009: https://datatracker.ietf.org/doc/html/rfc7009
* Proof Key for Code Exchange, RFC 7636: https://datatracker.ietf.org/doc/html/rfc7636
* OAuth 2.0 for Native Apps, RFC 8252: https://datatracker.ietf.org/doc/html/rfc8252
* OAuth 2.0 Device Authorization Grant, RFC 8628: https://datatracker.ietf.org/doc/html/rfc8628
* OAuth 2.0 for Browser-Based Apps: https://datatracker.ietf.org/doc/html/draft-ietf-oauth-browser-based-apps
* Best Current Practice for OAuth 2.0 Security, RFC 9700: https://datatracker.ietf.org/doc/html/rfc9700

#### OAuth 2.1

* OAuth 2.1 Overview: https://oauth.net/2.1/
* OAuth 2.1 Draft: https://datatracker.ietf.org/doc/draft-ietf-oauth-v2-1
* GNAP Overview: https://oauth.net/gnap/

#### Tokens

* OAuth 2.0 Bearer Token Usage, RFC 6750: https://datatracker.ietf.org/doc/html/rfc6750
* OAuth 2.0 Token Binding, Draft: https://datatracker.ietf.org/doc/html/draft-ietf-oauth-token-binding-08
* OAuth 2.0 Mutual-TLS Client Authentication and Certificate-Bound Access Tokens, RFC 8705: https://datatracker.ietf.org/doc/html/rfc8705
* JSON Web Token, RFC 7519: https://datatracker.ietf.org/doc/html/rfc7519
* JSON Web Token (JWT) Best Current Practice, RFC 8725: https://datatracker.ietf.org/doc/html/rfc8725
* JSON Web Token (JWT) Profile for OAuth 2.0 Access Tokens, RFC 9068: https://datatracker.ietf.org/doc/html/rfc9068

#### OIDC

* All OIDC Specifications: https://openid.net/developers/specs/
* OpenID Connect Core 1.0: https://openid.net/specs/openid-connect-core-1_0.html
* OpenID Connect RP-Initiated Logout 1.0: https://openid.net/specs/openid-connect-rpinitiated-1_0.html
* OpenID Connect Session Management 1.0: https://openid.net/specs/openid-connect-session-1_0.html
* OpenID Connect Front-Channel Logout 1.0: https://openid.net/specs/openid-connect-frontchannel-1_0.html
* OpenID Connect Back-Channel Logout 1.0: https://openid.net/specs/openid-connect-backchannel-1_0.html
