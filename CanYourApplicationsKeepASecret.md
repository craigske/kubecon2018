# Can Your Applications Keep a Secret

1. Ecxplosion of containers, tech
2. DevOps lifecycle
3. Security Island
    * A non-interoperable "box"
    * No centralized audit
4. Human Security Islands
    * Engineering teams that operate outside of central governance
5. Continent of Trust
    * A connected set of tools, apps
    * centralized audit
    * centralized admin
    * centralized audit
    * centralized monitoring
6. Common Patterns for Ent App Priv
    * Machine Identity
      * workload
      * service identity
    * Identity factories
      * token based identity. Secret zero problem
    * Service Broker model
      * k8s uses this
      * Easy to automate id but hard to automate auth
    * PKIaaS (public key infa as a svc)
      * central cert auth auto-injects machine identity
      * app uses it's cert to com with secret providers
    * AKI key, pw, token
      * Secret 0 problem
      * istion / service mesh
7. Enabling Auth
    * App auth
    * Retrieve creds via the vault API
    * benefit is flexibility
    * drawback is complex for dev without adding business value
8. Summon (product)
    * app wrapper. `summon node app.js`
    * open source and works with many system
    * can be used in a dev workstation
9. Secretless Broker (open source)
    * uses a local proxy with no creds at all
    * brokers call to external service
    * benefit: 
      * app never needs to know creds at all
      * works with many secrets providers
10. Service Mesh
    * all comms happen over TLS, so secure comms are ensured
11. Security Policy as code
    * Explicit and repeatable automation
    * Audit etc
12. Summary
    * Put these approaches together

Cyberark.com
