# Example dataset for Dumpling DMS pipeline

This repository contains an example dataset and configuration file to run the [Dumpling](https://github.com/odcambc/dumpling) DMS pipeline. This is a minimal example to
test the pipeline and demonstrate its functionality.

Please see the main repository for more details about the pipeline itself.

## Quick start

```bash
git clone
cd dumpling_example
conda env create --file dumpling_env.yaml
conda activate dumpling_env
snakemake -s workflow/Snakefile --software-deployment-method conda --cores 8
```

## Citations
This workflow is described in the following publication:

* Preprint: [Rao et al., 2023](https://www.biorxiv.org/content/10.1101/2023.10.24.562292v1)
* Published: [Rao et al., 2024](https://doi.org/10.1186/s13059-024-03279-7)

## License

This is licensed under the MIT license. See the LICENSE file for details.

## Getting help

For any issues running this example, please open an issue on the main
[Dumpling](https://github.com/odcambc/dumpling) repository. For
questions or feedback, [email Chris](https://www.wcoyotelab.com/members/).