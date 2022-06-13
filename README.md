## Surge-MkDocs

**MkDocs with Surge (minimal configuration)**

- [Surge](https://surge.sh/)
- [MkDocs](https://www.mkdocs.org/)

## How to use

1. Edit `mkdocs.yml` and `docs/index.md`, add more files if needed.
2. Add the pip package to `requirements.txt` . (Themes and plugins)
3. Get a token with the command `surge token`.
4. Select `Settings` for your GitHub project.
5. Select `Actions` in `Secrets`.
6. Select `New repository secrets`.
7. Enter `SURGE_LOGIN` in Name and Surge login email in Value.
6. Select `New repository secrets`.
9. Enter `SURGE_TOKEN` in Name and token in Value.
10. Commit to a GitHub project: `git push`

## Build error

Many of the build error are that you mistyped `mkdocs.yml`
or you forgot to add the package to` requirements.txt`.
Check the file change immediately before the error occurred.

This is often not a problem with this project.
You should not open an issue for that.
