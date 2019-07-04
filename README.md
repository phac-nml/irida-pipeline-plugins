# IRIDA Pipeline Plugins

This repository contains a list of pipelines in [IRIDA][] available as plugins.

# Installation

To install each of these plugins, please download the appopriate JAR file from the **Release** link and copy to the directory `/etc/irida/plugins/` on a machine running IRIDA. Then, re-start IRIDA and you should see the pipeline appear in your list of pipelines.

Please see the [IRIDA Pipeline Plugin][] documentation for more details.

# Plugins

| Name | Repository | Description | Release |
|------|------------|-------------|---------|
| Example Plugin | <https://github.com/phac-nml/irida-plugin-example> | An Example plugin to be used as a template for developing IRIDA pipeline plugins. | [![GitHub release](https://img.shields.io/github/release/phac-nml/irida-plugin-example.svg)](https://github.com/phac-nml/irida-plugin-example/releases/latest) |
| AMR Detection | <https://github.com/phac-nml/irida-plugin-amr-detection> | A pipeline for the detection of antimicrobial resistance genes in bacterial isolates. | [![GitHub release](https://img.shields.io/github/release/phac-nml/irida-plugin-amr-detection.svg)](https://github.com/phac-nml/irida-plugin-amr-detection/releases/latest) |
| MLST | <https://github.com/public-health-bioinformatics/irida-plugin-mlst> | A pipeline for traditional MLST using PubMLST schemas. | [![GitHub release](https://img.shields.io/github/release/public-health-bioinformatics/irida-plugin-mlst.svg)](https://github.com/public-health-bioinformatics/irida-plugin-mlst/releases/latest) |
| QI-TAXON | <https://github.com/quadram-institute-bioscience/irida-plugin-qi-taxon> | A pipeline for read based taxon classification. | [![GitHub release](https://img.shields.io/github/release/quadram-institute-bioscience/irida-plugin-qi-taxon.svg)](https://github.com/quadram-institute-bioscience/irida-plugin-qi-taxon/releases/latest) |

# Development

To develop a new plugin, please refer to the [IRIDA Pipeline Plugin][plugin-main] documentation in IRIDA and the [IRIDA Example Plugin][] or existing plugins listed above.

# Contributing

We welcome the contribution of any pipelines you have developed for IRIDA. If you wish to include this pipeline in the list, please submit a *Pull Request* to this repository which adds a new entry to the table in the **Plugins** section. This will be in the format of:

```
| [NAME] | [REPOSITORY/URL] | [DESCRIPTION] | [RELEASE] |
```

The `[RELEASE]` could be a direct link to your GitHub releases page (e.g., <https://github.com/phac-nml/irida-plugin-amr-detection/releases>), a link to the appropriate JAR file, or if you wish to make use of a badge for your release/repository, you can refer to <https://shields.io/category/version>.

# License

Text in this repository is licensed under the **Creative Commons Attribution 4.0 International** <https://creativecommons.org/licenses/by/4.0/> license. Licenses for each IRIDA plugin are specific to each plugin and should be available from the respective code repositories.

[IRIDA]: https://github.com/phac-nml/irida/
[IRIDA Pipeline Plugin]: https://irida.corefacility.ca/documentation/developer/tools/pipelines/#4-test-in-irida
[plugin-main]: https://irida.corefacility.ca/documentation/developer/tools/pipelines/
[IRIDA Example Plugin]: https://github.com/phac-nml/irida-plugin-example
