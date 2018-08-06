| Run name                        | HA bonus      | HA max| X bonus | Python | dome crawl | New OL correction  | Note                                                         |
| --------------------------------|:-------------:|:-----:|:------: |:------:|:----------:| :----------------: | :-----------:                                                |
| [baseline2018a](#baseline2018a) | 0.3           | 3.0   | 0.0     | 2      |     no     | no                 | Current opsimv4 baseline                                     |
| [mothra_2044](#mothra_2044)     | 0.3           | 3.0   | 0.0     | 3      |     no     | no                 | Python 3 baseline2018a replacement                           |
| [pontus_2003](#pontus_2003)     | 0.3           | 3.0   | 0.0     | 3      |     yes    | no                 | Python 3 baseline2018a replacement (with dome crawl)         |
| [kraken_2026](#kraken_2026)     | 0.3           | 3.0   | 0.0     | 3      |     yes    | yes                | Python 3 baseline2018a replacement (with dome crawl and OL)  |
| [colossus_2665](#colossus_2665) | 0.3           | 3.0   | 0.0     | 3      |     yes    | yes                | Python 3 baseline2018a replacement (with dome crawl and OL), WFD area increased by 1.5 degrees north an south  |
| [pontus_2002](#pontus_2002)     | 0.3           | 3.0   | 0.0     | 3      |     yes    | yes                | Simulation of a PanSTARRs like survey                        |
| [colossus_2664](#colossus_2664) | 0.3           | 3.0   | 0.0     | 3      |     yes    | yes                | WFD cadence in GP. GP proposal turned off                                                  |
| [colossus_2667](#colossus_2667) | 0.3           | 3.0   | 0.0     | 3      |     yes    | yes                | No pairs survey                                                                            |
| [pontus_2489](#pontus_2489)     | 0.3           | 3.0   | 0.0     | 3      |     yes    | yes                | "Many visits" 20s visits with single snap, 40s visits in u band )                          |
| [kraken_2035](#kraken_2035])    | 0.3           | 3.0   | 0.0     | 3      |     yes    | yes                | 9 Deep Drilling Fields (DDFs), 4 already decided + 5 additional                            |
| [mothra_2045](#mothra_2045)     | 0.3           | 3.0   | 0.0     | 3      |     yes    | yes                | 2 alternating Dec bands switched every other year, WFD off                                 |
| [pontus_2502](#pontus_2502)     | 0.3           | 3.0   | 0.0     | 3      |     yes    | yes                | 2 alternating Dec bands switched every other year, WFD on at 25% level                     |
| [kraken_2036](#kraken_2036)     | 0.3           | 3.0   | 0.0     | 3      |     yes    | yes                | Full WFD first and last 2 years, 3 alternating dec bands in between                        |
| [mothra_2048](#mothra_2048)     | 0.3           | 3.0   | 0.0     | 3      |     yes    | yes                | whitepaper2018_2rolling_decbands_wfdbg10p (maybe)                                          |


# Simulations

## Creating a new baseline with latest code, dome crawl, and OL correction delay

### `baseline2018a`
- current opsimv4 baseline
- [configuration repository](https://github.com/lsst-ts/opsim4_config/tree/baseline2018a/config_run)

### `mothra_2044`
- recreation of baseline using Python3 code
- [configuration repository](https://github.com/lsst-ts/opsim4_config/tree/baseline2018_py3/config_run)
- [comparison with baseline2018a](https://github.com/oboberg/lsst_notebooks/blob/master/whitepaper_runs/baseline2018a_mothra2044_comp/README.md)

### `pontus_2003`
- recreation of baseline using Python3 code and dome crawl
- [configuration repository](https://github.com/lsst-ts/opsim4_config/tree/baseline2018_dc/config_run)
- [comparison with baseline2018a](https://github.com/oboberg/lsst_notebooks/blob/master/whitepaper_runs/baseline2018a_pontus2003_comp/README.md)

### `kraken_2026`
- recreation of baseline using Python3 code, dome crawl, and new delay for OL correction
- [configuration repository](https://github.com/lsst-ts/opsim4_config/tree/baseline2018_dc_cl/config_run)
- [comparison with baseline2018a](https://github.com/oboberg/lsst_notebooks/blob/master/whitepaper_runs/baseline2018a_kraken2026_comp/README.md)
- [dither comparison with baseline2018a](https://github.com/oboberg/lsst_notebooks/blob/master/whitepaper_runs/baseline2018a_kraken2026_comp_dither/README.md)
- [comparison with pontus_2003](https://github.com/oboberg/lsst_notebooks/blob/master/whitepaper_runs/pontus_2003_kraken2026_comp/README.md)


## Alternate survey strategies

### `colossus_2665`
- WFD minimum and maximum dec limits increased by 1.5 degrees
- possible new baseline
- [configuration repository](https://github.com/lsst-ts/opsim4_config/tree/baseline2018_dc_cl_wfd15/config_run)
- [comparison with baseline2018a](https://github.com/oboberg/lsst_notebooks/blob/master/whitepaper_runs/baseline2018a_colossus2665_comp/README.md)
- [comparison with kraken_2026](https://github.com/oboberg/lsst_notebooks/blob/master/whitepaper_runs/kraken2026_colossus2665_comp/README.md)
- [dither comparison with kraken_2026](https://github.com/oboberg/lsst_notebooks/blob/master/whitepaper_runs/kraken2026_colossus2665_comp_dither/README.md)

### `pontus_2002`
- Simulation of a PanSTARRs like survey
- WFD + DD WFD having 274000 deg sq (X<1.5, DeMin = -78, DecMax = +18)
- [configuration repository](https://github.com/lsst-ts/opsim4_config/tree/whitepaper2018_big_wfdonly/config_run)
- [comparison with baseline2018a](https://github.com/oboberg/lsst_notebooks/blob/master/whitepaper_runs/baseline2018a_pontus2002_comp/README.md)
- [comparison with kraken_2026](https://github.com/oboberg/lsst_notebooks/blob/master/whitepaper_runs/kraken2026_pontus2002_comp/README.md)
- [dither comparison with kraken_2026](https://github.com/oboberg/lsst_notebooks/blob/master/whitepaper_runs/kraken2026_pontus2002_comp_dither/README.md)

### `colossus_2664`
- WFD through GP
- GP turned off
- [configuration repository](https://github.com/lsst-ts/opsim4_config/tree/whitepaper2018_nogp/config_run)
- [comparison with baseline2018a](https://github.com/oboberg/lsst_notebooks/blob/master/whitepaper_runs/baseline2018a_colossus2664_comp/README.md)
- [comparison with kraken_2026](https://github.com/oboberg/lsst_notebooks/blob/master/whitepaper_runs/kraken2026_colossus2664_comp/README.md)
- [dither comparison with kraken_2026](https://github.com/oboberg/lsst_notebooks/blob/master/whitepaper_runs/kraken2026_colossus2664_comp_dither/README.md)

### `colossus_2667`
- no pairs survey
- same footprint and bonus values used in `baseline2018a`
- [configuration repository](https://github.com/lsst-ts/opsim4_config/tree/whitepaper2018_nopairs/config_run)
- [comparison with baseline2018a](https://github.com/oboberg/lsst_notebooks/blob/master/whitepaper_runs/baseline2018a_colossus2667_comp/README.md)
- [comparison with kraken_2026](https://github.com/oboberg/lsst_notebooks/blob/master/whitepaper_runs/kraken2026_colossus2667_comp/README.md)
- [dither comparison with kraken_2026](https://github.com/oboberg/lsst_notebooks/blob/master/whitepaper_runs/kraken2026_colossus2667_comp_dither/README.md)

### `pontus_2489`
- "Many visits" survey
-  20s visits with single snap in `g,r,i,z,y`
-  40s visits with single snap  un `u` band
- [configuration repository](https://github.com/lsst-ts/opsim4_config/tree/whitepaper2018_manyvisits/config_run)
- [comparison with baseline2018a](https://github.com/oboberg/lsst_notebooks/blob/master/whitepaper_runs/baseline2018a_pontus2489_comp/README.md)
- [comparison with kraken_2026](https://github.com/oboberg/lsst_notebooks/blob/master/whitepaper_runs/kraken2026_pontus2489_comp/README.md)

### `kraken_2035`
- 9 DDFs
- [configuration repository](https://github.com/lsst-ts/opsim4_config/tree/whitepaper2018_9ddfs)
- [comparison with baseline2018a](https://github.com/oboberg/lsst_notebooks/blob/master/whitepaper_runs/baseline2018a_kraken2035_comp/README.md)
- [comparison with kraken_2026](https://github.com/oboberg/lsst_notebooks/blob/master/whitepaper_runs/kraken2026_kraken2035_comp/README.md)

### `kraken_2042`
- Single 30 second snaps
- [configuration repository](https://github.com/lsst-ts/opsim4_config/tree/whitepaper2018_single_snaps_30sec)
- [comparison with kraken_2026](https://github.com/oboberg/lsst_notebooks/blob/master/whitepaper_runs/kraken2026_kraken2042_comp/README.md)
- [dither comparison with kraken_2026](https://github.com/oboberg/lsst_notebooks/blob/master/whitepaper_runs/kraken2026_kraken2042_comp_dither/README.md)

### `mothra_2049`
- WFD + DD WFD having 274000 deg sq (X<1.5, DeMin = -78, DecMax = +18)
- 2 rolling dec bands.
- [configuration repository](https://github.com/lsst-ts/opsim4_config/tree/whitepaper2018_bigwfd_2rolling_dec/config_run)
- [comparison with kraken_2026](https://github.com/oboberg/lsst_notebooks/blob/master/whitepaper_runs/kraken2026_mothra2049_comp/README.md)
- [comparison with pontus_2002](https://github.com/oboberg/lsst_notebooks/blob/master/whitepaper_runs/pontus2002_mothra2049_comp/README.md)

## Rolling cadences


### `mothra_2045`
- Rolling cadence
- 2 alternating Dec bands switched every other year
- No WFD proposal in the background.
- [configuration repository](https://github.com/lsst-ts/opsim4_config/tree/whitepaper2018_2rolling_decbands/config_run)
- [comparison with baseline2018a](https://github.com/oboberg/lsst_notebooks/blob/master/whitepaper_runs/baseline2018a_mothra2045_comp/README.md)
- [comparison with kraken_2026](https://github.com/oboberg/lsst_notebooks/blob/master/whitepaper_runs/kraken2026_mothra2045_comp/README.md)
