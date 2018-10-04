# Table of Contents
1. [fO](#fo)
2. [Total Effective Time](#total-effective-time)
3. [Normalized Effective Time](#normalized-effective-time)
4. [Open Shutter Fraction](#open-shutter-fraction)
5. [Parallax](#parallax)
6. [Proper Motion](#proper-motion)
7. [Rapid Revisit](#rapid-revisit)
8. [Fraction in Pairs](#fraction-in-pairs)
9. [Slews](#slews)
10. [Filter Changes](#filter-changes)
11. [Nvisits](#nvisits)
12. [Proposal Fractions](#proposal-fractions)
13. [Median Nvisits WFD](#median-nvisits-wfd)
14. [Median CoaddM5 WFD](#median-coaddm5-wfd)
15. [Median FiveSigmaDepth](#median-fivesigmadepth)
16. [Median Internight Gap](#median-internight-gap)
17. [Median Airmass WFD](#median-airmass-wfd)
18. [Median Seeing WFD](#median-seeing-wfd)
19. [Skymap comparisons](#skymap-comparisons)
20. [Histogram comparisons](#histogram-comparisons)

# fO
|                                                       |   kraken_2026 |   pontus_2565 |
|:------------------------------------------------------|--------------:|--------------:|
| fOArea fO All visits HealpixSlicer                    |     18056.6   |     18308.4   |
| fOArea/benchmark fO All visits HealpixSlicer          |         1.003 |         1.017 |
| fONv MedianNvis fO All visits HealpixSlicer           |       940     |      1066     |
| fONv MinNvis fO All visits HealpixSlicer              |       857     |       960     |
| fONv/benchmark MedianNvis fO All visits HealpixSlicer |         1.139 |         1.292 |
| fONv/benchmark MinNvis fO All visits HealpixSlicer    |         1.039 |         1.164 |
| fOArea fO WFD HealpixSlicer                           |     18040.6   |     17915.6   |
| fOArea/benchmark fO WFD HealpixSlicer                 |         1.002 |         0.995 |
| fONv MedianNvis fO WFD HealpixSlicer                  |       938     |      1063     |
| fONv MinNvis fO WFD HealpixSlicer                     |       857     |       744     |
| fONv/benchmark MedianNvis fO WFD HealpixSlicer        |         1.137 |         1.288 |
| fONv/benchmark MinNvis fO WFD HealpixSlicer           |         1.039 |         0.902 |

# Total Effective Time
|                          |   kraken_2026 |   pontus_2565 |
|:-------------------------|--------------:|--------------:|
| Total Teff all bands     |   4.08386e+07 |   3.9841e+07  |
| Total Teff WFD all bands |   3.68931e+07 |   3.56664e+07 |

# Normalized Effective Time
|                                                    |   kraken_2026 |   pontus_2565 |
|:---------------------------------------------------|--------------:|--------------:|
| Mean Normalized Teff WFD all bands HealpixSlicer   |         0.583 |         0.578 |
| Median Normalized Teff WFD all bands HealpixSlicer |         0.584 |         0.597 |
| Normalized Teff WFD all bands HealpixSlicer        |     21495     |     23418     |
| Normalized Teff WFD all bands                      |         0.584 |         0.583 |

# Open Shutter Fraction
|                                                 |   kraken_2026 |   pontus_2565 |
|:------------------------------------------------|--------------:|--------------:|
| OpenShutterFraction All visits                  |         0.735 |         0.721 |
| Mean OpenShutterFraction Per night OneDSlicer   |         0.735 |         0.722 |
| Median OpenShutterFraction Per night OneDSlicer |         0.739 |         0.722 |
| OpenShutterFraction Per night OneDSlicer        |      3025     |      3025     |

# Parallax
|                                                                |   kraken_2026 |   pontus_2565 |
|:---------------------------------------------------------------|--------------:|--------------:|
| Median Parallax Error @ 22.4 All visits HealpixSlicer          |         1.816 |         1.72  |
| Median Parallax Error @ 24.0 All visits HealpixSlicer          |         7.066 |         6.715 |
| Median Parallax Coverage @ 22.4 All visits HealpixSlicer       |         0.555 |         0.57  |
| Median Parallax Coverage @ 24.0 All visits HealpixSlicer       |         0.551 |         0.565 |
| Median Parallax-DCR degeneracy @ 22.4 All visits HealpixSlicer |         0.237 |         0.27  |
| Median Parallax-DCR degeneracy @ 24.0 All visits HealpixSlicer |         0.235 |         0.269 |
| Median Parallax Error @ 22.4 WFD HealpixSlicer                 |         1.606 |         1.569 |
| Median Parallax Error @ 24.0 WFD HealpixSlicer                 |         6.175 |         6.052 |
| Median Parallax Coverage @ 22.4 WFD HealpixSlicer              |         0.559 |         0.587 |
| Median Parallax Coverage @ 24.0 WFD HealpixSlicer              |         0.555 |         0.583 |
| Median Parallax-DCR degeneracy @ 22.4 WFD HealpixSlicer        |         0.175 |         0.277 |
| Median Parallax-DCR degeneracy @ 24.0 WFD HealpixSlicer        |         0.172 |         0.275 |

# Proper Motion
|                                                            |   kraken_2026 |   pontus_2565 |
|:-----------------------------------------------------------|--------------:|--------------:|
| Median Proper Motion Error @ 20.5 All visits HealpixSlicer |         0.17  |         0.157 |
| Median Proper Motion Error @ 24.0 All visits HealpixSlicer |         1.813 |         1.663 |
| Median Proper Motion Error @ 20.5 WFD HealpixSlicer        |         0.166 |         0.153 |
| Median Proper Motion Error @ 24.0 WFD HealpixSlicer        |         1.677 |         1.575 |

# Rapid Revisit
|                                                      |   kraken_2026 |   pontus_2565 |
|:-----------------------------------------------------|--------------:|--------------:|
| Area (sq deg) RapidRevisits All visits HealpixSlicer |     10178     |     27547.8   |
| Mean RapidRevisits All visits HealpixSlicer          |         0.247 |         0.668 |
| Median RapidRevisits All visits HealpixSlicer        |         0     |         1     |
| RapidRevisits All visits HealpixSlicer               |     31116     |     32099     |
| Area (sq deg) RapidRevisits WFD HealpixSlicer        |     10757.1   |     36820.8   |
| Mean RapidRevisits WFD HealpixSlicer                 |         0.261 |         0.893 |
| Median RapidRevisits WFD HealpixSlicer               |         0     |         1     |
| RapidRevisits WFD HealpixSlicer                      |     21495     |     23418     |

# Fraction in Pairs
|                                                                          |   kraken_2026 |   pontus_2565 |
|:-------------------------------------------------------------------------|--------------:|--------------:|
| Median Fraction of visits in pairs (15-60 min) gri HealpixSlicer         |         0.868 |         0.898 |
| Median Fraction of visits in pairs (15-60 min) gri WFD+NES HealpixSlicer |         0.876 |         0.907 |

# Slews
|                            |   kraken_2026 |   pontus_2565 |
|:---------------------------|--------------:|--------------:|
| Mean slewTime All visits   |         6.789 |         7.623 |
| Median slewTime All visits |         4.792 |         4.952 |

# Filter Changes
|                                            |   kraken_2026 |   pontus_2565 |
|:-------------------------------------------|--------------:|--------------:|
| Filter Changes Whole Survey                |     10813     |     19030     |
| Filter Changes Per Night OneDSlicer        |      3025     |      3025     |
| Mean Filter Changes Per Night OneDSlicer   |         3.177 |         6.146 |
| Median Filter Changes Per Night OneDSlicer |         2     |         6     |

# Nvisits
|                                     |    kraken_2026 |    pontus_2565 |
|:------------------------------------|---------------:|---------------:|
| Fraction of total Nvisits All props |    1           |    1           |
| Nvisits All props                   |    2.43839e+06 |    2.39777e+06 |
| Mean Nvisits All props OneDSlicer   |  806.079       |  792.651       |
| Median Nvisits All props OneDSlicer |  806           |  798           |
| Nvisits All props OneDSlicer        | 3025           | 3025           |

# Proposal Fractions
|                                                  |   kraken_2026 |   pontus_2565 |
|:-------------------------------------------------|--------------:|--------------:|
| Fraction of total Nvisits All props              |         1     |         1     |
| Fraction of total Nvisits SouthCelestialPole     |         0.02  |         0.027 |
| Fraction of total Nvisits NorthEclipticSpur      |         0.054 |         0.061 |
| Fraction of total Nvisits GalacticPlane          |         0.016 |         0.019 |
| Fraction of total Nvisits WFD                    |         0.864 |         0.85  |
| Fraction of total Nvisits DeepDrillingCosmology1 |         0.046 |         0.042 |
| Fraction of total Nvisits DD                     |         0.046 |         0.042 |
| Fraction of total Nvisits WideFastDeep           |         0.864 |         0.85  |

# Median Nvisits WFD
|                                            |   kraken_2026 |   pontus_2565 |
|:-------------------------------------------|--------------:|--------------:|
| Median NVisits WFD i band HealpixSlicer    |           204 |           231 |
| Median NVisits WFD g band HealpixSlicer    |            90 |           102 |
| Median NVisits WFD y band HealpixSlicer    |           188 |           202 |
| Median NVisits WFD u band HealpixSlicer    |            64 |            72 |
| Median NVisits WFD r band HealpixSlicer    |           206 |           232 |
| Median NVisits WFD z band HealpixSlicer    |           186 |           213 |
| Median NVisits WFD all bands HealpixSlicer |           938 |          1056 |

# Median CoaddM5 WFD
|                                         |   kraken_2026 |   pontus_2565 |
|:----------------------------------------|--------------:|--------------:|
| Median CoaddM5 WFD i band HealpixSlicer |        26.618 |        26.641 |
| Median CoaddM5 WFD g band HealpixSlicer |        27.149 |        27.205 |
| Median CoaddM5 WFD y band HealpixSlicer |        24.906 |        24.911 |
| Median CoaddM5 WFD u band HealpixSlicer |        25.651 |        25.722 |
| Median CoaddM5 WFD r band HealpixSlicer |        27.201 |        27.246 |
| Median CoaddM5 WFD z band HealpixSlicer |        25.72  |        25.888 |

# Median FiveSigmaDepth
|                                                           |   kraken_2026 |   pontus_2565 |
|:----------------------------------------------------------|--------------:|--------------:|
| Median Median Inter-Night Gap WFD i band HealpixSlicer    |        10.957 |        11.454 |
| Median Median Inter-Night Gap WFD g band HealpixSlicer    |        25.858 |        26.371 |
| Median Median Inter-Night Gap WFD y band HealpixSlicer    |         3.962 |         5.971 |
| Median Median Inter-Night Gap WFD u band HealpixSlicer    |        23.959 |        26.392 |
| Median Median Inter-Night Gap WFD r band HealpixSlicer    |         7.941 |        11.009 |
| Median Median Inter-Night Gap WFD z band HealpixSlicer    |         5.994 |        11.952 |
| Median Median Inter-Night Gap WFD all bands HealpixSlicer |         1.956 |         1.995 |

# Median Internight Gap
|                                                          |   kraken_2026 |   pontus_2565 |
|:---------------------------------------------------------|--------------:|--------------:|
| Median Median fiveSigmaDepth WFD i band HealpixSlicer    |        23.691 |        23.656 |
| Median Median fiveSigmaDepth WFD g band HealpixSlicer    |        24.646 |        24.653 |
| Median Median fiveSigmaDepth WFD y band HealpixSlicer    |        21.997 |        21.999 |
| Median Median fiveSigmaDepth WFD u band HealpixSlicer    |        23.337 |        23.356 |
| Median Median fiveSigmaDepth WFD r band HealpixSlicer    |        24.263 |        24.253 |
| Median Median fiveSigmaDepth WFD z band HealpixSlicer    |        22.783 |        22.934 |
| Median Median fiveSigmaDepth WFD all bands HealpixSlicer |        23.492 |        23.468 |

# Median Airmass WFD
|                                                   |   kraken_2026 |   pontus_2565 |
|:--------------------------------------------------|--------------:|--------------:|
| Median Median airmass WFD i band HealpixSlicer    |         1.044 |         1.054 |
| Median Median airmass WFD g band HealpixSlicer    |         1.044 |         1.055 |
| Median Median airmass WFD y band HealpixSlicer    |         1.079 |         1.058 |
| Median Median airmass WFD u band HealpixSlicer    |         1.044 |         1.056 |
| Median Median airmass WFD r band HealpixSlicer    |         1.043 |         1.054 |
| Median Median airmass WFD z band HealpixSlicer    |         1.05  |         1.059 |
| Median Median airmass WFD all bands HealpixSlicer |         1.045 |         1.056 |

# Median Seeing WFD
|                                                     |   kraken_2026 |   pontus_2565 |
|:----------------------------------------------------|--------------:|--------------:|
| Median Median seeingEff WFD i band HealpixSlicer    |         0.827 |         0.832 |
| Median Median seeingEff WFD g band HealpixSlicer    |         0.891 |         0.898 |
| Median Median seeingEff WFD y band HealpixSlicer    |         0.805 |         0.794 |
| Median Median seeingEff WFD u band HealpixSlicer    |         0.945 |         0.92  |
| Median Median seeingEff WFD r band HealpixSlicer    |         0.854 |         0.86  |
| Median Median seeingEff WFD z band HealpixSlicer    |         0.811 |         0.811 |
| Median Median seeingEff WFD all bands HealpixSlicer |         0.836 |         0.833 |

# Skymap comparisons
- [Nvisits all bands](figures/pontus_2565_kraken_2026_NVisits_all_bands_HEAL_ComboSkyMap.pdf)
![png](figures/thumb.pontus_2565_kraken_2026_NVisits_all_bands_HEAL_ComboSkyMap.png)
- [Nvisits alt/az all bands](figures/pontus_2565_kraken_2026_Nvisits_as_function_of_Alt_Az_all_bands_HEAL_ComboSkyMap.pdf)
![png](figures/thumb.pontus_2565_kraken_2026_Nvisits_as_function_of_Alt_Az_all_bands_HEAL_ComboSkyMap.png)
- [Median airmass all bands](figures/pontus_2565_kraken_2026_Median_airmass_all_bands_HEAL_ComboSkyMap.pdf)
![png](figures/thumb.pontus_2565_kraken_2026_Median_airmass_all_bands_HEAL_ComboSkyMap.png)
- [Max airmass all bands](figures/pontus_2565_kraken_2026_Max_airmass_all_bands_HEAL_ComboSkyMap.pdf)
![png](figures/thumb.pontus_2565_kraken_2026_Max_airmass_all_bands_HEAL_ComboSkyMap.png)
- [CoaddM5 r band](figures/pontus_2565_kraken_2026_CoaddM5_r_band_HEAL_ComboSkyMap.pdf)
![png](figures/thumb.pontus_2565_kraken_2026_CoaddM5_r_band_HEAL_ComboSkyMap.png)
- [Normalized Proper Motion at 20.5](figures/pontus_2565_kraken_2026_Normalized_Proper_Motion_@_20_5_All_visits_HEAL_ComboSkyMap.pdf)
![png](figures/thumb.pontus_2565_kraken_2026_Normalized_Proper_Motion_@_20_5_All_visits_HEAL_ComboSkyMap.png)
- [Normalized Parallax at 22.4](figures/pontus_2565_kraken_2026_Normalized_Parallax_@_22_4_All_visits_HEAL_ComboSkyMap.pdf)
![png](figures/thumb.pontus_2565_kraken_2026_Normalized_Parallax_@_22_4_All_visits_HEAL_ComboSkyMap.png)
# Histogram comparisons
### CoaddM5 r band HealPix Histogram
![png](figures/thumb.pontus_2565_kraken_2026_CoaddM5_r_band_HEAL_ComboHistogram.png)
### Slew Distance Histogram
![png](figures/thumb.pontus_2565_kraken_2026_Slew_Distance_Histogram_All_visits_ONED_ComboBinnedData.png)
### Zoom Slew Distance Histogram
![png](figures/thumb.pontus_2565_kraken_2026_Zoom_Slew_Distance_Histogram_All_visits_ONED_ComboBinnedData.png)
### Slew Time Histogram
![png](figures/thumb.pontus_2565_kraken_2026_Slew_Time_Histogram_All_visits_ONED_ComboBinnedData.png)
### Zoom Slew Time Histogram 
![png](figures/thumb.pontus_2565_kraken_2026_Zoom_Slew_Time_Histogram_All_visits_ONED_ComboBinnedData.png)
