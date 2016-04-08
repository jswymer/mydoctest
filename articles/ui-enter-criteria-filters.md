<properties
	pageTitle="Entering Criteria in Filters | Project “Madeira”"
        description="Welcome to Project "Madeira""
        services=""
        documentationCenter="Madeira"
        authors="edupont04"/>

# Entering Criteria in Filters
When you enter criteria, you can use all the numbers and letters that you can normally use in the field. In addition, you can use special symbols to further filter the results. Later in this topic, you can read more about the Quick Filter on pages.

## Symbols
The following tables show the symbols which can be used in filters in Project "Madeira".

**Important**: There may be instances where field values contain these symbols and you want to filter on them. To do this, you must include the filter expression that contains the symbol in quotation marks (''). For example, if you want to filter on records that start with the text S&R, the filter expression is 'S&R*'.  

### Interval
|Sample Expression|Records Displayed|
|-----------------|-----------------|
|1100..2100 |Numbers 1100 through 2100.|
|..2500 |Up to and including 2500.|
|..12 31 00|Dates up to and including 12 31 00.|
|P8..|Information for accounting period 8 and thereafter.|
|..23|From the beginning date until 23-current month-current year 23:59:59.|
|23..|From 23-current month-current year 0:00:00 until the end of time.|
|22..23|From 22-current month-current year 0:00:00 until 23-current month-current year 23:59:59.|

<!-- html syntax because symbols conflict with MarkDown syntax -->
### (|) Either/or
<TABLE>
  <TR>
    <TH>Sample Expression</TH>
    <TH>Records Displayed</TH>
  </TR>
  <TR>
    <TD>1200|1300</TD>
    <TD>Numbers with 1200 or 1300.</TD>
  </TR>
</TABLE>

### (<>) Not equal to
|Sample Expression|Records Displayed|
|-----------------|-----------------|
|<>0       |All numbers except 0. The SQL Server Option allows you to combine this symbol with a wild card expression. For example, <>A* meaning not equal to any text that starts with A.|

### (>) Greater than
|Sample Expression|Records Displayed|
|-----------------|-----------------|
|>1200|Numbers greater than 1200.|

### (>=) Greater than or equal to
|Sample Expression|Records Displayed|
|-----------------|-----------------|
|>=1200|Numbers greater than or equal to 1200.|

<!-- html syntax because symbols conflict with MarkDown syntax -->
### (<) Less than
<TABLE>
  <TR>
    <TH>Sample Expression</TH>
    <TH>Records Displayed</TH>
  </TR>
  <TR>
    <TD><1200</TD>
    <TD>Numbers less than 1200.</TD>
  </TR>
</TABLE>

### (<=) Less than or equal to
<TABLE>
  <TR>
    <TH>Sample Expression</TH>
    <TH>Records Displayed</TH>
  </TR>
  <TR>
    <TD><=1200</TD>
    <TD>Numbers less than or equal to 1200.</TD>
  </TR>
</TABLE>

### (&) And
<TABLE>
  <TR>
    <TH>Sample Expression</TH>
    <TH>Records Displayed</TH>
  </TR>
  <TR>
    <TD>>200&<1200</TD>
    <TD>Numbers greater than 200 and less than 1200.</TD>
  </TR>
</TABLE>

### ('') An exact character match
|Sample Expression|Records Displayed|
|-----------------|-----------------|
|'man'|Text that matches man exactly and is case sensitive.|

### (@) Case insensitive
|Sample Expression|Records Displayed|
|-----------------|-----------------|
|@man'|Text that starts with man and is case insensitive.|

<!-- html syntax because symbols conflict with MarkDown syntax -->
### (*) An indefinite number of unknown characters
<TABLE>
  <TR>
    <TH>Sample Expression</TH>
    <TH>Records Displayed</TH>
  </TR>
  <TR>
    <TD>>*Co*</TD>
    <TD>Text that contains "Co".</TD>
  </TR>
  <TR>
    <TD>>*Co</TD>
    <TD>Text that ends with "Co".</TD>
  </TR>
  <TR>
    <TD>>Co*</TD>
    <TD>Text that begins with "Co".</TD>
  </TR>
