# web.config-File-Upload-RCE-Check

**Description**<br />
IIS7 and higher.<br/>

**Description**<br />
Sometimes IIS supports ASP files but it is not possible to upload any file with .ASP extension. In this case, it is possible to use a web.config file directly to run ASP classic codes:
<br/>

If you upload this web.config file and the file return `3`, then RCE is possible. 
