This is the REPO for my community group website.

[>> LINK TO WEBSITE <<](https://communitygroup.sbalunis.workers.dev/)

The site is build using Hugo with the PaperMod theme. It is utilized by community groups for [Smyrna First Baptist Church]() who do weekly sermon review.

Deployments are managed via [Cloudflare](https://dash.cloudflare.com/a766a302d3491c71a72a5edb5087a500/workers/services/view/communitygroup/production/deployments)

[>> LINK TO DEPLOYMENT <<](https://dash.cloudflare.com/a766a302d3491c71a72a5edb5087a500/workers/services/view/communitygroup/production/deployments)

Commits against the master branch will be rebuilt and deploy automatically. Commits against other branches will be proceeded with the version number for that build & branch.

## Useful Hugo Commands

Create new Discussion Questions Content  
`hugo new content -k discussions content/questions/20260115-discussions.md`