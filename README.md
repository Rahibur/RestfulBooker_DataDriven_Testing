# **API Testing**
![Image](https://github.com/user-attachments/assets/cbf74dc0-d2fd-4715-9240-fea0265fcfb3)
### Project name: RestfulBooker
([https://restful-booker.herokuapp.com](https://restful-booker.herokuapp.com/))

### Test Summary Link: [Click here to view ](https://sites.google.com/view/rahibur-rahman/projects)

For further information, feel free to contact me:
Website: [www.rahiburrahman.com](http://www.rahiburrahman.com/) LinkedIn: [Rahibur
Rahman](https://www.linkedin.com/in/rahibur-rahman-2158a4241/)

## **Overview**

Restful-booker is an API that you can use to learn more about API
Testing or try out API testing tools against. Restful-booker is a Create
Read Update Delete (CRUD) Web API that comes with authentication
features and is loaded with a bunch of bugs for you to explore.

## **API Endpoints Tested**

1 POST - Create Authentication Token

  -----------------------------------------------------------------------
  ![](./image1.png)
  -----------------------------------------------------------------------
  
  -----------------------------------------------------------------------

2 GET - Retrieve All Bookings
![Image](https://github.com/user-attachments/assets/3d7789bc-e2aa-406d-bdcc-dcf12d7c9dc0)

-----------------------------------------------------------------------
3 POST - Create a Booking
![Image](https://github.com/user-attachments/assets/fec59957-bfc7-4fed-a0fa-aeab89b41ba5)

-----------------------------------------------------------------------
4 GET - Retrieve a Single Booking
![Image](https://github.com/user-attachments/assets/7eacf746-46c4-4541-a948-d9bee8d4c902)

-----------------------------------------------------------------------
5 PUT - Update Booking
![Image](https://github.com/user-attachments/assets/43863409-e54e-4a87-86bb-c97997f0d2c9)

-----------------------------------------------------------------------
6 GET - Retrieve Updated Booking Data
![Image](https://github.com/user-attachments/assets/71e60250-483d-4902-8fc6-881700ffb8aa)

-----------------------------------------------------------------------
7 PATCH - Update a Partial Booking
![Image](https://github.com/user-attachments/assets/a978f14c-09d8-4812-aad5-00b52900b287)

-----------------------------------------------------------------------
8 DELETE - Remove a Booking
![Image](https://github.com/user-attachments/assets/9b3306a2-0aee-43ec-9c14-db5a556ae8b3)

-----------------------------------------------------------------------
## **Testing Approach**

1.  Authentication Testing:

    -   Verified if the API generates a valid authentication token for
        authorized access.

2.  CRUD Operations Testing:

    -   Ensured that new bookings could be created, retrieved, updated,
        and deleted correctly.

3.  Data Validation:

    -   Checked whether invalid data inputs were handled properly,
        including error responses.

4.  Response Time & Performance:

    -   Measured API response times to ensure efficient processing.

5.  Error Handling & Bug Exploration:

    -   Investigated how the API responds to invalid requests or
        incorrect authentication.

## **Test Results & Observations**

-   Success Rate: Most CRUD operations were functional, but some
    inconsistencies were found in error handling for incorrect data
    inputs.

-   Authentication Issues: The authentication token was required for
    some requests but was not always validated correctly.

-   Data Consistency: Updating a booking worked correctly, but
    retrieving updated data had minor inconsistencies.

-   Bugs Identified:

    -   Some endpoints returned unexpected responses when provided with
        missing or invalid data.

    -   Partial updates via PATCH did not always reflect changes
        immediately.

**Conclusion**

The RestfulBooker API is a great tool for practicing API testing and
learning about various testing techniques. While it mostly functions as
expected, it contains built-in bugs that allow testers to explore
different failure scenarios. Further improvements in error handling and
data consistency would enhance its reliability.
