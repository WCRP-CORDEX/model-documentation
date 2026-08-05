# CORDEX model documentation

This repository gathers information on CORDEX models documentation and related [discussions](https://github.com/WCRP-CORDEX/model-documentation/issues).
To date, no central resource provides systematic documentation for all CORDEX models and their components.
The closest approach to gather this information is this repository, but the information is not in a common, machine-readable format.

## CORDEX-CMIP5

Some resources exist for individual regional domains, but the most comprehensive documentation was compiled for the IPCC AR6 and maintained at:

Diez-Sierra, J., Iturbide, M., Gutiérrez, J. M., Fernández, J., Milovac, J., Cofiño, A. S., Cimadevilla, E., Nikulin, G., Levavasseur, G., Kjellström, E., Bülow, K., Horányi, A., Brookshaw, A., García-Díez, M., Pérez, A., Baño-Medina, J., Ahrens, B., Alias, A., Ashfaq, M., Bukovsky, M., Buonomo, E., Cabos, W. D., Caluwaerts, S., Chou, S. C., Christensen, O. B., Ciarlò, J. M., Coppola, E., Corre, L., Demory, M.-E., Djurdjevic, V., Evans, J. P., Fealy, R., Feldmann, H., Jacob, D., Jayanarayanan, S., Katzfey, J., Keuler, K., Kittel, C., Kurnaz, M. L., Laprise, R., Lionello, P., McGinnis, S., Mercogliano, P., Nabat, P., Önol, B., Ozturk, T., Panitz, H.-J., Paquin, D., Pieczka, I., Raffaele, F., Remedio, A. R., Scinocca, J., Sevault, F., Somot, S., Steger, C., Tangang, F., Teichmann, C., Termonia, P., Thatcher, M., Torma, C., van Meijgaard, E., Vautard, R., Warrach-Sagi, K., Winger, K., and Zittis, G.: CORDEX model component description, Zenodo, https://doi.org/10.5281/ZENODO.6335378, 2022.

## CORDEX-CMIP6

There is no central resource, but some model documentation is available for different domains in different formats:

| domain | resource | type |
|--------|----------|------|
| MED | https://med-cordex.github.io/model-documentation | Website with free-text description plus [machine-readable metadata](https://github.com/Med-CORDEX/model-documentation/blob/main/_models/CNRM-RCSM6B-SN.md?plain=1) preamble |
| EUR | https://doi.org/10.5281/zenodo.8388778 | Table in PDF format (XLSX, CSV available on request) |

Different degrees of model documentation in various formats is available via the `further_info_url`, which is accessible by following the links under the **source_id** header in the [list of CORDEX-CMIP6 registered models](https://wcrp-cordex.github.io/cordex-cmip6-cv/CORDEX-CMIP6_source_id.html).
Additional information on particular model configurations is sometimes available via the `source_id` registration [GitHub issues](https://github.com/WCRP-CORDEX/cordex-cmip6-cv/issues?q=is%3Aissue%20label%3A%22Register%20source_id%22).
