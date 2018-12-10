# Operations after Deployment
AWS, Chris Hein

1. Least priv
    * RBAC
    * Audit roles
    * QR code in photos
    * use and indentity provider
      * SMB
      * IAM
      * aws-iam-authenicator
2. rehash pod sec/network/non-root policies
3. Scans
    * Envs
    * Images
    * CI/CD automation
4. Nist Framework:
    * Identify
      * teach about attack vectors
      * container isolation
      * network security
      * host access
    * Protect
      * set a baseline. ML tools for syscalls etc
      * build models
      * 
    * Detect
      * Alert on events not in the baseline
      * notifications (slack, email, pagerduty)
    * Respond
      * Cordon node
      * Isolate nodes on network
      * pause container / snaphot
      * analyse logs
    * Recover
      * Root cause / RCA
      * patch / fix
      * use a CI/CD pipeline rollout change

5. Summary
    * k8s doesn't solve all problems
    * use OSS and commercial products
    * security is day 0

