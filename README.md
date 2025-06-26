# cs340-grazioso-salvare-rescue-dashboard

#Creator: Hunter Marx

Required functionality:
MongoDB + Dash dashboard to identify rescue dogs for Grazioso Salvare. Filters by breed/age/rescue type. Includes data table + geolocation charts. CS 340 Project Two
*MISSING SCREENSHOTS - Connection functionality unsucessfuly due to faulty host. Final project unable to retrieve data. User plans to recreate outside of apporto in the future and will push updates to this repo.

Describe the tools used to achieve this functionality and a rationale for why these tools were used:
- MongoDB (Used as the database to store and query data. MongoDB is ideal due to easy Python integration with Pymongo and flexible NoSQL structure)
- Dash (web framework for building dashboard UI. Provided the view structure as widgets/charts etc. Provided the controller structure as callback functions. This allowed reactive UI updates without Javascript.)
- Apporto (used so to streamline software configuration - replaceable with local environment)
- Jypiter notebook (for client side scripting)
- Python (a portable CRUD module)

Steps to complete project:
- import database server side and set up credentials
- Code python module for CRUD functionality
- Test CRUD functionality from ipynb client side
- Code Dash UI with filters
- Test Functionality

My greatest challenge was establishing consistent connectivtiy. I ended up coding many try and catch statements and continously making my error handling more robust until I had very specific information on what was going wrong. This lead me to discover that my connectivity with MongoDB was working, but my connectivity with the host was not. I plan to configure my local system so I am continue the development of this project, at which point I will push my updates to this repo.

- Included are screenshots of the empty dashboard as well as the connection error
  ![image](https://github.com/user-attachments/assets/70fe02eb-c872-4ece-8730-25b3c9f9e6dd)
  ![image](https://github.com/user-attachments/assets/e4db5f85-9ceb-4c5d-b0aa-8cae5fd064cc)
