# resonator_tools

A small python library to fit complex resonator scattering data.
It supports transmission, reflection and notch-type measurements.

For installation of the module execute:
python setup.py install

Description of the algorithm:
http://scitation.aip.org/content/aip/journal/rsi/86/2/10.1063/1.4907935

Where is it used?
The "resonator_tools" have contributed to the following publications:
https://scholar.google.de/scholar?oi=bibs&hl=de&cites=690000812747125148&as_sdt=5

Questions? Contact the author:
https://www.phi.kit.edu/ustinov_downloads.php

## SeeQC Fork

This fork updates the dependencies to ensure compatibility with latest python and package releases. The specific dependency version requirements are for compatibility with the SeeQC control software control-core project.

The project version is changed to adhere to semantic versioning.

This package can installed using poetry as `poetry install`, or with pip as `pip install .`, or built as a package using `poetry build` and choosing the appropriate package in the `./dist/` directory.
