# WordPress on Amezmo

# How to
1. Clone this repository into your GitHub account.
2. Setup a new application on your Amezmo account, and head to the Git Wizard to import a repository. More information is located in the documentation located at https://www.amezmo.com/docs/git

# Admin Password
The default password is "password". You should change this. Simply change the password by editing line 37 and 38 inside `.amezmo/after.pull` On line 37 and 38, you should see the following:

```bash
  --admin_password='password' \
  --admin_email='info@amezmo.com' \
```

Edit the values between the quotes to your chosen ones. Make sure to commit your changes before Importing your repository to your Amezmo account.

# Learn More
Learn more about Amezmo at [https://www.amezmo.com](https://www.amezmo.com/?utm_source=GitHub&utm_campaign=WordpressRepositoryReadMe&utm_medium=social)

# Next (Advanced)
To further leverage Amezmo, you may consider using a more advanced WordPress deployment and caching strategy.
