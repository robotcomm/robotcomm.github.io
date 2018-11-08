The tender bits of docuement content controls and metadata.

The following bits of information are dynamically linked between SharePoint and Process Docs (docx):


DISPLAYED IN DOC
* PCF ID - shows in the upper-right of the document / controlled in SP metadata manager for site collection
* Document Type (proc, narr, instruction, etc.) - shows in the upper-right also / controlled in SP lib column type 'choice' 
* Subject - used to control default groupings in doc lib., also upper-right / controlled in SP lib column type 'choice'
* Title - the 'Title of the document' (e.g., Using X to do Y) / free to choose at doc level
* Subtitle - optional, shown directly below Title / free to choose at doc level
* File name - shown in doc footer (e.g., CER-PROC-012.docx)

NOT DSPLAYED IN DOC (DOCUMENT ATTRIBUTES ONLY)
* PCF Hierarchy / controlled in SP metadata manager for site collection
* PCF Level / controlled in SP metadata manager for site collection
* Enterprise Keywords / open selection @ farm metadata mananger

The following bits of information are automatically updated with the document, but not linked to SP.

* Last Updated - header disp. only. Updates on save (close and open to see refreshed data). If it does not refresh, close > re-open > right-click field and select 'update field'
