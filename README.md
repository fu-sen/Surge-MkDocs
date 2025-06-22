<!-- 2024/10/03 MkDocs 1.6.1 -->

## Surge-MkDocs

**MkDocs with Surge (minimal configuration)**

- [Surge](https://surge.sh/)
- [MkDocs](https://www.mkdocs.org/)

## How to use

1. Edit `mkdocs.yml` and `docs/index.md`, add more files if needed.
2. Change the `docs/CNAME` to the desired `example.surge.sh`. Or you can use the custom domain `example.com`
3. Add the pip package to `requirements.txt` . (Themes and plugins)
4. Get a token with the command `surge token`.
6. The API Key will be displayed, so save this text string.
7. Select `Settings` for your GitHub project.
8. Select `Secrets and variables ` in `Secrets`.
9. Select `Actions`
10. Select `New repository secrets`.
11. Enter `SURGE_LOGIN` in Name and Surge login email in Value.
12. Select `New repository secrets`.
13. Enter `SURGE_TOKEN` in Name and token in Value.
14. Commit to a GitHub project: `git push`

## Build error

Many of the build error are that you mistyped `mkdocs.yml`\
or you forgot to add the package to` requirements.txt`.\
Check the file change immediately before the error occurred.

This is often not a problem with this project.\
You should not open an issue for that.

## Note

`*.surge.sh/robots.txt` is fixed.\
**`*.surge.sh` rejects the search engine crawler.**

If you want to use Surge properly, use Custom Domain.

This sample also uses the [EU.org domains](https://nic.eu.org/),
and Surge deploys it with a custom domains.
