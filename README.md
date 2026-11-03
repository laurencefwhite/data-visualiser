# Data Visualiser

Live: https://laurencefwhite.github.io/data-visualiser/

This repository holds the published site only.

## Data and credits

Data are reshaped (selected and put in a table with a column for each year) but not otherwise changed. Each sample
is credited in the line under the file name and in the legend, and in the app under "Sources and licences".

- Country boundaries: Natural Earth, admin-0 countries at 1:50 million (Gibraltar and the US Minor Outlying
  Islands at 1:10 million), public domain (https://www.naturalearthdata.com/about/terms-of-use/). Boundaries are
  de facto, as Natural Earth draws them. The 2019 sample is Natural Earth's own attributes (2019 population and GDP
  estimates, income groups).
- Our World in Data, CC BY 4.0 (https://ourworldindata.org/faqs): population by country and year, from HYDE
  (2023), Gapminder (2022) and the UN World Population Prospects (2024), with the UN medium projections from 2024 to
  2100; and the samples over time, as processed by Our World in Data: CO₂, Global Carbon Budget (2025); life
  expectancy, Riley (2005), Zijdeman et al. (2015), Human Mortality Database (2025) and UN WPP (2024); children per
  woman, Human Fertility Database (2026) and UN WPP (2024); GDP per person, access to electricity and income
  groups, World Bank (2026).
- The World Bank, CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/; https://datacatalog.worldbank.org/public-licenses):
  "The World Bank: World Development Indicators" (32 series, 03/11/2026, from https://api.worldbank.org/v2/) and
  "The World Bank: The Changing Wealth of Nations 2024" (World Bank Wealth Accounts, source 59). The series codes and
  underlying sources (UN, IMF, ILO, UNESCO, FAO, ITU, IEA, WHO, UNICEF, UNODC, EDGAR and others) are in the header of
  each `data\sample-wdi_*.js`. Military expenditure (SIPRI terms) is not bundled. Indicators fetched through the search
  box are not part of this site; each is shown with its own licence from the World Bank's metadata
  (`data\wdi-licences.js`, checked 03/11/2026).
- UNDP, Human Development Report 2025, Human Development Index, CC BY 3.0 IGO
  (https://hdr.undp.org/copyright-and-terms-use), via Our World in Data; reshaped here.
- V-Dem (electoral democracy index and political regime), CC BY-SA 4.0
  (https://creativecommons.org/licenses/by-sa/4.0/). Coppedge, Michael, John Gerring, Carl Henrik Knutsen, Staffan I.
  Lindberg, Jan Teorell, David Altman and others (2026). "V-Dem Country-Year Dataset v16". Varieties of Democracy
  (V-Dem) Project. https://doi.org/10.23696/vdemds26 (https://v-dem.net/data/the-v-dem-dataset/), via Our World in
  Data. The regime classification is Regimes of the World: Lührmann, Anna, Marcus Tannenberg and Staffan I. Lindberg
  (2018), "Regimes of the World (RoW): Opening New Avenues for the Comparative Study of Political Regimes", Politics
  and Governance 6(1): 60–77, https://doi.org/10.17645/pag.v6i1.1214. The two V-Dem files here
  (`data\sample-electdem.js`, `data\sample-regime.js`) are adapted from V-Dem's (a subset, reshaped to a table) and are
  offered under CC BY-SA 4.0; the rest of this site is not covered by that licence.
- Colour schemes after ColorBrewer (Cynthia Brewer, Apache 2.0), viridis and magma (CC0) and Tableau 10.
- SheetJS Community Edition (Apache 2.0), d3 (ISC) and topojson-client (BSD).

## Copyright

Code, page and design © 2026 Laurence F. White. All rights reserved. The data and artwork credited above keep their own licences.
