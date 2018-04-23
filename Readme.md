# How to stretch the detail area to fill the entire page


<p>The following example demonstrates how to calculate the height of a usable page area without a page header and a page footer. This might be required to specify the size of a detail area, which fills the entire page.</p>


<h3>Description</h3>

<p>For this, it is necessary to implement a converter class that subtracts the height of a page header and footer from the entire usable page height. Then, this converter should be used in a <strong>DataTemplate</strong> for a detail area.</p>

<br/>


