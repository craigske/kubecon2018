# How Security of the Cloud helps secure containers workloads in the Cloud

## Henrik Johansson - Office of the CISO AWS Security
## What matters: Visibility
1. Incident Lifecycle
   * log parsing
   * Canaries
   * Tools (scanners etc)
   * Staff, staff and staff
2. Tools for detection
   * AWS GuardDuty
   * AWS Trusted Advisor
   * AWS Shield
   * Cloud Trail
   * 
3. What is a security service
   * AWS guard duty, inspector, Macie...
   * if it can help you with security, use it
4. Container Specific threats
   * Corruption (add something naughty)
   * deps
   * not hardened. Priv esc. Root. API Access
   * network access map to security groups?
   * Secret Manager? Secrets
   * Forensic process
      * autscaling capture
      * memory cap
   * detection services like GaurdDuty
   * Can you isolate IAM creds
5. Reactive Auto Remdiation
   * Instead consider proactive remediation
   * GaurdDuty -> Cloudwatch events -> Lamba remediation
   * Must do a threat vs risk analysis first
6. Takeaways
   * understand shared security model
   * harden
   * structured approach to developing apps and containers
   * Update runbooks
   * 