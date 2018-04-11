{\rtf1\ansi\deff0\nouicompat{\fonttbl{\f0\fnil\fcharset0 Courier New;}}
{\colortbl ;\red0\green0\blue255;}
{\*\generator Riched20 10.0.16299}\viewkind4\uc1 
\pard\f0\fs22\lang1033 Why do it ?\par
\par
\tab Because Tech is exciting, but unpredictable.\par
\tab A back-up income strategy is needed.\par
\tab For Happy / Early Retirement\par
\par
Case Study:\par
\par
\tab Buy single family house in expanding job market in South \tab Carolina\par
\par
\tab Be lazy for 10 years and collect rent\par
\tab Check back to see value increase 4x times after 10 years\par
\par
Factors considered for property investment:\par
\par
\tab Cost of single family house\par
\tab School ratings\par
\tab Job growth\par
\tab Crime rate\par
\tab Cost-to-Rent ratio\par
\par
Data Sources:\par
\par
\tab Zipcode Csv file from USPS \tab ({{\field{\*\fldinst{HYPERLINK https://tools.usps.com/go/ZipLookupAction_input }}{\fldrslt{https://tools.usps.com/go/ZipLookupAction_input\ul0\cf0}}}}\f0\fs22 )\par
\par
\tab Rental Data from City Data API ({{\field{\*\fldinst{HYPERLINK http://www.city-data.com/ }}{\fldrslt{http://www.city-data.com/\ul0\cf0}}}}\f0\fs22 )\par

\pard\li720\par
Rental & Cost of Single Family House from Zillow\par
({{\field{\*\fldinst{HYPERLINK https://www.zillow.com/howto/api/APIOverview.htm }}{\fldrslt{https://www.zillow.com/howto/api/APIOverview.htm\ul0\cf0}}}}\f0\fs22 )\par
\par
Property Data from Quandl API\par
({{\field{\*\fldinst{HYPERLINK https://www.quandl.com/tools/api }}{\fldrslt{https://www.quandl.com/tools/api\ul0\cf0}}}}\f0\fs22 )\par
\par
Great Schools API ({{\field{\*\fldinst{HYPERLINK https://www.greatschools.org/ }}{\fldrslt{https://www.greatschools.org/\ul0\cf0}}}}\f0\fs22 )\par
\par
Crime Rate Data retrieved from Crime Rate website ({{\field{\*\fldinst{HYPERLINK http://www.crimerate.com/ }}{\fldrslt{http://www.crimerate.com/\ul0\cf0}}}}\f0\fs22 )\par
\par
Job Growth Data retrieved from Bureau of Labor Statistics ({{\field{\*\fldinst{HYPERLINK https://www.bls.gov/sae/#tables }}{\fldrslt{https://www.bls.gov/sae/#tables\ul0\cf0}}}}\f0\fs22 )\par

\pard\par
Retrieval Methods:\par
\tab\par
\tab APIs to retrieve data using requests module\par
\tab\par
\tab Web scraping using BeautifulSoup module\par
\tab\par
\tab Converting XML data to python dictionaries using XmlDict \tab module\par
\par
\tab Converting HTML tags into text and selecting data using \tab split function\par

\pard\li720\par
Converting unstructured scraped data using regular expressions\par
\par
Python Pandas for aggregation and clean up of data\par

\pard\par
Data Summary & Metrics\par
\par
\tab Data retrieved for 407 zip codes in South Carolina state.\par
\tab\par
\tab After cleanup and aggregation, final data set contains \tab data for 206 zip codes\par
\par
\tab Normalization of 'Rent', 'School Ratings', 'Job Growth' & \tab 'Crime Rate' to a factor of '1'\par
\par
\tab Summary metric derived by adding the normalized values\par
}
 