# Air Quality Sandbox: Philadelphia

An interactive teaching tool for Drexel University's ENVE 460/560 Air Pollution Control course.
Students place emission sources on a map of the Philadelphia area and see ground-level and
vertical concentration fields respond for five weather hours from 2024.

**Open the app:** https://scapps.github.io/aq-design-phl/

This repository holds only the built, static site. Concentration fields are precomputed with
EPA's AERMOD dispersion model (version 24142) at a unit emission rate and summed in the browser,
which is valid for conserved primary pollutants; the app's "Model limits" layer and About tab
describe the assumptions and limitations.

Data credits: road geometry © OpenStreetMap contributors (ODbL); meteorology from NOAA NCEI ISD
and IGRA; background concentrations from EPA AirData; traffic counts from PennDOT and NJDOT.
