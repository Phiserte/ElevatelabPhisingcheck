## Steps involved in analysing the phsising email
- 1) Check the sender mail . In the taken example email the sender mail address is support.microsoft@email.records where as original mail is support@microsoft.com.
- 2) Analyze the header using google message box
     - Key points header analyzation
        -Shows it came from an unknown ip address
        - Failing SPF means the domain wasn't authorized to send email from that IP.
        - Digital signature was failed
        - mail didn’t align with the domain’s DMARC policy
 - 3) The mail is creating sense of urgency by saying high priority security alert
 - 4) Check the mail with attachments for .zip .exe which may deliver certain malwares
   These are the traits of possble phising email
