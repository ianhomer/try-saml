# try-saml

Try SAML IDP

# TL;DR

Configure SP

```
export DOJO_SP_APP_ID=set-app-id
export DOJO_SP_ENTITY_ID=https://localhost:8443/
export DOJO_IDP_METADATA_URL=http://idp.ssocircle.com/idp-meta.xml
```

And build

    mvn clean install
    mvn spring-boot:run -pl sp

And access https://localhost:8443/




