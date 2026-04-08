## 📊 Sample Firewall Log Analysis

### Log Entry
Time: 22:14:32  
Source IP: 10.0.0.25  
Destination IP: 142.250.x.x  
Service: HTTPS  
Action: Denied  

### Analysis
- Traffic blocked due to missing allow rule
- Destination is external web service

### Fix
- Created allow rule for HTTPS traffic