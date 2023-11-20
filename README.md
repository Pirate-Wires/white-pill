# white-pill

This repository deploys to Vercel and is hosting a \_redirects file to redirect witepill.pw/_ to https://piratewires.com/_

To alias:

Go to domain registrar's DNS settings for whitepill.pw (Google Domains)
Create an ALIAS or ANNAME record pointing whitepill.pw to https://white-pill.vercel.app

Now traffic to whitepill.pw will hit the Vercel deployment first, and get redirected based on the \_redirects file.
