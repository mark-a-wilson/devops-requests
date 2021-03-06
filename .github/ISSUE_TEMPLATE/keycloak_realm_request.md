---
name: Request for KeyCloak Realm
about: To create a set of KeyCloak Realms
title: ''
labels: keycloak-realm
assignees: caggles, ShellyXueHan

---

## Step 0
**Are you the product owner or project admin/team lead?**
If not, you will need to ask one of those two people to make this request for you. We can't process realm requests except from individuals in these roles.

**Do you have an IDIR account?**
We use IDIR authentication for realm admin users, so you *must* have one in order to become a realm admin.  

**Are you requesting for Identity Provider Update?**
If so, you need to be the realm admin and continue to Step 4.


## Step 1
Login to each of the following links using your **IDIR credentials**. You will and see a the "_Forbidden_" message, but this is expected behaviour and will actually create your initial account on KeyCloak.
- https://sso-dev.pathfinder.gov.bc.ca/auth/admin/idir/console
- https://sso-test.pathfinder.gov.bc.ca/auth/admin/idir/console
- https://sso.pathfinder.gov.bc.ca/auth/admin/devhub/console


## Step 2
Fill out the following fields:

* Project Name: 
* Admin of Realm (user's email): 
* For security purpose, please send your IDIR account to this email address - pathfinder@gov.bc.ca

## Step 3
Once you submit your issued and we have completed processing your request, you can proceed to creating a realm at Realm-O-Matic: https://realm-o-matic.pathfinder.gov.bc.ca/



## Step 4
Only fill out the following fields if you have an realm and need to add an IDP:

* Project Name: 
* Realm ID: 
* Admin of Realm (email): 
* For security purpose, please send your IDIR account to this email address - pathfinder@gov.bc.ca
* Identity Provider: IDIR or BCeID or GitHub

