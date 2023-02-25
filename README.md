### Python3 password decryption tool for the McAfee **SiteList.xml** file.
 
- Author:  jerome.nokin@gmail.com
- Blog:  http://funoverip.net
- Date:  Feb 10 2016

### Installation:

- Ensure you have pyenv and direnv installed.
- `pyenv install 3.10.10`
- Clone directory and enter it.
- `direnv allow`
- `pip install -r requirements.txt`
- Run the script: `python mcafee_sitelist_pwd_decrypt.py ...`

### References:

- https://funoverip.net/2016/02/mcafee-sitelist-xml-password-decryption/
- https://www.reddit.com/r/netsec/comments/43mni7/mcafee_privileged_sitelistxml_leads_to_active/
- https://github.com/tfairane/HackStory/blob/master/McAfeePrivesc.md
- https://www.syss.de/fileadmin/dokumente/Publikationen/2011/SySS_2011_Deeg_Privilege_Escalation_via_Antivirus_Software.pdf

### Example usage:

```
python mcafee_sitelist_pwd_decrypt.py jWbTyS7BL1Hj7PkO5Di/QhhYmcGj5cOoZ2OkDTrFXsR/abAFPM9B3Q==
Crypted password   : jWbTyS7BL1Hj7PkO5Di/QhhYmcGj5cOoZ2OkDTrFXsR/abAFPM9B3Q==
Decrypted password : MyStrongPassword!
```

