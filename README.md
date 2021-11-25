# sofunBench

This contains benchmarking workflows and outputs for each rsofun tag (version).

## Usage

To conduct the benchmarking workflow for a new rsofun tag (version) create a new directory, copy the latest RMarkdown workflow file and adjust their names, including text in the workflow file by:

```sh
mkdir tag_v4.1
cp tag_v4.0/benchmark_gpp_FLUXNET2015_ensemble_v4.0.Rmd tag_v4.1/benchmark_gpp_FLUXNET2015_ensemble_v4.1.Rmd
git add tag_v4.1/benchmark_gpp_FLUXNET2015_ensemble_v4.1.Rmd
```
