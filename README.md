# Denmark Carrom Association

DKCA enables Denmark residents to play carrom tournaments in European countries & international level. We are a community of carrom enthusiasts who help new players understand the game and improve their skills through regular play. Our association is dedicated to promoting carrom as a fun and competitive sport.


# Website Development

## Idea
Website is developed using Hugo & Github Pages.
Hugo + Github pages
References:
https://4bes.nl/2021/08/29/create-a-website-with-hugo-and-github-pages/
https://medium.com/@magstherdev/github-pages-hugo-86ae6bcbadd
https://gohugo.io/getting-started/quick-start/


## DNS Hosting
godaddy.com --> carrom.dk
Github pages namespace service confirguration is already added. Ref: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site

Domain configuration is done at: `Repository Settings > Pages > Custom domain`

## Website Hosting
Github Pages

## Local Development
Required: `hugo cli` and installation steps at: https://gohugo.io/installation/
To run website locally, use command: `hugo server --disableFastRender`
In addition, you can disable Chrome browser cache via Developer options.

## Production ready
When you are ready to deploy, use command `hugo` to generate `docs` folder.

## Github pages
Production deployment goes via `main` branch and points to `docs` folder.
However, if you want to display `Website under maintainance` message, ensure deployment points to `/` which is root directory.
Configuration is available under: `Repository Settings > Pages`

## Deployment website
https://carrom.dk

## Troubleshooting
If facing `submodule url not found` error, refer: https://confluence.atlassian.com/bbkb/fix-error-fatal-no-url-found-for-submodule-path-in-gitmodules-1188400518.html


# Special recognization
Thank you for Github theme: https://github.com/zerostaticthemes/hugo-serif-theme
Integrating Facebook events: https://www.sociablekit.com/
