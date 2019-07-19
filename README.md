# This project automates the installation of WordPress on Amezmo

# How to
1. Clone this repository into your GitHub account.
2. Setup a new application on your Amezmo account, and head to the Git Wizard to import a repository. More information is located in the documentation located at https://docs.amezmo.com/git/import-or-create-repo.html

# Admin Password
The default password is "password". You should change this. Simply change the password by editing line 37 and 38 inside `.amezmo/after.pull` On line 37 and 38, you should see the following:

```bash
  --admin_password='password' \
  --admin_email='info@amezmo.com' \
```

Edit the values between the quotes to your chosen ones. Make sure to commit your changes before Importing your repository to your Amezmo account.

# More
Learn more about Amezmo at https://www.amezmo.com
