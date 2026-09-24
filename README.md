# mparam
Unifying set of files and protocol to parametrize AMBER metal-ligand force fields, using QM software outside of those currently supported by the MCPB.py protocol.

QM Softwares include:

- TURBOMOLE (tested on 7.6/7.7)
- Orca (tested on 6.0/6.0.1/6.1)
- PySCF (in-progress)

Also included is a parametrization protocol using the "big-QM" approach within MCPB.py, where a larger QM subsystem may allow for more accurate force field descriptions

For the examples shown, these are verified against Gaussian (version 16) parameters, which is the typical AMBER protocol.
