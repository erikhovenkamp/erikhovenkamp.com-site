# Erik Hovenkamp — Personal academic website

This is a ready-to-publish, one-page academic website for `erikhovenkamp.com`.
It uses only HTML/CSS and a small SVG favicon. There are no subscriptions,
third-party scripts, tracking cookies, fonts, databases, or special software
requirements. The page works in ordinary browsers.

## Preview the site

Open `index.html` in a browser. When you're happy with it, follow the
publication steps below.

## Publish for free with GitHub Pages

1. Create a free account at https://github.com/ if you do not already have one.
2. Select **New repository**. Name it `erikhovenkamp-site` (or similar),
   choose **Public**, then create the repository.
3. Click **Add file > Upload files** and upload the individual website files
   (`index.html`, `favicon.svg`, `CNAME`, `robots.txt`, `sitemap.xml`). You do
   not need to upload this README, but you can. Click **Commit changes**.
4. In the repository, open **Settings > Pages**. Under **Build and deployment**,
   choose **Deploy from a branch**, branch `main`, folder `/(root)`, and Save.
5. The `CNAME` file is already set to `erikhovenkamp.com`. In **Settings > Pages**,
   verify that **Custom domain** shows `erikhovenkamp.com`. If not, enter it
   there and Save.
6. At the company where you purchased the domain, open DNS settings. Create
   these **A** records (Host / Name: `@`) for the bare domain:
       185.199.108.153
       185.199.109.153
       185.199.110.153
       185.199.111.153
   These are GitHub Pages' published IPv4 addresses. If your domain registrar
   already has `@` A records pointing elsewhere, replace those conflicting
   records rather than leaving them alongside these. Do not remove unrelated
   MX/TXT records used for email.
7. Optionally, make `www.erikhovenkamp.com` work too: add a **CNAME** record
   with Host / Name `www` and value `<your-GitHub-username>.github.io`.
   (Replace the placeholder with your actual GitHub username.)
8. DNS changes can take time. When GitHub permits it, enable **Enforce HTTPS**
   under **Settings > Pages**.

You can later update the text by editing `index.html` on GitHub using only
your browser. There is no need to install an editor on your computer.

Official GitHub documentation:
https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site

## Before publishing

Please review all personal and professional information and confirm that the
email address, selected publications, and teaching information are how you
want them displayed. This is a design draft based on public Cornell faculty
materials and a Cornell-hosted CV. No site has been published or DNS modified.

## Sources consulted for the draft

- Cornell Law faculty profile: https://www.lawschool.cornell.edu/faculty-research/faculty-directory/erik-hovenkamp/
- Cornell-hosted CV: https://ww3.lawschool.cornell.edu/faculty/faculty_cvs/Hovenkamp.pdf
- SSRN author page: https://papers.ssrn.com/sol3/cf_dev/AbsByAuth.cfm?per_id=1009772
