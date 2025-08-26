# Vaccination coverage

## Contents

This repository contains data extracted from the Italian Minister of Health bulletins. 





## Getting the data

**Direct download (CSV)**: [https://raw.githubusercontent.com/fbranda/vaccines-open-data/main/Report_ISS/Efficacia_vaccinale/report_iss_efficacia_vaccini.csv](https://raw.githubusercontent.com/fbranda/vaccines-open-data/main/report_iss_efficacia_vaccini.csv)  

**Python** (requires `pandas`):
```python
import pandas as pd
df = pd.read_csv("https://raw.githubusercontent.com/fbranda/vaccines-open-data/main/report_iss_efficacia_vaccini.csv")
```

**R** (requires `httr`):
```r
library(httr)
df <- read.csv(text=content(GET("https://raw.githubusercontent.com/fbranda/vaccines-open-data/main/report_iss_efficacia_vaccini.csv")))
```

## Contributions

1. [Branda F. Impact of the additional/booster dose of COVID-19 vaccine against severe disease during the epidemic phase characterized by the predominance of the Omicron variant in Italy, November 2021-March 2022. medRxiv. 2022 Jan 1](https://www.medrxiv.org/content/10.1101/2022.04.21.22273567v3)


## License and attribution

This repository and data exports are published under the CC BY 4.0 license.

If you use this file, please cite it as described in *CITATION.cff* file.



