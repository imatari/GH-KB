If you do a git clone and you know the repository you are cloning should ask for username and password but it doesn't and you are on a Windows PC, you may need to review your Generic Credentials in the Crendential Manager found in the Control Panel (see image).  
![Credential Manager](https://user-images.githubusercontent.com/19500800/39739875-0d554c36-5248-11e8-9554-0e99c476152d.jpg)

For my situation I just deleted the Generic Credential for my git and when I tried cloning again in Git Bash I got the prompts for my credentials.

Resource that helped me -> [link](https://cmatskas.com/how-to-update-your-git-credentials-on-windows/)
