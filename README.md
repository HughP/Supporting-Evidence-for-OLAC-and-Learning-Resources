# Supporting Evidence for OLAC and Learning Resources

Templates and work supporting the conference presentation: Paterson III, Hugh J., Phil Barker &amp; Matthew R. Lee. 2022. Metadata for Language Learning Resources: Advancing OLAC for Language Development. Paper presented at the Language Documentation and Archiving Conference. Berlin-Brandenburgische Akademie der Wissenschaften, Berlin, Germany. October 5th–7th.

The crux of this work is to enable the [OLAC OAI-PMH aggregator](http://www.language-archives.org/OLAC/protocol.html) to recieve [LRMI metadata](https://www.dublincore.org/about/lrmi/) about lanugage resources. To this end several XML templates and XSD templates are included in this repo.

Two approaches can be taken. The first is to expand the OLAC namespace to include all LRMI concepts, the second is to include the LRMI xsd validation file in the OLAC header for inclusion in existing validation processes.

[OLAC framework extensions](http://www.language-archives.org/NOTE/third-party-extensions.html) are documented within the OLAC documentation. Specifically see §4,§5,§6. http://www.language-archives.org/OLAC/metadata.html and the previous in-text link.

Prior art by Hugh Paterson III on OLAC framework plugins includes the validating OLAC static repository here: https://hughandbecky.us/Becky-CV/olac/oai.xml

And its refeenced Zotero xsd here: https://hughandbecky.us/Becky-CV/schemas/zotero/zotero-items.xsd
