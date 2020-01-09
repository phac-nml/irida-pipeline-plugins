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
| ECTYPER | <https://github.com/phac-nml/irida-plugin-ectyper> | A pipeline to in silico serotype *E.coli* isolates | [![GitHub release](https://img.shields.io/github/release-pre/phac-nml/irida-plugin-ectyper.svg?color=blue)](https://github.com/phac-nml/irida-plugin-ectyper/releases) |
| MLST | <https://github.com/public-health-bioinformatics/irida-plugin-mlst> | A pipeline for traditional MLST using PubMLST schemas. | [![GitHub release](https://img.shields.io/github/release/public-health-bioinformatics/irida-plugin-mlst.svg)](https://github.com/public-health-bioinformatics/irida-plugin-mlst/releases/latest) |
| QI-TAXON | <https://github.com/quadram-institute-bioscience/irida-plugin-qi-taxon> | A pipeline for read based taxon classification. | [![GitHub release](https://img.shields.io/github/release/quadram-institute-bioscience/irida-plugin-qi-taxon.svg)](https://github.com/quadram-institute-bioscience/irida-plugin-qi-taxon/releases/latest) |
| QI-PHYLO | <https://github.com/quadram-institute-bioscience/irida-plugin-qi-phylo> | A pipeline for rFast phylogeny pipeline (Snippy, IQTree) | [![GitHub release](https://img.shields.io/github/release/quadram-institute-bioscience/irida-plugin-qi-phylo.svg)](https://github.com/quadram-institute-bioscience/irida-plugin-qi-phylo/releases/latest) |
| Species Abundance | <https://github.com/public-health-bioinformatics/irida-plugin-species-abundance> | Estimate relative species abundance with Kraken2 & bracken | [![GitHub release](https://img.shields.io/github/release/public-health-bioinformatics/irida-plugin-species-abundance.svg)](https://github.com/public-health-bioinformatics/irida-plugin-species-abundance/releases/latest) |
| Resistance Screen | <https://github.com/public-health-bioinformatics/irida-plugin-resistance-screen> | Detect presence of specific resistance genes | [![GitHub release](https://img.shields.io/github/release/public-health-bioinformatics/irida-plugin-resistance-screen.svg)](https://github.com/public-health-bioinformatics/irida-plugin-resistance-screen/releases/latest) |
| TETyper | <https://github.com/public-health-bioinformatics/irida-plugin-tetyper> | Determine sequence types for specific transposable elements | [![GitHub release](https://img.shields.io/github/release/public-health-bioinformatics/irida-plugin-tetyper.svg)](https://github.com/public-health-bioinformatics/irida-plugin-tetyper/releases/latest) |
| Snippy Single | <https://github.com/public-health-bioinformatics/irida-plugin-snippy-single> | Variant calling against a reference genome for a single isolate  | [![GitHub release](https://img.shields.io/github/release/public-health-bioinformatics/irida-plugin-snippy-single.svg)](https://github.com/public-health-bioinformatics/irida-plugin-snippy-single/releases/latest) |
| MiCall-Lite | <https://github.com/public-health-bioinformatics/irida-plugin-micall-lite> | Hepatitis C Virus Genotyping  | [![GitHub release](https://img.shields.io/github/release/public-health-bioinformatics/irida-plugin-micall-lite.svg)](https://github.com/public-health-bioinformatics/irida-plugin-micall-lite/releases/latest) |
| Plasmid Screen | <https://github.com/public-health-bioinformatics/irida-plugin-micall-lite> | Locate resistance genes on plasmids  | [![GitHub release](https://img.shields.io/github/release/public-health-bioinformatics/irida-plugin-plasmid-screen.svg)](https://github.com/public-health-bioinformatics/irida-plugin-plasmid-screen/releases/latest) |



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
