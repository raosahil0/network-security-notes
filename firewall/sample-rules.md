## 🔥 Sample Firewall Rule Configuration (Sophos)

### Scenario
Allow HTTPS traffic for internal users to access external web services.

### Rule Configuration
- Source Zone: LAN
- Source Network: Any
- Destination Zone: WAN
- Destination Network: Any
- Service: HTTPS (Port 443)
- Action: Allow
- Log Traffic: Enabled

### Notes
- Rule priority placed above deny rules
- Logging enabled for monitoring access