rest-countries-gen-ai
Description
rest-countries-gen-ai is a RESTful web service designed to provide detailed information about various countries based on specified filters. Users can query information related to a country's name, population, and more. The responses include comprehensive details, including official names, translations, currency, population, and geo-locational data.

Running the Application Locally
Ensure that you have Mule Runtime installed and appropriate Anypoint Studio version.
Import the project into Anypoint Studio.
In the Package Explorer, right-click on the project name and select Run As > Mule Application.
Once deployed, the application will be running on the default port 8081.
Usage Examples
The primary endpoint for querying countries information is /countries. Here are some usage examples:

Retrieve All Countries: http://localhost:8081/countries
Filter by Country Name: http://localhost:8081/countries?name=Sp
Filter by Population: http://localhost:8081/countries?population=10
Sort Countries by Name in Ascending Order: http://localhost:8081/countries?sort=ascend
Sort Countries by Name in Descending Order: http://localhost:8081/countries?sort=descend
Pagination - Set Offset: http://localhost:8081/countries?OFFSET=1
Pagination - Limit Records: http://localhost:8081/countries?LIMIT=1
Combination of Filters: http://localhost:8081/countries?name=Sp&population=10
Combination with Sorting: http://localhost:8081/countries?name=Sp&sort=descend
Complex Combination: http://localhost:8081/countries?name=Sp&population=10&sort=ascend&OFFSET=1&LIMIT=5