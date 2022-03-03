# ComicControl
A Repo for bugfix/tweaks for ComicControl

Please note that this repo contains primarily bugfixes/tweaks against stock ComicControl and is not intended as a replacement or rework.

Some notable changes are for one-off use cases or security issues.

# Should I use a make multiple comics as modules or use one copy multiple times?

The standard way to use ComicControl is to make one module per comic that is underneath the domain, eg example.com , example.com/comicone example.com/comictwo

If a comic is instead multiple subdomains eg comicone.example.com comictwo.example.com and these are defined as separate document_root's under the same account, it may make more sense to install comiccontrol once, create separate configurations per subdomain, and simply copy or hardlink to the same comiccontrol folder. This will depend on your setup.
