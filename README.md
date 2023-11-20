# white-pill

This repository deploys a Serverless Function to Vercel for redirecting the whitepill.pw domain to https://piratewires.com/.

The api/index.js file exports a function that redirects all requests to piratewires.com.

Usage
To alias the domain:

Go to domain registrar's DNS settings for whitepill.pw (Google Domains)
Create an ALIAS or ANNAME record pointing whitepill.pw to the Vercel deployment URL
Now traffic to whitepill.pw will hit the Vercel serverless function first, and get redirected to https://piratewires.com/.

The function returns a 301 permanent redirect status.

Customization
To customize the redirect logic, edit the api/index.js file.
