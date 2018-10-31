# ThingWorx Navigate  

ThingWorx Navigate enables users to quickly and easily access specific Windchill information from approved devices that support a Web browser.

#### System and License Requirements

* PC running X or higher
* Internet Explorer version x or higher
* Chrome emulation extension for IE [(installation instructions)][1]
* License X or X - obtain from [IT self-service][2]

#### Partial and Exact Match Search

Partial matching uses 'wildcard' characters to allow users to find multiple Windchill resources that share a common name or 'root' (example, a 'base' part number). The wildcard character, an asterisk, may be placed at the beginning, middle, or end of a search string.

    Leading (*1234) matches resources with a name ending in '1234'
    Trailing (1234*) matches resources with a name beginning with '1234'
    Middle (12*34) matches resources with a name that begins with '12' and ends with '34'

The most effective strategy when the base part / assembly number is known is to combine leading and trailing wildcards (example, '*1234*') 


## View Design Files  

Use the search function to retrieve ASM and PRT files. To ensure you are returning a result set that contains all applicable files, enter the base part or assembly number with an asterisk before and after the search term.

    
    EXAMPLE: *part_1234*
    

The asterisk is a 'wildcard' character, which means that any search will match any records that contain the supplied search term.


## View Drawing  

Use the search function to retrieve PDF renderings of CAD files. As with *View Design Files* use wildcard characters to ensure your search results contain all possible applicable results.
    
    
    EXAMPLE IMAGE GOES HERE
    

You may search for a component, or parent part / assembly.

 
## View & Measure in 3D

**View & Measure in 3D** launches [Creo View Lite][3] in a new browser window. Using the Creo View Lite application, users can view and manipulate the 3D representation of the model. This does not make changes to the original.   

    
### Example users of the Creo View Lite application:
    
| Role | Description |
|:---- |:----------- |  
| Reliability Engineer | view and manipulate the 3D representation using Creo View to show wetted parts. Screenshot exploded view and annotate for listing packet. |
| Customer Quality (CQI) / Call Center | view / rotate / explode product as needed when troubleshooting with customer. |
| Compliance | with Reliability review 3D viewables for 'claims of similarity'.  |
| Technical Literature team | retrieve viewables for use in constructing tech lit (some will still be pulled from SAP). |
  

### How-to  

1. Click **View & Measure** > **Lifecycle state**.
1. Choose **Released** from the dropdown list.
1. Type search term with wildcards into the *Search field*.
1. Press <kbd>ENTER</kbd>
1. Click the **Start button**.
1. Click the **checkbox** to choose an asset.
1. Viewable loads and geometry appears in the graphics window.

*You now have access to all Creo View Lite functions.*


## View Part Properties

The **View Part Properties** task displays the CAD document and parametric attribtutes. 


## View Parts List  

The **View Part Structure** task displays the CAD document, parametric attributes, and the parts list (BOM) in tabular form. Each row in the table contains the part parametric data, and a link to CAD data and / or PDF viewable(s).  

To review the parts list in Excel, click the **Export All** button.


## View Part Structure

The **View Part Structure** task displays the parts list (BOM) in a hierarchical view. The relationship between parts / assemblies and related parents or children is represented by indentation.

### How-to

1. Click **View Part Structure** > **Lifecycle state**.
1. Choose **Released** from the dropdown list.
1. Type search term with wildcards into the *Search field*.
1. Press <kbd>ENTER</kbd>
1. Review attribute information and thumbnail image in **Part Details** section.
1. Scroll to **Part Structure** to review assembly hierarchy.
1. In **Part Structure** table, click assembly title (ex., 1244_chr.asm) select it.
1. Assembly appears in **Selected Part** section.
1. Click the file name in **Selected Part** to filter **Part Structure**.
1. Click **View Design Files** to show 3D CAD assembly.
1. If prompted, click **OK** to open the viewable in Adobe Reader.
 

## View Document

The **View Document** task displays the document thumbnail along with the document attributes. There are two important functions:

* **View in Windchill** - Open the document information page in Windchill
* **Open** - Open the document in PDF viewer

### How-to  

1. Click **View document** > **Lifecycle state**.
1. Choose **In Work** from the dropdown list.
1. Type search term with wildcards into the **Search field**.
1. Press <kbd>ENTER</kbf>
1. Click the thumbnail image.
1. Click **OK** to open the document in PDF viewer.


## View Document Structure  

## Download Drawing Bundle  

## View Requirements



[1]: http://www.google.com
[2]: http://www.google.com
[3]: http://www.google.com


