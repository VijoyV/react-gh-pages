# README.md

- This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## What is this Repo / Project ?

This project is created for hosting a react-js based app as github pages.

This has been achieved by executing instructions from:
https://github.com/gitname/react-gh-pages 

## Changes from above instructions

However, there are some changes required for hosting this site to a custom domain named 'pages.vijoy.in'

1. Map a CNAME record with domain registrar (www.onlydomains.com) DNS record entry as as 
| pages | CNAME | vijoyv.github.io. |

2. In the github repo - 'react-gh-pages', go to settings and save custom domain as 
'pages.vijoy.in'

3. In the actual repo, 'package.json' change the homepage as :
"homepage": "http://pages.vijoy.in",

4. Republish each time post changes as 'npm run deploy'  
