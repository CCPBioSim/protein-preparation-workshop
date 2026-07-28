# CCPBioSim Protein Preparation Workshop

This workshop walks through the process of preparing a simple protein + ligand system for molecular dynamics simulation:

1. Using tools like *Alphafold3* and *Boltz2* to generate models for the protein/ligand complex.
2. Adding hydrogen atoms to the models - fixing the ionization states of titratable groups.
3. Creating a solvent environment - adding ions and water boxes.
4. Conversion into file formats ready for MD simulation packages.

## How to Use

This training course is deployed on the [CCPBioSim](www.ccpbiosim.ac.uk) website via our cloud infrastructure, however you can deploy on your own machine with docker.

Pull the container from our repository::

    docker pull ghcr.io/ccpbiosim/protein-preparation-workshop:latest

In our containers we are using the JupyterHub default port 8888, so you should
forward this port when deploying locally::

    docker run -p 8888:8888 ghcr.io/ccpbiosim/protein-preparation-workshop:latest

## Authors

Workshop Content Authors:

- Charlie Laughton
- Hima Bindu Koli
- Jas Kalayan

## Contact

Please direct all questions and feedback to [Charlie Laughton](mailto:charles.laughton@nottingham.ac.uk)

