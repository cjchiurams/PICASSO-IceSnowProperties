# PICASSO-IceSnowProperties
Retrievals presented in 

Kedzuf, N.J., Chiu, J.C., Chandrasekar, V., Biswas, S., Joshil, S.S., Lu, Y., van Leeuwen, P.J., Westbrook, C., Blanchard, Y. and O'Shea, S, 2021: Retrieving microphysical properties of concurrent pristine ice and snow using polarimetric radar observations, Atmos. Meas. Tech., 14, 1–20, 2021, https://doi.org/10.5194/amt-14-1-2021

Format: npz file; you can use np.load to read the output

====================================================

All variables comprise 6 values corresponding to different data cluster

CLUSTER_TIMES = time of data clusters

NT_hvps_ENCORE= ENCORE-retrieved total ice number concentration (consistent with hvps size bins)

NT_RYZK       = emprically-derived total ice number concentration from Murphy et al. (2020)

IWC_ENCORE    = ENCORE-retrieved total ice water content

IWC_RYZK      = emprically-derived total ice water content from Murphy et al. (2020)

DM_ENCORE     = ENCORE-retrieved mean effective diameter using maximum particle dimension as the size descriptor (mm)

DM_RYZK       = emprically-derived mean effective diameter using equivalent volume diameter as the size descriptor (mm)

DM_MELT_RYZK  = emprically-derived mean effective diameter using equivalent melted diameter as the size descriptor (mm)

DM_A_ENCORE   = ENCORE-retrieved mean effective diameter for snow aggregates, using maximum particle dimension as the size descriptor (mm)

DM_P_ENCORE   = ENCORE-retrieved mean effective diameter for pristine ice, using maximum particle dimension as the size descriptor (mm)

DM_A_MELTED_ENCORE = ENCORE-retrieved mean effective diameter for snow aggregates, using equivalent melted diameter as the size descriptor (mm)

DM_P_MELTED_ENCORE = ENCORE-retrieved mean effective diameter for pristine ice, using equivalent melted diameter as the size descriptor (mm)
