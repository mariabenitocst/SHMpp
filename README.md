# SHMpp
Halo integrals for SHM++ halo model.

SHMpp_gvmin.py outputs tables of vmin [km/s] and g(vmin) [s/km].

Three data files are produced:
gvmin_round.dat, gvmin_sausage.dat and gvmin_SHMpp.dat
The file gvmin_round.dat gives g(vmin) from the round component of the halo.
The file gvmin_sausage.dat gives g(vmin) from the sausage component of the halo.
The file gvmin_SHMpp.dat gives g(vmin) for the SHM++ with eta=0.2.


SHMpp_hvmin.py outputs a table of vmin [km/s] and h(vmin) [km/s].

Three data files are produced:
hvmin_round.dat, hvmin_sausage.dat and hvmin_SHMpp.dat
The file hvmin_round.dat gives h(vmin) from the round component of the halo.
The file hvmin_sausage.dat gives h(vmin) from the sausage component of the halo.
The file hvmin_SHMpp.dat gives h(vmin) for the SHM++ with eta=0.2.

The code is fairly self-explantatory.
Between v1 and v2 (which matched the PRD version) of the paper, we updated vesc to the newer value (528 km/s) from Deason et al (arXiv:1901.02016).
The codes have been updated (Feb. 2019) to include this new value for vesc.
For queries, email christopher.mccabe@kcl.ac.uk.
