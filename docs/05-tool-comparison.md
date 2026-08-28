# 05-Tool Comparison

| Tool | Access model | Connection method | Best fit |
|---|---|---|---|
| **RDP** | Unattended (native Windows) | Direct over LAN/VPN | Internal networks, domain-joined machines, sysadmin-style access |
| **AnyDesk** | Unattended (password-based) | Relay / direct, lightweight | Fast, low-bandwidth remote support; common with independent technicians and smaller IT shops |
| **TeamViewer QuickSupport** | Attended, ad-hoc only | Relay, no install/account | One-off support requests where the end-user is present and no persistent access is wanted |

**Key takeaway:** unattended tools (RDP, AnyDesk) are suited to recurring support or scheduled maintenance where no one needs to be at the keyboard. Ad-hoc/attended tools (QuickSupport) are better suited to one-time troubleshooting requests, since no persistent access is left behind on the client machine, a meaningful distinction for security posture in a real support role.

