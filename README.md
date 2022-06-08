# Industry Toolkit

## Contributing to Docs

To add a new asset to the Industry Toolkit, create a new branch and add your markdown file to the appropiate folder within the "docs" directory. Add the path to the new file to the appriopriate section of the mkdocs.yml file.

### Publish Content

This repository has been configured to build and publish the changes automatically via travis-ci. There are two builds currently configured:

- `main` branch is automatically published to the `gh-pages` branch in this repository which is visible on the Industry Toolkit website.

**Note:** There is a time delay between when deploy process completes and when the
content is available on the published site.
