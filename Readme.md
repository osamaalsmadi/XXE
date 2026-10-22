<!-- هنا عرفنا الثغرة بشكل مختصر وواضح -->
# XXE (XML External Entity) Vulnerability
An XML External Entity (XXE) vulnerability is a security flaw that occurs when a poorly configured XML parser processes XML input containing references to an external entity. This allows an attacker to interfere with the application's processing of XML data.

<!-- هنا ذكرنا سيناريوهين للاستغلالع -->
## Exploitation Scenarios
1. **Local File Disclosure (LFD):** Exploiting the vulnerability to retrieve sensitive files from the server's filesystem, such as `/etc/passwd`.
2. **Server-Side Request Forgery (SSRF):** Using the XML parser to make HTTP requests to internal network resources that are otherwise inaccessible from the outside.
