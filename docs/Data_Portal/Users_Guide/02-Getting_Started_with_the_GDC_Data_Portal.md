# Introduction to the GDC Data Portal

The GDC Data Portal is a robust data-driven platform that allows users to search and download cancer data sets for analysis using modern web technologies. Key GDC Data Portal features include:

*   Data browsing by project, file, case, or annotation
*   Visualization allowing users to perform fine-grained filtering of search results
*   Data search using advanced smart search technology
*   Data selection into a personalized cart
*   Data download from cart or a from GDC Data Transfer Tool

Additional descriptions of key GDC Data Portal features are provided in the section that follows.

# GDC Data Portal Key Features

## Data Browsing

By browsing through the GDC Data Portal, users can obtain details about specific aspects of the data, such as the associated project, files, cases and annotations (explanatory comments about the data). For example, from a project page a user can view files or cases within the project. While users are browsing through the Data Portal, they can progressively add more elements to a cart for data download.

## Visualization

The GDC Data Portal allows researchers to identify data they are looking for and narrow their search using multiple visualization mechanisms such as tables, charts, and plots. Whenever possible, cross-references are enabled so that users can dive into the data directly from a plot.

## Data Searching

GDC Data Portal contains two primary mechanisms for searching data: 1) searching using predefined filters (also called Facets) or 2) searching via advanced search technology and the advanced query language. When a user clicks on a Facet, the GDC smart search is automatically populated to help users get familiar with the advanced query language. At any time, when a need for a more specific query arises, users can switch to smart search and update their query with more specific filters.

## Cart Facilities for Data Selection

While navigating and searching through the GDC Data Portal, researchers can add files to their cart. The cart provides detailed statistics about the files it contains to inform the user about the overall number and size of files the user may want to download.

## Data Download

The GDC Data Portal provides two primary channels to allow users to download data from a cart: 1) download directly from the browser or 2) download using a dedicated Data Transfer Tool. The GDC Data Portal generates a list of desired files (or manifest) that can be easily imported into the GDC Data Transfer Tool to execute the download. Note that users can download all files that are under the GDC open access policy as well as any controlled access files that they have authorization for through dbGaP. Please visit [Obtaining Access to GDC Controlled Data](https://gdc.nci.nih.gov/node/8035/) for information how to obtain authorization to access controlled data sets through dbGaP.

# Accessing the GDC Data Portal

The GDC Data Portal is accessible using a web browser such as Chrome, Internet Explorer, and Firefox at the following URL: [https://gdc-portal.nci.nih.gov](https://gdc-portal.nci.nih.gov). When navigating to the site, the GDC Data Portal main page is displayed (Image 2.3-1).

[![GDC Data Portal Main Page](images/gdc-data-portal-project-page.png)](images/gdc-data-portal-project-page.png "Click to see the full image.")

The GDC Data Portal allows download of open access data without requiring a user login. To retrieve controlled access data, users must have access to the controlled access data set through dbGaP.

# Authentication

While not required for public data access, a user may login using the ‘login’ button at the upper right side of the opening screen.

More details about [Authentication and Authorization](../../Commons/Authentication.md) can be found in a [dedicated section of the documentation](../../Commons/Authentication.md).

If the eRA commons login was unsuccessful, the username will not be displayed.  The ‘Only My Projects’ option is chosen by default, but can be unchecked.  When this option is chosen, the user will only see projects and data for which he/she has authorization.  When it is unchecked, all projects and available data filenames will be shown, but controlled access data for which the user is not authorized will not be able to be viewed or downloaded.

The GDC also supports GDC Data Transfer Tool for downloading high volumes of data, and an Application Programming Interface (API) for programmatic access to data.  The Data Transfer Tool supports download of both open and controlled access data. For download of controlled access data through the Data Transfer Tool and API a valid token (a file containing a unique key) is required. However, a token is not required for controlled data download through the portal.

## Obtaining a Token

After successful authentication, users can [download a GDC Token](../../Commons/Authentication.md#gdc-authentication-token) from GDC Data Portal.

Users obtaining the token file should store it in a safe location where it can also be easily retrieved. The token should be treated with the same care as the eRA Commons password.