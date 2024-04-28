# ATM_Mangement_System
ATMs are Automated Teller Machines that are used to carry day-to-day financial transactions. ATMs can be used to withdraw money or to deposit money or even to know the information of an account like the balance amount, etc. They are convenient and easy to use,and  it allows consumers to perform quick self-service transactions.

Automated Teller Machines (ATMs) are indispensable tools for day-to-day financial transactions, offering convenience and ease of use. In this article, we delve into the ATM Management System in C++, a comprehensive application mirroring the functionalities of real-world ATMs.

Key Functions:

1. Enter Personal Information:
   - Users input their name, account number, and account type for transaction identification.
   - The system displays transaction-related information based on user inputs.

2. Deposit Funds:
   - Users enter the amount to be deposited into their account.
   - The system updates the account balance accordingly.

3. Check Account Balance:
   - Users can view their current account balance.

4. Withdraw Funds:
   - Users specify the amount to be withdrawn from their account.
   - The system verifies the availability of funds and updates the account balance accordingly.

5. Transaction Cancellation:
   - Users have the option to cancel ongoing transactions.

Approach:

- Implementation leverages fundamental concepts of classes, access modifiers, data types, variables, and switch-case statements in C++.
- Functionalities are encapsulated within class methods:
   - `setvalue()`: Sets user data using standard input/output methods (cout and cin).
   - `showvalue()`: Prints user data.
   - `deposit()`: Facilitates depositing funds into the account.
   - `showbal()`: Displays the total account balance post-deposit.
   - `withdrawl()`: Enables withdrawal of funds from the account.
- The `main()` function orchestrates the application flow, presenting users with a menu-driven interface through a switch-case construct within an infinite loop for continuous interaction.

Overall, the ATM Management System in C++ provides users with a seamless and intuitive interface for performing various financial transactions, ensuring a smooth and efficient banking experience.