</TABLE>

### (?) One unknown character
|Sample Expression|Records Displayed|
|-----------------|-----------------|
|Hans?n|Text such as Hansen or Hanson.|

<!-- html syntax because symbols conflict with MarkDown syntax -->
### Combined format expressions
<TABLE>
  <TR>
    <TH>Sample Expression</TH>
    <TH>Records Displayed</TH>
  </TR>
  <TR>
    <TD>>5999|8100..8490</TD>
    <TD>Include any records with the number 5999 or a number from the interval 8100 through 8490.</TD>
  </TR>
  <TR>
    <TD>>..1299|1400..</TD>
    <TD>Include records with a number less than or equal to 1299 or a number equal to 1400 or greater (all numbers except 1300 through 1399).</TD>
  </TR>
  <TR>
    <TD>>>50&<100</TD>
    <TD>Include records with numbers that are greater than 50 and less than 100 (numbers 51 through 99).</TD>
  </TR>
</TABLE>

## Quick filter
You can add filters to all pages, either by using the Quick Filter or the Advanced Filter. The Quick Filter is enabled by entering criteria in the **Type to filter** box at the top of a page. This filtering type is used for a fast entry of criteria. The advanced filtering option is available when you click the expand button next to the Quick Filter or when you press F3. All filters are cleared by pressing Ctrl+Shift+A.

**Note**: In Project "Madeira" Tablet client and Project "Madeira" Phone client, you have a Search capability that works in the same way as Quick Filter.

**Important**: Filtering using the Quick Filter works a bit differently than using the Advanced Filter. The Quick Filter provides an easy access to filter data by entering plain text, but does also provide a lot of search criteria options. Depending on whether you enter plain text or text including symbols, the Quick Filter behaves differently.  
- If you enter plain text in the search criteria, the search criteria is interpreted as a case insensitive search that contains certain text.  
- If you enter text including symbols in the search criteria, the search criteria is interpreted exactly as you entered it, and the search is case sensitive

### Quick filter criteria
<!-- html syntax because symbols conflict with MarkDown syntax -->
<TABLE>
  <TR>
    <TH>Search Criteria</TH>
    <TH>Interpreted as...</TH>
    <TH>Returns...</TH>
  </TR>
  <TR>
    <TD>>man</TD>
    <TD>@*man*</TD>
    <TD>All records that contain the text man and case insensitive.</TD>
  </TR>
  <TR>
    <TD>>se</TD>
    <TD>@*se*</TD>
    <TD>All records that contain the text se and case insensitive.</TD>
  </TR>
  <TR>
    <TD>>Man*</TD>
    <TD>Starts with Man and case sensitive.</TD>
    <TD>All records that start with the text Man.</TD>
  </TR>
  <TR>
    <TD>'man'</TD>
    <TD>An exact text and case sensitive.</TD>
    <TD>All records that match man exactly.</TD>
  </TR>
  <TR>
    <TD>@*man</TD>
    <TD>Ends with and case insensitive.</TD>
    <TD>All records that end with man.</TD>
  </TR>
  <TR>
    <TD>@man*</TD>
    <TD>Starts with and case insensitive.</TD>
    <TD>All records that start with man.</TD>
  </TR>
</TABLE>

**Note**: You cannot use a wildcard when filtering on enumeration fields, such as the **Status** field on sales orders. To enter a filter for this type of field, you can enter the numeric value as a filtering parameter. For example, in the **Status** field on a sales order that has the values **Open**, **Released**, **Pending Approval**, and **Pending Prepayment**, use the values **0**, **1**, **2**, and **3** to filter for these options.  

## See Also
[Work with Project "Madeira"](ui-work-product.md)
