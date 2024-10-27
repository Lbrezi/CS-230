# CS-230

Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?
 - Draw It or Lose It is a web-based game application where teams of players guess on puzzles based on randomly rendered images. 
    - Game Structure:
      - Four rounds of play, each lasting one minute.
      - Drawings will be rendered at a steady rate and fully completed by the 30-second mark.
      - Teams must guess the puzzle within the time frame. If unsuccessful, other teams will have a 15-second opportunity to make a single guess each.
  - The application will render images from a large library of stock drawings as clues.
  - A game will have the ability to have one or more teams involved.
  - Each team will have multiple players assigned to it.
  - Game and team names must be unique to allow users to check whether a name is in use when choosing a team name.
  - Only one instance of the game can exist in memory at any given time. 

What did you do particularly well in developing this documentation?
  - The recommendation portion of the documentation is my strong suit. I clearly establish what and why I recommend something in a fashion that’s consumable for both tech and non tech savvy business partners. 

What about the process of working through a design document did you find helpful when developing the code?
  - Listing out the Requirements and Design constraints was beneficial in developing the code. It helped me get organized with what exactly the business side expected out of me and allowed me to focus on what needed attention first. 

If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
  - I would redo the Evaluation part of the documentation to have less word clutter and establish what exactly each operating system strengths and weaknesses were for the client, and server side more efficiently.

How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?
  - When designing the software the main thing we kept in mind was having good user experience. More particularly things such as having a good looking UI across every platform, as well as having smooth multiplayer server-client interaction. Finally making sure that when playing Draw It or Lose It having the game run quickly with minimal delay was a big point of concern. So deciding on how to manage different parts of the game such as pre-loading commonly used images was crucial. This overall was important because if you don’t consider the users needs, the entire game falls apart. The users are what drives your product. They are both your consumers and marketing plan. WIth a happy consumer comes a successful game so when designing our software we wanted to make sure the user was getting everything they needed to get the best experience out of the product.

How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?
  - We followed mainly differing Agile principles while keeping our design user-centered when working on this product. We wanted Draw It or Lose It to be flexible and scalable both during the design process and into the future after launch. The use of frameworks such as React makes work cheaper and faster by keeping more of the project on one code base, and would highly recommend its use for future endeavors. 
