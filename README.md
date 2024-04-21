<!-- 2024/04/21 MkDocs 1.6.0 -->

## Surge-MkDocs

**MkDocs with Surge (minimal configuration)**

- [Surge](https://surge.sh/)
- [MkDocs](https://www.mkdocs.org/)

## How to use

1. Edit `mkdocs.yml` and `docs/index.md`, add more files if needed.
2. Change the `docs/CNAME` to the desired `example.surge.sh`. Or you can use the custom domain `example.com`
3. Add the pip package to `requirements.txt` . (Themes and plugins)
4. Get a token with the command `surge token`.
5. Select `Settings` for your GitHub project.
6. Select `Actions` in `Secrets`.
7. Select `New repository secrets`.
8. Enter `SURGE_LOGIN` in Name and Surge login email in Value.
9. Select `New repository secrets`.
10. Enter `SURGE_TOKEN` in Name and token in Value.
11. Commit to a GitHub project: `git push`

## Build error

Many of the build error are that you mistyped `mkdocs.yml`\
or you forgot to add the package to` requirements.txt`.\
Check the file change immediately before the error occurred.

This is often not a problem with this project.\
You should not open an issue for that.

## Note

`*.surge.sh/robots.txt` is fixed.\
**`*.surge.sh` rejects the search engine crawler.**

<https://mkdocs-ex.surge.sh/robots.txt>

If you want to use Surge properly, use Custom Domain.
