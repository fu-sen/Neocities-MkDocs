<!-- 2024/10/03 MkDocs 1.6.1 -->

## Neocities-MkDocs

**MkDocs with Neocities (minimal configuration)**

- [Neocities](https://neocities.org/)
- [MkDocs](https://www.mkdocs.org/)

## How to use

1. Edit `mkdocs.yml` and `docs/index.md`, add more files if needed.
2. Add the pip package to `requirements.txt` . (Themes and plugins)
3. Log in to Neocities and select `Settings`.
4. Select `Manage Site Settings` in` Manage Sites`.
5. Select `Generate API Key` in` API Key`. 
6. The API Key will be displayed, so save this text string.
7. Select `Settings` for your GitHub project.
8. Select `Actions` in `Secrets`.
9. Select `New repository secrets`.
10. Enter `NEOCITIES_API_KEY` in Name and API Key in Value.
11. Commit to a GitHub project: `git push`

## Build error

Many of the build error are that you mistyped `mkdocs.yml`
or you forgot to add the package to` requirements.txt`.
Check the file change immediately before the error occurred.

This is often not a problem with this project.
You should not open an issue for that.
