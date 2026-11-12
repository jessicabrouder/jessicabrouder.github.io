# Jessica Brouder

Static portfolio site for GitHub Pages. The site includes the home page, work
gallery, CV, and contact page; all artwork is stored in this repository so it
does not depend on Wix.

## Publish with GitHub Pages

In the repository settings, enable **Pages** and publish the `master` branch
from the repository root. The `CNAME` file sets the custom hostname to
`www.jessicabrouder.com`.

At the domain's DNS provider, point `www` to `jessicabrouder.github.io` with a
CNAME record. To have the apex domain (`jessicabrouder.com`) work as well, set
its A records to GitHub Pages' current IP addresses and configure the apex as
an additional custom domain in Pages. Keep the domain registration; canceling
Wix hosting is separate from changing the domain's DNS. Do not cancel Wix
until the GitHub Pages deployment and custom domain are working over HTTPS.
