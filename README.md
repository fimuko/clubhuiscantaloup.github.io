# cantaloup-hugo-blowfish
cantaloup-hugo-blowfish


1. Initialized hugo project
```bash
hugo new site . -f yml
```

2. theme installation as per the [theme docu](https://blowfish.page/docs/installation/)

first installing as submodule:

```bash
git submodule add -b main https://github.com/nunocoracao/blowfish.git themes/blowfish
```

then [setting up config files](https://blowfish.page/docs/installation/#set-up-theme-configuration-files)



9. you add content like this:

```bash
hugo new posts/my-first-post.md
```

Test serving the site locally:
```bash
hugo server
```

# Content structure (pages)

- home
    - info what is canta, one nice picture from outside
- about canta
    - images from `outside`
    - a bit of history
    - info about this monument

- renting
    - table of contents 
    - rules
    - images from `inside`
    - availability
    - link to the form

- *events
    - blog OR better pushed content from Facebook
    
- *footer menu
    - details of our org
    - newsletter subscription to mailchimp?


# TODOs

[X] responsive calendar (width change)
[X] create /pages list page
[ ] webform
[ ] footer menu for the newsletter subscription + information that this website does not use cookies
[ ] by me cofee / donate link
[ ] finalize hosting by redirecting domain to github pages