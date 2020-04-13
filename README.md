# eht-dmc
A radio interferometric modeling tool developed for the Event Horizon Telescope (EHT).  The framework employed here utilizes PyMC3 for sampling and the eht-imaging library for VLBI data manipulation.

NOTE: Currently still in testing mode, so no guarantees that code will work at all yet.

### Installation instructions
To install the most recent version, clone the repository, move into the main directory, and install using `pip`:

```
git clone https://github.com/dpesce/eht-dmc.git
cd eht-dmc
pip install .
```

### Recommendations
Import the `eht-dmc` library using the `dm` alias:

```
import eht_dmc as dm
```
