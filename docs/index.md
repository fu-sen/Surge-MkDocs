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
