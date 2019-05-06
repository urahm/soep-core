# Metadata

## Publications

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
