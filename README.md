# GOV_UK_Colours

This package creates options for using diffent colours within the [GOV.UK pallette](https://design-system.service.gov.uk/styles/colour/)

## Table of Contents

- [Background](#background)
- [Install](#install)
- [Usage](#usage)
- [License](#license)

## Background

This package centralises the location for GovUKColours in order that it can be used in all Government dashboards. 

## Install

For installation using pip:

```sh
pip install git+https://github.com/communitiesuk/Plotly_utilities.git
```

For installation using conda, paste the following code into the environment configuration file:

```yml
 - pip:
     - git+https://github.com/communitiesuk/Plotly_utilities.git
```


## Usage

In order to access the colours in the package, use the command:

```python
from GOV_UK_Colours.colours import GovUKColors

GovUKColors.DLUHC_BLUE.value
```

## License

[MIT](LICENSE) Copyright (c) 2022 Crown Copyright (Department for Levelling Up, Housing and Communities)