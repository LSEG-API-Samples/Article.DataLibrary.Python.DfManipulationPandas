----
<div style="display: flex; align-items: center;">
    <img src="https://developers.lseg.com/content/dam/devportal/icons/logo/lseg-logo.svg" width="20%" style="vertical-align: top;">
</div>

# [Dataframe Manipulation with Pandas, a Beginner's Guide](https://developers.lseg.com/en/article-catalog/article/dataframe-manipulation-with-pandas-a-beginners-guide)

----

## Introduction to Pandas and Dataframes

[Pandas](https://pandas.pydata.org/), a very popular library in Python, helps us to work with data easily. You can think of it as a tool that allows us to play with data, like moving columns and rows in an Excel sheet. Pandas makes it easy to clean, modify, and analyze data, making it very useful in the data-related projects such as data science projects.

[DataFrame](https://pandas.pydata.org/docs/reference/frame.html#dataframe) is like a table with rows and columns. It's similar to a table in SQL or an Excel spreadsheet, making it easy to work with structured data and allow you to organize data in a way that is easy to read and work with.

## Setting Up Your Environment
Here, I'm using **Python version 3.12.4** with Python libraries: **pandas version 2.2.2** and **lseg.data version 2.0.0** to retrieve the data.

Pandas can be installed with the 'pip' command as below (Python and pip needed to be installed first). More detail of Pandas installation can be found in [this page](https://pandas.pydata.org/docs/getting_started/install.html).

## Retrieving the data
Data can be loaded into the DataFrame from different sources, such as importing it from CSV/Excel files, JSON data, SQL Database or retriving the data from any Python libraries.

In this article, we're retrieving the data from [LSEG Data Library for Python](https://developers.lseg.com/en/api-catalog/lseg-data-platform/lseg-data-library-for-python), which provides a set of ease-of-use interfaces offering coders uniform access to the breadth and depth of financial data and services available on the LSEG Data Platform. The API is designed to provide consistent access through multiple access channels and target both Professional Developers and Financial Coders. Developers can choose to access content from the desktop, through their deployed streaming services, or directly to the cloud. With the LSEG Data Library, the same Python code can be used to retrieve data regardless of which access point you choose to connect to the platform.

The example code can be found in [GitHub Example - Data Library Python](https://github.com/LSEG-API-Samples/Example.DataLibrary.Python/tree/lseg-data-examples), such as [EX-1.01.01-GetData.ipynb](https://github.com/LSEG-API-Samples/Example.DataLibrary.Python/blob/lseg-data-examples/Examples/1-Access/EX-1.01.01-GetData.ipynb). For example, let's retrieve data of MAMAA stocks (Meta, Amazon, Microsoft, Apple and Alphabet). To find the instruments and fields you're interested in, [Data Item Browser](https://developers.lseg.com/en/video-catalog/data-item-browser) can be used.

## Conclusion
In this beginners' guide to dataframe manipulation with Pandas, we've covered the essential functions that are the backbone of data analysis in Python from loading data and inspecting it, to filtering, grouping, and transforming. Pandas provides a powerful toolkit that simplifies working with complex datasets. By using practical examples and applying these techniques to datasets, you should now have a solid foundation to manipulate dataframes. Whether you're cleaning data, performing exploratory analysis, or preparing data for machine learning models, mastering these Pandas basics will signigicantly enhance your data science capabilities.
For further reading and more advanced tutorials, consider exploring the [official Pandas documentation](https://pandas.pydata.org/docs/getting_started/index.html) and using it with the datasets provided by LSEG via [LSEG Data Library for Python](https://developers.lseg.com/en/api-catalog/lseg-data-platform/lseg-data-library-for-python).
