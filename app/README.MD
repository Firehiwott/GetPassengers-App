Project Deliverables: GetPassengers App
App Description:
GetPassengers is an Android app designed to collect and display airline passenger information. It consists of two main activities:

MainActivity: Displays the final passenger list and provides a button to navigate to the GetPassengers screen.
GetPassengers Activity: Allows users to enter passenger details (first name, last name, and phone number). The collected data is then sent back to the MainActivity to display the final list.


Challenges and Solutions:
Challenge: Passing multiple passenger entries between activities.
Solution: Implemented an ArrayList of passenger objects and used dynamically generated keys to transfer the data correctly.
Challenge: The Android app is running into low memory issues, which affects performance.  (Still an ongoing issue, working on a solution.)


Key Learning Points:
Gained experience in passing data between activities using Intent and putExtra().
Learned how to structure a simple Kotlin class (Passenger) and override the toString() method for formatted display.
Understood how to define UI components in XML and link them to Kotlin using findViewById()
Practiced handling user input and dynamically updating TextView elements.


Future Improvements:
Input Validation: Prevent users from submitting blank fields or invalid phone numbers.
Edit/Delete Functionality: Allow users to edit or remove passengers before finalizing the list. Database Integration: Store passenger details in a database instead of resetting them when the app closes.
Improved UI Design: Use RecyclerView instead of a simple TextView to display the list more dynamically.







