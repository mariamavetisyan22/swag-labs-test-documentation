# Swag Labs Test Documentation
- This is the test documentation of open source project [Swag Labs](https://www.saucedemo.com) which includes test document file of the demo account creation page, below you can find the test environment parameters, requirements, possible test scenarios, test data (in one table for easy use) and test cases.

  There are the scenarios of the documented file.
- In the Swag Labs Test Cases.doc file indicates test cases for following four scenarios.
  
  1. Log in as a standard_user, add 2 items to cart and complete order.
  2. Log in as a standard_user and check items sorting functionality.
  3. Log in as a performane_glitch_user and check the behavior of the application.
  4. Log in as a problem_user and check behavior of the application.

## **Test Objective**
 
The objective of testing the page [Swag Labs](https://www.saucedemo.com) is to ensure that all the key functionalities and features work as intended and provide a seamless user experience during the login process.

## **Test Environment**
Parameters | Values | 
--- | --- |
Operating System | Windows 11 Home, 22H2, 22621.1778 |
Browser | Chrome: 114.0.5735.110 (Official Build) (64-bit) |
Screen Resolution | 1920x1080 pixels |

## **Requirements**

- **Username:** the field should allow only text with underscore without any spaces
- **Password:** field must be filled out with English alphabet letters and must include three character types: lowercase letters, uppercase letters and numbers. You also have the option to use any of these special characters: # [ ] ( ) @ $ & * ! ? | , . ^ / \ + _ -
   - 10 — 15 characters
   - At least one uppercase letter (ABC...)
   - At least one lowercase letter (abc...)
   - At least one number (123...)


## **Test Data**
#### _Valid Test Data_
  - **Username:** standard_user; problem_user; performance_glitch_user
  - **Password:** secret_sauce

## **Test Execution Results**
Parameters | Values | 
--- | --- |
**Total** | **$${\color{black}23}$$** |
Passed | $${\color{green}23}$$ |
Failed | $${\color{red}5}$$ |


