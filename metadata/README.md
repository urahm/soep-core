# Metadata

## Publications

View schema with [DataPackage Viewer](https://data.okfn.org/tools/view?url=https%3A%2F%2Fraw.githubusercontent.com%2Fpaneldata%2Fsoep-core%2Fdata-validation%2Fmetadata%2Fdatapackage.json)

| CSV-Column / SQL-Field | Type | Required | Max length |
| ------ | ---- | -------- | ---------- |
| name   | char | x | 255 |
| sub_type   | char |  | 255 |
| title   | char | DESIRED |  |
| author   | text |  |  |
| year   | text |  |  |
| abstract   | text |  |  |
| cite   | text |  |  |
| url   | text |  |  |
| doi   | text |  |  |
| studies   | text |  |  |

study: foreign key

Sources:
-   [Model definition in ddionrails](https://github.com/ddionrails/ddionrails/blob/master/publications/models.py#L12)
-   <https://git.soep.de/ddionrails/ddionrails-datamodel/blob/master/docs/input/publication.rst>
-   <https://git.soep.de/ddionrails/ddionrails-datamodel/blob/master/docs/output/publication.rst>
-   <https://git.soep.de/ddionrails/ddionrails-datamodel/blob/master/docs/sql/publication.rst>
-   <https://git.soep.de/ddionrails/ddionrails-datamodel/blob/master/docs/elastic/publication.rst>
