# About Page

The Municipal Library operated by the New York City Department of Records and
Information Services (DORIS) is responsible for providing information about City
government to the public. This includes reports dating to the 19th Century and 
up-to-the minute reports that are available on our website.

We have revamped the government publications portal to provide easy access to 
these documents and we have increased the number of reports available online. 
This new portal includes reports from most City offices and agencies. We will 
be adding additional types of information to the portal in the upcoming months 
and we will continue to solicit past reports and additional government 
participants. You will not find documents from the following entities on this 
portal: The Center for Economic Opportunity, the Center for Innovation through 
Data Intelligence, the Economic Development Corporation, The Health and 
Hospitals Corporation and the Department of Small Business Services. 

# Github Wiki/Readme

## Government Publications Portal

### About

This application was built under the direction of Joel Castillo by three 
talented interns from the NYU Polytechnic School of Engineering, Alan Chen, 
Alvi Kabir, and Panagis (Peter) Alisandratos using Python and the Flask 
microframework. We currently use the following packages in our application:

- Flask 0.10.1
- Flask-Mail 0.9.0
- Flask-Migrate 1.2.0
- Flask-Moment 0.4.0
- Flask-MySQL 1.2
- Flask-SQLAlchemy 2.0
- Flask-Script 2.0.5
- Flask-WTF 0.10.2
- Flask-WhooshAlchemy 0.56
- Jinja2 2.7.3
- Mako 1.0.0
- MarkupSafe 0.23
- MySQL-python 1.2.5
- SQLAlchemy 0.9.7
- WTForms 2.0.1
- Werkzeug 0.9.6
- Whoosh 2.6.0
- alembic 0.6.7
- blinker 1.3
- flask-paginate 0.2.1
- itsdangerous 0.24
- marshmallow 0.7.0
- six 1.8.0
- wsgiref 0.1.2

We are also making use of MySQL Community Edition (v 5.1) to house our database.

### Features

- Basic Search – The default search will comb through the database searching 
document titles, descriptions, agencies, types, and categories to give you the 
best possible results.
- Advanced Search – You can filter your results By Agency, Category, and Type 
to make the search even faster and targeted.
- Fulltext Search – The next version of the app will have full text search for 
all documents.
Currently this feature is only available for the City Record published from 
2008 to the present.
- Sorting – All searches can be sorted by Agency, Category, Type, and Relevance.
- Dynamic Pagination – Allows users to view 10, 20, 50, or 100 results per page.
- Embedded PDFs – To make it easier to view the documents, the files are 
embedded in the results page, allowing the user to view their document without 
manually saving to their computer.

### Upcoming Features

- Full Text Search – Full text search will be available for all documents in 
the near future, making it even easier to find the right document.
- Relevancy Scores – A percentage based score of how relevant a result is to 
your original search query.
- CSV Export – Users will be able to export their search results to a CSV file 
for manipulation in a program such as Microsoft Excel.
- API – Allow other applications to take advantage of our database of documents 
and display them in unique ways to users.

### Getting Involved

We are launching this product as a beta so that we can get your input. Please
use our feedback form or Github issues to submit new requests and bug reports.
We would also encourage you to send any improvements on our code. Clone our 
repository and show us what you can do with our codebase to make it even better.

### Acknowledgements

Special thanks to our four talented interns
(Alan Chen, Alvi Kabir, Brandon Tang, and Panagis Alisandratos);
