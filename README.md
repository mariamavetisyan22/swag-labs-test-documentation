# Swag Labs Test Documentation
- This is the test documentation of the open source project [Swag Labs](https://www.saucedemo.com) which includes a test document file of the demo account creation page, you can find the test environment parameters, requirements, possible test scenarios, test data (in one table for easy use) and test cases.

  There are the scenarios of the documented file.
- In the Swag Labs Test Cases.doc file indicates test cases for the following four scenarios.
  
  1. Log in as a standard_user, add 2 items to the cart, and complete the order.
  2. Log in as a standard_user and check the item's sorting functionality.
  3. Log in as a performane_glitch_user and check the application's behavior.
  4. Log in as a problem_user and check the application's behavior.

## **Test Objective**
 
Testing the page [Swag Labs](https://www.saucedemo.com) aims to ensure that all the essential functionalities and features work as intended and provide a seamless user experience during the login process.

## **Test Environment**
Parameters | Values | 
--- | --- |
Operating System | Windows 11 Home, 22H2, 22621.1778 |
Browser | Chrome: 114.0.5735.110 (Official Build) (64-bit) |
Screen Resolution | 1920x1080 pixels |

## **Requirements**

- **Username:** The field should allow only text with an underscore without any spaces
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


