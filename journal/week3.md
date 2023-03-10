# Week 3 — Decentralized Authentication
-Setup Cruddr user pool
-Setup Amplify/React configuration
-adjusted the react/js files to integrate Cognito
-Forced username change for cognto user using:
'''
aws cognito-idp admin-set-user-password \
  --user-pool-id us-east-1_jaw7Pu2tA \
  --username mhoustoncruddurtestuser \
  --password Testing1234! \
  --permanent
'''
-Was able to sign in with cognito username/pw
-Tested signout functionality, was working.
-Able to set display name and preferred username
-deleted user
-Got signup functionality working and tested sign in afterwards as well as saw new user creation in userpool in Cognito.
-Successfully forgot password and sent code to reset new password and signin.
