# shiny-fishstick
Traveler friends' contact list
When I travel and meet new people I want to save their contact information to hang out/plan other trips or just talk to them, so I found a need for a program that can maintain a list of contacts, including their full names, phone numbers, and email addresses so I can keep track of it without getting my personal contacts mixed up, so we are creating a Traveler Contact List to have this information apart for easy access. Contact details like names, phone numbers, and email addresses are among the input data that this application is anticipated to collect. Through the program's user interface, the user will enter this information. The program will address the issue by giving the user access to a mechanism for saving, editing, and deleting contact information. To manage the contact information, the software will make use of Python's data structures. The user will need to add the information to the program so it can be stored. As I mentioned, I want to solve this problem because I meet people all around the world, and most of the time I lose track of their information because I have too many contacts in my normal list. I wanted to add more details to always remember how we met and to keep in touch in the future. The expected results are that the program works perfectly and smoothly, so the user can look up and add those details at any time. The program indicates what is needed so it is easy to comprehend.  

Scenario 1: The user selects option 3: Display all contacts without adding any contacts to the list first, it will show the next line: No contacts found! 
The user selects option 1: Add a new contact and proceeds to add the information about her friend, Aria whom she met in Greece last year. The information she should be seeing once she finishes is this: 
Name: Aria
Phone: 20451525
Email: No email
Country: Greece
Met: We met in 2022 at a museum
Here I tried to use an edge case and it worked, the output shows that she needs to add friends to the list before showing her the list since she did not add one yet.

Scenario 2: Victoria selects option 1 and adds a traveler friend to the list: Leon, phone number: 12345678, email address: Leon123@gmail.com, country: USA. They met at a restaurant. The program should generate the information like this once Victoria selects option 3:
Name: Leon
Phone: 12345678
Email: Leon123@gmail.com
Country: USA
Met: At a restaurant.
