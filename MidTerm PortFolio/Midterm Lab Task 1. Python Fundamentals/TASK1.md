
Problem 1. Use Appropriate Escape
Sequence

SOURCE OF CODE

    name = "John Doe"
    email = "john.doe@example.com"
    university = "ABC University "
    
    print(f"Database Record")
    print("\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\")
    print(f"Name:\t\t\t {name}")
    print(f"Email:\t\t\t {email}")
    print(f"University:\t\t {university}")


<img width="325" height="152" alt="image" src="https://github.com/user-attachments/assets/d98420d7-b369-47e6-b3f6-714d263ff673" />




Problem 2. Using Placeholders for
Email Details

SOURCE OF CODE

    subject ="Greetings"
    sender ="Jane"
    version = "1.2"
    discount = "10.50%"
    status = "A"
    code = "ABCD123"
    location = "City XYZ"
    company = "ABC Corporation"
    website ="www.example.com"
    phone ="1-123-456-7890"
    job_title ="Software Engineer"
    department ="Engineering"
    
    print("Dear John, I hope this email finds you well!")
    print("I want to reach out and say hello :)")
    print("I hope you are doing well and enjoying your day")
    print("It's been a while since we last spoke, and I wanted to catch up with you")
    print("Let's plan to meet up soon and have a great time together!")
    print(f"Subject : %s" % subject)
    print(f"Sender : %s" % sender)
    print(f"Version : %s" % version)
    print(f"Discount : %s" % discount)
    print(f"Status : %s" % status)
    print(f"Code : %s" % code)
    print(f"Location : %s" % location)
    print(f"Company : %s" % company)
    print(f"Website : %s" % website)
    print(f"Phone : %s" % phone)
    print(f"Job Title : %s" % job_title)
    print(f"Department : %s" % department)


<img width="601" height="286" alt="image" src="https://github.com/user-attachments/assets/dfd11aa5-5816-43ea-a9e3-e1062993bbd3" />




Problem 3. Book Reservation

SOURCE OF CODE

    book = str(input("Enter the book title: "))
    author = str(input("Enter the book author: "))
    year = int(input("Enter the year of publication: "))
    genre = str(input("Enter the book genre: "))
    library = str(input("Enter the book library: "))
    member_id = str(input("Enter the member ID: "))
    return_date = str(input("Enter the return date: "))
    
    print(f"You have successfully reserve the book {book}")
    print(f"Year of Publication: {year}.")
    print(f"Genre: {genre}.")
    print(f"Library: {library}.")
    print(f"Member: {member_id}.")
    print(f"Return date: {return_date}.")


<img width="379" height="279" alt="image" src="https://github.com/user-attachments/assets/dcea6546-6fa3-4c40-a7a4-071a3d9606bd" />




Problem 4. Day Identifier

SOURCE OF CODE

    day = int(input("Enter the day: "))
    
    if day == 1:
        print("Monday")
    elif day == 2:
        print("Tuesday")
    elif day == 3:
        print("Wednesday")
    elif day == 4:
        print("Thursday")
    elif day == 5:
        print("Friday")
    elif day == 6:
        print("Saturday")
    elif day == 7:
        print("Sunday")
    else:
        print("Invalid Input")



  <img width="336" height="435" alt="image" src="https://github.com/user-attachments/assets/64837472-125b-4a49-8156-316df3596f11" />
