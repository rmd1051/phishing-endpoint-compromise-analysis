Phishing Attack Leading to Endpoint Compromise – SOC Investigation

This project presents a simulated Security Operations Center (SOC) investigation of a phishing attack that led to malware execution and potential system compromise.

🎯 Objective

The goal of this investigation was to:

Analyze a phishing email attack
Identify Indicators of Compromise (IOCs)
Reconstruct the attack timeline
Understand attacker behavior
Recommend mitigation strategies
🧠 Key Findings

The investigation revealed:

A phishing email from a suspicious domain targeting a user
Execution of a malicious file: flbpfuh.exe
Registry modification indicating persistence
Outbound connection to 91.185.23.222
Suspicious login activity involving the Administrator account

🕒 Attack Timeline
Time	Event
08:40	Phishing email received
08:41	Malicious file downloaded
08:42	Registry modified
16:34	Outbound connection to external IP
11:47	User logged off
11:48	Administrator login
🛡️ Analyst Conclusion

The attack likely followed this pattern:

Initial access via phishing email
Malware execution on the victim’s machine
Persistence established via registry changes
Communication with external attacker-controlled IP
Possible privilege escalation

🔐 Recommendations
Implement email filtering and phishing detection
Block malicious IP addresses
Restrict administrative privileges
Enable endpoint detection and monitoring
Conduct user awareness training

💡 Skills Demonstrated
Threat detection & analysis
Log analysis
Incident investigation
SOC workflow understanding
MITRE ATT&CK mapping
📄 Full Report

See attached PDF for detailed analysis.
