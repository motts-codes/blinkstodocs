# 🚀 Excel Bulk conversion

Excel bulk conversion operates similarly to the datagrid method. To access the Excel converter page, click on the 'Excel' submenu under 'Bulk Conversion'.

<figure><img src="../.gitbook/assets/Excel Sheet.jpg" alt=""><figcaption><p>Img 1 - Excel Bulk Converter</p></figcaption></figure>



Utilizing the Excel format provides additional field options for customization, with the number of URLs limited according to your plan. Follow these steps

1. **Download the Excel Template:** This template outlines the available fields for customization. The URL field is mandatory. Download the template below 👇🏻

{% file src="../.gitbook/assets/blinksto_excel_template.xlsx" %}
File 1 - Excel file template
{% endfile %}

<figure><img src="../.gitbook/assets/excel_format.svg" alt=""><figcaption><p>Img 2 - Fields provided in Excel template. Url is mandatory</p></figcaption></figure>

2. **Fill in and Upload:** Complete the required fields and upload the filled file using the drag-and-drop widget in the center. Click 'Upload,' and the progress bar will display the file upload progress and the conversion status of each URL. If the number of URLs is small, the process may be quick, and the progress bar might not be visible.
3. **Check Conversion Report:** After the conversion is complete, download an Excel file displaying the status of each URL (Success or Error). If errors occur, the nature of the error is indicated next to the status column."
4. **Fix Errors & Repeat:** If errors occur, exclude the URLs without errors, rectify the rows with issues, re-upload, and repeat the process.

### <mark style="color:purple;">Let's explore a simple example:</mark>

I've downloaded the Excel file and completed the fields as illustrated below.

<figure><img src="../.gitbook/assets/excel - filled in (1).jpg" alt=""><figcaption><p>Img 3 - Filled in excel template</p></figcaption></figure>

There are a total of 5 links to be converted:

* The first link has all fields filled in (alias, domain, title, and UTM parameters).
* The second link lacks UTM parameters.
* The third link is missing the domain (the preferred domain set will be used).
* The fourth link doesn't have the title filled in.
* The final link only has the URL.

{% hint style="info" %}
If you're utilizing UTM parameters, ensure the first three are filled in, as they are required fields for UTM (source, medium, and campaign). You can leave them empty if UTM is not needed, but when using UTM, all three are required to be filled in.
{% endhint %}

Next, I uploaded the file and clicked on 'upload.' Since there were no errors, the shortening was successful, and the conversion status Excel is available for download."

<figure><img src="../.gitbook/assets/Excel - converted without errors.jpg" alt=""><figcaption><p>Img 4 - Bulk conversion completed</p></figcaption></figure>

**Here is a snapshot of the conversion report:**

<figure><img src="../.gitbook/assets/Excel - conversion status.jpg" alt=""><figcaption><p>Img 5 - Snapshot of Conversion report</p></figcaption></figure>

The conversion report presents the initially filled columns used for conversion. It also includes additional fields:

* **Short URL:** The alias used for the URL.
* **Long URL:** The shortened link with the alias.
* **Error:** In the case of any error, it displays the type of error.
* **Status:** Conversion status - 1. Success or 2. Failed.

**The shortened urls are shown below for reference:**

<figure><img src="../.gitbook/assets/Excel - converted urls.jpg" alt=""><figcaption><p>Img 6 - Shortened urls using Excel bulk converter</p></figcaption></figure>
