# rest-countries-gen-ai 🌍

## Application Description

`rest-countries-gen-ai` offers an interface to fetch detailed information about different countries based on specified filters. The application serves not only basic details like a country's name or population, but also an array of specifics including translations, currencies, and much more.

The API allows users to filter results based on parameters such as name, population, sorting method, and pagination controls. This makes it a versatile tool for anyone needing country-specific details.

## Running the Application Locally 🚀

1. Ensure you have the required dependencies installed, such as Mule Runtime and the relevant Anypoint Studio version.
2. Clone or download the project repository to your local machine.
3. Open Anypoint Studio and import the project.
4. Navigate to the Package Explorer, right-click on the project, and choose **Run As** > **Mule Application**.
5. Once the application is deployed successfully, it will run on the default port, typically `8081`.

## How to Use the Developed Endpoint 🛠

Given the `/countries` endpoint, here are some example usages:

1. **Fetch All Countries**:  
   `http://localhost:8081/countries`
2. **Filter by Country Name**:  
   `http://localhost:8081/countries?name=Sp`
3. **Filter by Population**:  
   `http://localhost:8081/countries?population=10`
4. **Sort by Name Ascending**:  
   `http://localhost:8081/countries?sort=ascend`
5. **Sort by Name Descending**:  
   `http://localhost:8081/countries?sort=descend`
6. **Pagination Offset**:  
   `http://localhost:8081/countries?OFFSET=1`
7. **Limit the Number of Records**:  
   `http://localhost:8081/countries?LIMIT=1`
8. **Filter by Name and Population**:  
   `http://localhost:8081/countries?name=Sp&population=10`
9. **Sort and Filter by Name**:  
   `http://localhost:8081/countries?name=Sp&sort=descend`
10. **Advanced Query with Multiple Parameters**:  
   `http://localhost:8081/countries?name=Sp&population=10&sort=ascend&OFFSET=1&LIMIT=5`

---

I hope this serves as a useful guide to the application and its endpoint! 📘
