
* **The objective is to show that the following activities have been accomplished:**

* **The two microservices accounts (2222) and web are running and registered (two terminals, logs screenshots)**
    
    Accounts on port 2222:
      ![account2222](images/account2222.png)
      
    Web on the terminal and the browser:
        ![web](images/web3333.png)
        ![web_dasboard](images/web_dashboard.png)
        
      

* **The service registration service has these two microservices registered (a third terminal, dashboard screenshots)**
    
    Registration launched:
      ![registration](images/registration1111.png)
      
    Registration dashboard:
      ![dashboard_registration](images/dashboard_registration.png)

* **A second accounts microservice instance has been started and will use the port 4444. This second accounts (4444) is also registered (a fourth terminal, log screenshots).**
    
    Accounts on port 4444:
      ![account4444](images/account4444.png)
      
    Dashboard with new accounts service:
      ![registration_2services](images/registration_2services.png)

* **What happens when you kill the microservice accounts (2222) and do requests to web? Can the web service provide information about the accounts again? Why?**
    
    Killing the microservice accounts on port 2222, as it's seen the instance of the service has been cancelled.
    ![killingAccount2222](images/kill2222.png)
    
    Checking it does not appear on the dashboard:
    ![dashboardjust4444](images/just4444.png)
    
   The microservice has been remove from the registration dashboard, however the web service still can provide information about the accounts due to there's a second
   accounts service registered. It's now using the microservice on port 4444 to provide the information.
   