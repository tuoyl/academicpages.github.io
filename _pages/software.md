---
permalink: /software/
title: "Software"
gallery:
header:
---

Software development using statistical methods or data that observered by instruments has always been a passion of mine.
A good deal of my time is spent to develop software and scripts allow astronomers to better analyze and understand the data. The softwares I developed are related to pulsar timing analysis, GRB data analysis (for SVOM/GRM), pipeline and docker container for HXMTDAS.


# [hxmt_pipeline](https://code.ihep.ac.cn/hxmthsdc/hxmt_pipeline)

[![pipeline status](https://code.ihep.ac.cn/hxmthsdc/hxmt_pipeline/badges/master/pipeline.svg)](https://code.ihep.ac.cn/hxmthsdc/hxmt_pipeline/-/commits/master)
[![coverage report](https://code.ihep.ac.cn/hxmthsdc/hxmt_pipeline/badges/master/coverage.svg)](https://code.ihep.ac.cn/hxmthsdc/hxmt_pipeline/-/commits/master)

I am a developer of the [hxmt_pipeline](https://code.ihep.ac.cn/hxmthsdc/hxmt_pipeline). It is a toolkit wrtten in Python calling the multiple modules in HXMTDAS to perform the data analysis processes. `hxmt_pipeline` is targeted at scientific data analysis by HXMT users and can produce specific products for a variety of data analysis requirements, such as: spectral analysis, timing analysis, phase-resolved spectral analysis, etc.
I have developed both interactive and command-line approaches to use the tool. An example of executing `hpipeline` in interactive method shown below:

```console
$ hpipeline
============================================================
             Running HXMT pipeline (hpipeline)
Task: hpipeline Version: 1.2.4-25  Release Date: 2022.01.05
============================================================
```

# [HXMTDAS docker container](https://github.com/tuoyl/hxmt_docker)
I integrated the HXMTDAS software and environment into the [docker container](https://github.com/tuoyl/hxmt_docker) for easy installation. And maintain the docker container for a long time (although not much people use it T_T)


To install the latest release of hxmt_docker:

```console
docker pull ihepuni/hxmtsoft
```

# [Pulsar analysis package](https://github.com/tuoyl/tat-pulsar)
In my Ph.D period, the main topic of my research is timing analysis of pulsars. We study the evolution of the arrival of periodic signal from neutron star from isolated or binary system. The mesurements from the Crab pulsar could be a good indicator to calibrate the timing stability of the instruments, because of the stable timing properties of the pulsar.
`tat-pulsar` package is developed to perform several timing analysis including:
- search periodic signal
- calculate the ToAs (time of arrival) of signal, and the corresponding errors

the code is used in several publications: 
1. [GECAM timing calibration paper](https://academic.oup.com/mnras/advance-article/doi/10.1093/mnras/stac085/6507588)
2. [HXMT timing calibration paper](https://arxiv.org/pdf/2109.04709.pdf)
3. [4U1901+03 accretiong property study](https://www.sciencedirect.com/sdfe/reader/pii/S2214404820300276/pdf)

# Other resources

- [grmtools](https://code.ihep.ac.cn/svom/grm-product): I am currently working on the SVOM/GRM analyasis tools `grmtools`. It is in the processs of development and is expected to be ready in Alpha version by the end of April 2022.
