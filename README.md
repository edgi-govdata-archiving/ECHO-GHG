 [![Code of Conduct](https://img.shields.io/badge/%E2%9D%A4-code%20of%20conduct-blue.svg?style=flat)](https://github.com/edgi-govdata-archiving/overview/blob/main/CONDUCT.md)

# GHG emission by company
This repo hosts a Jupyter Notebook for analyzing greenhouse gas emissions reported to USEPA by corporate owner.

Under the US Environmental Protection Agency's Greenhouse Gas Reporting Program (GHGRP), a variety of emitters are required to count and report their emissions anually. 

Conceptually this is similar to reporting pollutant discharages under the Clean Water Act's National Pollutant Discharge Elimination System (NPDES), but whereas NPDES has legal teeth - facilities are permitted to release only so much of a pollutant into the water - there is no such equivalent legislation for greenhouse gases (GHGs).

Facilities reporting GHGs are also required to report information about ownership - the share a parent company has in the facility. Through this information we can determine not just which specific facilities reported the most GHGs every year, but which companies can be said to be the most responsible in terms of their ownership of these facilities.

The GHGRP does not attempt to account for all of the US's GHG emissions; the [GHG Inventory](https://www.epa.gov/ghgemissions/inventory-us-greenhouse-gas-emissions-and-sinks) does that. But GHGRP focuses on industrial direct emitters and some suppliers above certain thresholds. As EPA notes, "The GHGRP does not represent total U.S. GHG emissions, but provides facility level data for large sources of direct emissions, thus representing the majority of U.S. GHG emissions. The GHGRP data collected from direct emitters represent about half of all U.S. emissions." Including estimates from suppliers of fossil fuels, the GHGRP dataset [can account for](https://www.epa.gov/ghgreporting/learn-about-greenhouse-gas-reporting-program-ghgrp) up to 90% of all US emissions. 

As EPA [notes](https://ccdsupport.com/confluence/pages/viewpage.action?pageId=98598976), "Data from direct emitters and suppliers cannot be viewed together because it would cause double counting of emissions in many sectors.  In general, it is more accurate to look at upstream (also called suppliers) data separately from downstream (also called direct emitters) data." EPA [elaborates](https://ccdsupport.com/confluence/pages/viewpage.action?pageId=98598975) on the differences between direct emitters and suppliers:

> "Direct emitters" are facilities that combust fuels or otherwise put GHGs into the atmosphere directly from their facility.  An example of this is a power plant that burns coal or natural gas and emits carbon dioxide directly into the atmosphere...."Suppliers" are those entities that supply products into the economy which if combusted, released or oxidized emit greenhouse gases into the atmosphere.  These fuels and industrial gases are not emitted from the supplier facility but instead distributed throughout the country and used.  An example of this is gasoline, which is sold in the U.S. and primarily burned in cars throughout the country."

This notebook uses self-reported data from both emitters and suppliers to estimate GHG emissions by parent company. For further information about how the EPA's GHGRP works, please see our PowerPoint slides [here](https://docs.google.com/presentation/d/1EVtWOFDEeaqZhg1FTf0IsEL3M736hITP5G76q9l6bP0/edit?usp=sharing) or the EPA's website [here](https://www.epa.gov/ghgreporting). For a full FAQ, see EPA's [helpdesk](https://ccdsupport.com/confluence/display/faq/GHG+Data+and+Publication).


# How to start contributing to this repo
* Instructions go here!


---

## License & Copyright

Copyright (C) <year> Environmental Data and Governance Initiative (EDGI)
This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, version 3.0.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

See the [`LICENSE`](/LICENSE) file for details.
