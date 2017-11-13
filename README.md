# 3DS-QR-Poster

A python3 script that creates and posts QR codes to reddit for new 3DS hombrebrew posted on the /r/3DShacks subreddit.

    pip install requests==2.9.1
    pip install praw==3.5.0
    pip install praw-oauth2util==0.3.4
    pip install humanize==0.5.1
    pip install bs4==4.4.1
	If there is an error installing any of those versions, try installing the newest version instead.

    
You will need to [set up oauth2util](https://github.com/SmBe19/praw-OAuth2Util/blob/master/OAuth2Util/README.md)  
Create a file called `github_credentials.txt` containing
```
username
password
```

and nothing else (no newline at end, not as strings)

Big thanks to /u/codepoet82 for help with SMDH data, github auth, API help, and other things.
