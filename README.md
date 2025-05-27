Task 2 – Phishing Email Analysis

Objective - To analyze a suspicious email sample and identify phishing indicators such as spoofed sender addresses, malicious links, and social engineering techniques.

Tools Used -

**Sample Email**:

![Image](https://github.com/user-attachments/assets/9e22fb65-1ed1-4c98-869d-04fad382b2ee)

**Header Analyzer**: Not used (headers not available in this sample)
**Manual Observation**: Link hover, grammar check, sender analysis

Steps Performed -

1. Reviewed the sample email content.
2. Examined the **sender's domain** for legitimacy.
3. Looked for **urgency** or **threatening language**.
4. Checked for **mismatched links** and unsafe download prompts.
5. Identified grammar issues or generic content.
6. Noted all phishing indicators in this README.

Phishing Indicators Found

1. **Suspicious Sender Domain**  
   - `desktop-support@securesupportcloud[.]com`  
   - Not a corporate domain; likely spoofed.

2. **Urgency & Threat Tactics**  
   - Text: *"update by the end of today"*  
   - Creates fear of being locked out of systems.

3. **Deceptive Link**  
   - Text: *“Update Now”*  
   - Link destination is unknown, but clickbait-style wording is suspicious.

4. **Credential Theft Attempt**  
   - Step 2: *"Use your company credentials to verify your identity"*  
   - A classic phishing move to steal login info.

5. **Malicious Attachment Prompt**  
   - Step 3: *"Download and run the update file"*  
   - Encourages running unknown software—high risk of malware.

6. **Generic Targeting**  
   - Addressed to: *"Dear all Contoso Corp employees"*  
   - No personalization—typical of mass phishing campaigns.

7. **Masked Domain Trick**  
   - Sender email includes `[.]com` formatting  
   - Avoids link detection and may bypass filters.

Learnings -

- Recognized phishing signs such as suspicious domains, urgent language, and unsafe links.
- Understood how attackers exploit user fear to gain access to systems.
- Became more aware of social engineering tactics used in corporate phishing attempts.

Recommendations -

**Never click unknown links** or download files from unverified emails.
**Verify sender addresses** and use header analysis tools when possible.
**Report** such emails to the IT department immediately.
