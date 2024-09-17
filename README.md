# Jupyter Notebook as Open OnDemand App

An interactive Open OnDemand app that launches an Jupyter Notebook using a Apptainer image.

Based on:

* [bc\_osc\_rstudio\_server](https://github.com/OSC/bc_osc_rstudio_server).
* [ood\-bih\-rstudio\-server](https://github.com/bihealth/ood-bih-rstudio-server).
* [bc\_osc\_example\_jupyter](https://github.com/OSC/bc_example_jupyter).

## License

- MIT, see `LICENSE` file.

## Container Building

The app is designed for using the [Continuum](https://hub.docker.com/u/continuumio/) built Docker containers, or those based on them.

For example, you convert the latest Anaconda3 image into an Apptainer image with:

```bash
apptainer pull docker://continuumio/anaconda3:latest
```
