# ScientificProgramming1
## Assignment 1 Server-Client Interaction 

The focus during this assignment will be on the Thyroid stimulating hormone receptor (TSHR) gene. Other names for this gene are LGR3, thyrotropin receptor, TSH receptors and TSHR_HUMANS. The protein encoded by this gene is a member of the glycoprotein hormone receptor family, which is part of a larger superfamily of G protein-coupled receptors (GPCRs). This protein plays a key role in the regulation of thyroid development, growth and function. The thyroid gland is a butterfly-shaped tissue in the lower neck, in which the most receptors are on the outer surface of the cell and only a small amount is kept in the inside of the cell. TSHR gene mutations are known in people with congenital hypothyroidism, which is a condition caused by a very low thyroid hormone level. Impaired thyroid stimulating hormone receptors can also affect thyroid development, causing the gland to be smaller than normal. Another condition that affects the function of the thyroid is Graves disease, which is characterized by an overactive thyroid, making more hormones than the body needs.

In this assignment I will create two HTML files, one to access content from the Open PHACTS database using ops.js library and the second to access the content from Wikidata using SPARQL and wikidata-sdk.js. The first step is writing the html files using JavaScript and SPARQL as programming languages, in which the script needs to retrieve the gene/protein information from the Open PHACTS and Wikidata. Eventually the HTML sends a query to Open PHACTS and Wikidata, who will send this back to JavaScript to extract the information. The information obtained from OpenPHACTS will contain the top 10 drugs that target TSHR and the html file for the wikidata will display gene information. 

### Prerequisites
Google chrome and Notepad++

#### Built with
JavaScript and SPARQL

#### File formats
HTML and JSON

#### Approaches
* Server-Client communication
* REST API
* ops.js and wikidata-sdk.js
