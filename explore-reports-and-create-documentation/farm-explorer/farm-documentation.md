---
title: Create Farm Documentation
description: This article describes how to produce SharePoint farm documentation using SPDocKit.
Author: Iva Novoselic
date: 17/5/2017.
---

## Generate Documentation
This section describes how you can generate SharePoint farm documentation using SPDocKit.

1. Use the __Take Snapshot__ button to load local SharePoint farm settings, or choose to Open existing farm snapshot. You can view all of your snapshots if you navigate to the __Backstage Actions Screen__ and click the __View Snapshots__ button or if you go directly to the Snapshots tab.

1. Click __Generate__ from the left-side navigation pane and select the format in which you wish to create your farm documentation. The available formats are __.doc, .pdf and .xlsx__.

1. The farm settings you want to export can be selected from the drop-down options.

    The selection you make can be saved and used as a template for generating documentation in the future. SPDocKit comes with predefined documentation templates, with commonly used options already pre-selected. 

   The documentation templates available by default are: __All, Full Documentation (Without Site Explorer) Regular Documentation or Simple Documentation.__ Use the Up and Down arrows to rearrange the order of your documentation.

   There is a possibility that there will be a large amount of data contained in Site Explorer reports, so we added a template called __Full Documentation without Site Explorer__. If you want to export all Site Explorer information, please note that the active snapshot will need to be saved in the SPDocKit database.

1. The __Document Outline__ tab displays how the table of contents of your document will look.

1.  With the Options tab you can choose whether [Passwords and Product Keys](#internal/get-to-know-spdockit/farm-explorer-screen/passwords-and-product-keys)  will be displayed in the generated document. If these were not defined, the check box will be disabled.

1. Click the __Generate__ button, wait a few moments and your SharePoint farm documentation will be generated!


##  Customize Documentation Template
### Quick guide

To prepare a template for your documentation, you need to prepare a Word document template and customize Word styles. SPDocKit uses Word styles to generate customized output to match your corporate branding.

1. Create a custom Word document template (.dotx). Use your existing template or download our [sample documentation template.](https://www.spdockit.com/wp-content/uploads/2015/08/SharePoint-Farm-Documentation-Template.dotx) 

   We recommend you use the __Medium Shading 1 – Accent 1__ table style with this template. Customize the following styles to match your corporate branding: Heading1, Heading2, Heading3, Heading4, Normal and Hyperlink (you can make any changes required as long as these changes are performed over the style itself).

1.  Customize the table styles to match your branding.
1.  Customize headers and footers to add your company name, page numbers, etc.
1.  Customize the front page.
1.  Remove extra content except for the custom front page (or first few pages) that you wish to be included in every document.
1.  Start SPDocKit.
1.  In the Home ribbon, click __Change Styles__.
1.  Select __Upload a Custom Template__. Click Next to continue.
1.  Browse your Word template (.dotx) and choose the table style you want to use when generating tables (we recommend you use __Medium Shading 1 – Accent 1__ with [our template](https://www.spdockit.com/wp-content/uploads/2015/08/SharePoint-Farm-Documentation-Template.dotx)).
1. Click Finish to save.

### Customizing styles

SPDocKit uses the following default Word styles to generate documentation:
* __Heading1, Heading2, Heading3 and Heading4__ – used to generate section headings.
* __Normal__ – used to generate paragraph text.
* __Hyperlink__ – used for hyperlinks.

SPDocKit styles need to be customized to match your corporate or other desired branding. To modify a Style in Microsoft Word do the following:

1. From the __Styles__ ribbon right-click the style you want to customize.

1. From the context menu choose __Modify__.

1. A new dialog will open. Use it to make the desired changes (font, size, etc.)

You can read more about [style basics in Word here.](https://support.office.com/en-nz/article/Style-basics-in-Word-d382f84d-5c38-4444-98a5-9cbb6ede1ba4)

### Customizing Table Styles

To brand tables used in SharePoint farm documentation, you need to customize one of the built-in table styles. We currently support these styles:
* Table Grid
* Light Shading
* Light Shading – Accent 1
* Light Shading – Accent 3
* Light Shading – Accent 4
* Light Shading – Accent 5
* Medium Shading 1 – Accent 1
* Medium Shading 1 – Accent 4
* Medium Shading 1 – Accent 5
* Light Grid – Accent 6
* Medium Grid 1 – Accent 4
* Medium Grid 1 – Accent 5
* Medium List 2 – Accent 1
* Medium Grid 2 – Accent 2
* Medium Grid 2 – Accent 3

To customize the table style do the following:

1. Insert a table into the template document. (the table will be removed in the last step)

1. From the __Table Tools__ contextual ribbon, expand __Table Styles__.

1. Right-click the style you want to change and choose __Modify Table Style__.

1. Make the changes to the table style to match your desired branding. Pay special attention to the formatting of the whole table, header row, odd and even banded rows.

1. Remove the table you inserted in step 1.