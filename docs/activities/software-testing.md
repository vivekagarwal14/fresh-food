# Software Testing
Each of the action items in section 1.4 (Iteration 1 Design and Implementation) are to be tested sequentially with an emphasis on functionality rather than UX design.
1. Item 1.4.1 (Design of customer login page) implementation testing:
    1. A pre-set customer with a unique login credential should be able to log in and be redirected to a restaurant list page with no errors.
    2. When either the login or password is entered incorrectly, the system prompts the user to retry.
2. Item 1.4.2 (Design of restaurant order manager login page) implementation testing:
    1. A pre-set restaurant order manager with a unique login credential should be able to log in and be redirected to a restaurant list page with no errors.
    2. When either the login or password is entered incorrectly, the system prompts the user to retry.
3. Item 1.4.3 (Preliminary UI for restaurant selection) implementation testing:
   1. Upon successful login by the customer, a pre-set number of restaurants are viewed in a single column.
   2. If the column size exceeds the screen resolution, the user should be able to scroll through the list in order to view all available restaurants.


# Approach / Details - 
1. Reliability protocols - overloading system with requests.
2. Invalid inputs
   1. No pin code, wrong address, etc.
   2. Invalid email/credit card number
3. Testing time constraints for delivery - looking for accuracy of estimation.
   1. Ensure that we can accommodate the carrying capacity proposed.
4. Security testing (pen testing, payment encryption protocols, etc.)
5. Functional Testing - basic flow of what the system intends to do
6. User-Acceptance Testing - testing with beta users
7. Cross-platform validation - does our service run equally well on mobile/web, Android/iOS?
8. Integration Testing - 
   1. Interservice integration testing
   2. External integration testing

