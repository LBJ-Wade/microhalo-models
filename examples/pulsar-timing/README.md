# Example: probing early matter domination using pulsar timing

This code requires numba in addition to numpy and scipy.

1. Begin with the EMD power spectrum power_32_20.txt (for the scenario with T_RH=32 MeV and k_cut/k_RH=20).
2. halos.py uses the halo_formation module to generate a halo list in halos_32_20.txt.
3. suppression.py applies tidal suppression and stellar encounters to produce the final halo list suppressed_halos_32_20.txt.
4. PTA_form_factor.py computes the "form factor" for pulsar timing calculations that is associated with the postencounter halo density profile.
