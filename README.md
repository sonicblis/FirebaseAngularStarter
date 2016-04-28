# App Name
App description.
---
Cloning:
- git clone https://github.com/sonicblis/firebaseangularstarter [newAppName]
- cd [newAppName]
- git remote set-url origin [newAppRepoUrl]
- git push -f
- npm install
- del firebase.json
- firebase init
- gulp publish
- [set up google app](https://console.developers.google.com/project)
  - authorized origins: https://auth.firebase.com
  - authorized redirect: https://auth.firebase.com/v2/**[newAppName]**/auth/google/callback
- enable google auth
