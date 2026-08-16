# DSH Get Data

Public catalog snapshot for [DSH Get](https://www.dshget.com/), an independent
directory for discovering DeepSeek Harness plugins.

**Browse the live directory:** https://www.dshget.com/

## Snapshot

- 2,460 plugin entries
- 14 categories
- 4 public catalog sources
- English and Chinese descriptions where available
- Repository, install command, license, version, tags, and source attribution

The website is updated more frequently than this repository. Use DSH Get when
you need the latest searchable catalog, category filters, plugin detail pages,
or the plugin knowledge graph.

## Files

- `catalog.json` - Current normalized catalog snapshot used by DSH Get.

Each plugin entry can include:

- `name` and `owner`
- `url` and source repository page
- localized `description`
- `category`, `tags`, and source catalogs
- `install` command
- stars, license, version, and verification metadata when available

## Sources

The snapshot aggregates and deduplicates public metadata from:

- [awesome-dsh-plugin](https://awesome-dsh-plugin.com/)
- [hrhgit/deepseek-harness-plugin-manager](https://github.com/hrhgit/deepseek-harness-plugin-manager)
- [OMDSH Hub](https://github.com/omdsh-dev/dsh-hub-workshop)
- [GitHub's dsh-plugin topic](https://github.com/topics/dsh-plugin)

Source attribution is retained on each entry through the `sources` field.

## Corrections

For a missing plugin or incorrect metadata, open an issue in this repository or
follow the submission guidance on [DSH Get](https://www.dshget.com/).

## Disclaimer

DSH Get is an independently maintained community project and is not affiliated
with or endorsed by DeepSeek. Catalog inclusion is not a security review.
Review third-party source code, permissions, and licensing before installation.

Plugin metadata is aggregated from public sources. Individual repositories and
their contents remain subject to their respective owners' terms and licenses.
