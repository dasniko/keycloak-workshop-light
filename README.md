# Keycloak Workshop für Einsteiger by @dasniko

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
* Moderator @ Keycloak Discourse Forum:
https://keycloak.discourse.group/
