This folder contains an experimental/wip effort to make an interactive version of the DORA Core Model -- it's intended to replace the "spider diagram" on `/research` ... see https://github.com/dora-team/dora.dev/discussions/265

### Changelog of Core Model content

- **v1.1.0** (2023-08-07) Added connector between Continuous Delivery and Generative Organizational Culture, and moved those elements closer to facilitate the connection. This connection is motivated by findings across several years of study. It lacks directional arrowheads because there is ongoing research to understand the predictive pathway between these constructs.
- **v1.0.0** (2023-07-19) Initial version proposed for GA


### Ongoing dev process (speculative/experimental)

1. Using Figma, export the Core diagram as SVG, to `dora-core-model-EXPORT.svg`
  * the resulting file will look pretty, but will be lacking key features, including usable `class` and `id` attributes.
1. Run the script: `process-figma-export-to-interactive-core-svg.sh`, which will copy the exported file to `dora-core-model.svg` and perform some text manipulations
1. Implement interactivity by editing the javascript in the template file
1. Also, export PDF and PNG versions and adjust references to them in the template if needed