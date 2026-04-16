# Deep-dive-investigation-
deep-dive investigation into a compromised account using Splunk!
The Trigger: Spotted "Session Flapping" (repeated logins/logouts) for user rmartinez in the VPN logs.The Pivot: Used SPL to correlate the source IP and traced the activity back to Japan—a major anomaly for this user. 🇯🇵The Scoping: Ran a final "hunt" query to ensure no lateral movement or data exfiltration occurred beyond the VPN session.
Nothing beats the feeling of successfully turning raw logs into a clear security story. Huge thanks to TryHackMe for the hands-on lab!
