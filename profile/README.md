# Official GitHub organization of the Climate-ecological Observatory of Arctic Tundra ([COAT](https://coat.no/)).

<details>
<summary>🗃️ Datacatalog</summary>

The datacatalog is available at [data.coat.no](https//data.coat.no).

Here is an overview of all the public repositories that are part of the datacatalog:

- 🌟 [datacatalog](https://github.com/COATnor/datacatalog): main code repository (based on [CKAN](https://ckan.org/))
- 📖 [coatnor.github.io](https://github.com/COATnor/coatnor.github.io): user documentation hosted at [coatnor.github.io](https://coatnor.github.io)
- ⚙️ Datacatalog custom extensions
  - [ckanext-coat](https://github.com/COATnor/ckanext-coat): extension containing custom logic, such embargo and versioning
  - [ckanext-coatcustom](https://github.com/COATnor/ckanext-coatcustom): extention containing schemas and presets
  - [ckanext-scheming](https://github.com/COATnor/ckanext-scheming): fork of [ckan/ckanext-scheming](https://github.com/ckan/ckanext-scheming) containing a fix for https://github.com/ckan/ckanext-scheming/issues/387
  - [ckanext-oauth2](https://github.com/COATnor/ckanext-oauth2): fork of [conwetlab/ckanext-oauth2](https://github.com/conwetlab/ckanext-oauth2) containing fixes for Python 3 and compatibility for [Feide](https://www.feide.no/)
- 🧰 Additional components
  - [ckan](https://github.com/COATnor/ckan): base Docker images
  - [coat2pycsw](https://github.com/COATnor/coat2pycsw): compatibility layer for [SIOS](https://github.com/SIOS-Svalbard)

</details>

<details>
<summary>🧰 COAT Data Portal example scripts</summary>

The following repository contains examples demonstrating how to create, upload,
and download datasets and state variables to the COAT Data Portal.

- [coat_data_portal_example_scripts](https://github.com/COATnor/coat_data_portal_example_scripts)

</details>

<details>
<summary>📦 Module-specific scripts</summary>

The following repositories contain scripts associated with specific COAT
monitoring modules.

### 🌡️ Climate module

The Climate module contains scripts for calculating COAT climate-related state
variables.

- [State-variable scripts](https://github.com/COATnor/climate_module/tree/main/state_variable_scripts)

### 🦌 Svalbard ungulate module

The Svalbard ungulate module contains scripts for calculating state variables
related to ungulate populations and their dynamics.

- [State-variable scripts](https://github.com/COATnor/ungulate_module_svalbard/tree/main/state_variables)

### 🐭 Small rodent module

The Small rodent module contains scripts for calculating COAT state variables
related to small rodent populations.

- [State-variable scripts](https://github.com/COATnor/small_rodent_module/tree/main/state_variable_scripts)

### 🦊 Arctic fox module

The Arctic fox module contains an integrated population model (IPM) for the
Svalbard Arctic fox population.

- [Svalbard Arctic fox integrated population model](https://github.com/COATnor/S_arcticfox_IPM)

</details>

<details>
<summary> 📊 Maps and graphics</summary>

The R Shiny apps are available at [apps.coat.no](https://apps.coat.no).

The source code is available in the
[apps repository](https://github.com/COATnor/apps).

- 🗺️🦊 [Red fox tracks](https://apps.coat.no/red_fox_tracks/)
- 📈🐭 [Small rodents abundance](https://apps.coat.no/small_rodents_abundance/)

</details>
