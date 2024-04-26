# Keycloak Workshop für Einsteiger by @dasniko

## Voraussetzungen

* Texteditor (Notepad++, VS Code, etc.)
* [Docker](https://www.docker.com/) und [Docker Compose](https://docs.docker.com/compose/) V2 installiert und lauffähig (ggf. lokale Admin-Rechte auf dem Rechner erteilen)
* Internetzugriff (ggf. Proxy-/Firewall-/VPN-Konfigurationen etc. überprüfen)
* Browser

## Docker Images

Folgende Docker Images werden im Workshop verwendet und können (sollten!) bereits _vor_ dem Workshop mit den folgenden Befehlen runtergeladen werden:

```
docker pull quay.io/keycloak/keycloak:24.0
docker pull axllent/mailpit:latest
docker pull dasniko/bookshop:0.0.6
```

## Download Workshop-Material

https://github.com/dasniko/keycloak-workshop-light/archive/refs/heads/main.zip

## Allgemeine Beispiele

* Niko's YouTube Kanal:
https://www.youtube.com/@dasniko
* Niko's GitHub Profil:
https://github.com/dasniko
* Keycloak Extensions Beispiele:
https://github.com/dasniko/keycloak-extensions-demo
* Testcontainer-Keycloak Projekt:
https://github.com/dasniko/testcontainers-keycloak

## Workshop-Links

### Securing Applications

OAuth2, OIDC & JWT Basics Präsentation:
https://speakerdeck.com/dasniko/oauth2-oidc-and-jwt-important-basics

Sequenz-Diagramm [Authorization Code Grant OIDC](Seq_Authorization_Code_Grant_OIDC.pdf)

Sequenz-Diagramm [PKCE for OAuth2](Seq_PKCE_for_OAuth2.pdf)

Bookshop (Verteilte Anwendung, Basis Quarkus & React.JS):
https://github.com/dasniko/keycloak-bookshop-demo

## Kontakt

Niko Köbler  
https://www.n-k.de
