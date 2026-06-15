The two output files requested are in `output_uvfits`.

This is a minimal repo to run the reference simulation 1.8_lunar from pyuvsim. The simulation is of 1 time, 1 frequency, and 128 antennas (8256 baselines). A text catalog is used with sources spelling `MOON`, and the MWA 128T antenna configuration is used as the layout.

All necessary data files to run reference simulation `1.8_lunar` are added. The reference simulation can be ran using:
`mpiexec run_pyuvsim --param test_config/obsparam_ref_1.8_lunar.yaml`
