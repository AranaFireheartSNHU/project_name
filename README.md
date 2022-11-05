# Custom User Template with email username
This is the basic configuration for a Django site that has a Custom User Model defined for the purpose of changing the default Django primary identifier from username to email address.

This will be the starting point for new projects moving forward.

**To use this project:**

1. mkdir **newDjangoProjectName**
2. cd **newDjangoProjectName**
3. pipenv shell
4. python3 -m pip install django
5. django-admin startproject --template _httpLinkToGitHubRepo_ **newDjangoProjectName**
