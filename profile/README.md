Official GitHub organization of the [COAT](https://coat.no/) project.

<details>
<summary>🗃️ Datacatalog</summary>

The datacatalog is available at [data.coat.no](https//data.coat.no).
The user documentation is available at [coatnor.github.io](https://coatnor.github.io).

It is made of different components:
  
- 🌟 [datacatalog](https://github.com/COATnor/datacatalog): main code repository (based on [CKAN](https://ckan.org/))
- 📖 [coatnor.github.io](https://github.com/COATnor/coatnor.github.io): user documentation
- ⚙️ Datacatalog custom extensions
  - [ckanext-coat](https://github.com/COATnor/ckanext-coat): extension containing custom logic, such embargo and versioning
  - [ckanext-coatcustom](https://github.com/COATnor/ckanext-coatcustom): extention containing schemas and presets
  - [ckanext-scheming](https://github.com/COATnor/ckanext-scheming): fork of [ckan/ckanext-scheming](https://github.com/ckan/ckanext-scheming) containing a fix for https://github.com/ckan/ckanext-scheming/issues/387
  - [ckanext-oauth2](https://github.com/COATnor/ckanext-oauth2): fork of [conwetlab/ckanext-oauth2](https://github.com/conwetlab/ckanext-oauth2) containing fixes for Python 3 and compatibility for [Feide](https://www.feide.no/)
- 🧰 Additional components
  - [ckan](https://github.com/COATnor/ckan): base Docker images
  - [coat2pycsw](https://github.com/COATnor/coat2pycsw): compatibility layer for [SIOS](https://github.com/SIOS-Svalbard)
  - [coat-bulk-download](https://github.com/COATnor/coat-bulk-download): provide datasets as ZIP files on demand

</details>
