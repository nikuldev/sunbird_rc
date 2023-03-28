# SunbirdRC Infra setup

### Linux/Ubuntu

```sh
npm install --global registry-cli
Fetched all the containers manually
Regsitry init.(command)
Added local tunelling to access keycloak admin UI.
Added host & port details of keycloak inside the hosts file.
Marked ssl as off inside the keycloak admin panel for accessing the UI without tunelling.
APIs with access_token were failing & 401 error code was returning. (SSL certificate & domain naming was required for accessing the APIs).
```




### Windows

```sh
Installed docker app on the system.
Added host & port details of keycloak inside the hosts file.
```

### reference documents
* Setup Registry - https://docs.sunbirdrc.dev/developer-documentation/setup-a-registry-instance
* Installation without docker - https://docs.sunbirdrc.dev/developer-documentation/installation-guide
