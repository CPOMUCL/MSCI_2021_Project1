# MSCI_2021_Project1
Optimal interpolation of sea surface elevation in polar oceans

Goal: apply a Gaussian Process methodology already implemented for sea ice freeboard optimal interpolation to sea level data from the same satellites to retrieve daily gridded sea surface height anomaly and sea surface elevations at 50 km (or higher resolution)

Data: satellite elevation data from radar altimeters (CryoSat-2, Sentinel3A, Sentinel3B, AltiKa) and optionally laser altimeter (ICESat-2). 

Tool: the Gaussian Process optimal interpolation python code developed by William Gregory as part of his paper https://tc.copernicus.org/articles/15/2857/2021/tc-15-2857-2021.html

Github link: https://github.com/William-gregory/OptimalInterpolation

Bibliography: 

- Gregory, William, Isobel R. Lawrence, and Michel Tsamados. "A Bayesian approach towards daily pan-Arctic sea ice freeboard estimates from combined CryoSat-2 and Sentinel-3 satellite observations." The Cryosphere Discussions (2021): 1-22.
- Lawrence, Isobel, et al. "A merged CryoSat-2 Sentinel-3 freeboard product, its sensitivity to weather events, and what it can tell us about Ku-band radar penetration." EGU General Assembly Conference Abstracts. 2020.
- Ricker, Robert, et al. "A weekly Arctic sea-ice thickness data record from merged CryoSat-2 and SMOS satellite data." The Cryosphere 11.4 (2017): 1607-1623.
- Many other previous studies have reported statistical interpolation methods under a variety of names, e.g. Gaussian process
regression (Paciorek and Schervish, 2005; Rasmussen and Williams, 2006), kriging (Cressie and Johannesson, 2008; Kang et al., 2010; Kostopoulou, 2020), objective analysis (Le Traon et al., 1997)
