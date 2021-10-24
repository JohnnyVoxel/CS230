# CS230
Operating Platforms: Software Design Document

This project covers the design of Draw It or Lose It, a multiplayer web-based game by The Gaming Room. Their requirements for the project were to develop apps for both Android and iOS, and have those apps integrate with their existing server. The apps needed to have the same functionality as their existing browser-based client and for all apps to be able to play together synchronously.

One thing that was done well in preparing this documentation was identifying the strengths and weaknesses of different server implementations. Ultimately, I decided to develop for a Linux based server due to the cost of development, security, and ubiquity in cloud services. One aspect that I could have improved on was detailing the cost of development for the different client platforms. While I covered the specific knowledge and hardware required for development, I did not calculate cost into the equation.

The key aspects I kept in mind for the development of the software was security, simplicity, and responsiveness. With any internet connected software, security is paramount and should be the top priority when developing the app. Using an established and proven framework for authentication and authorization is a good first step. Simplicity and responsiveness go hand in hand. The more overly complex and bloated a program becomes, the less responsive it will be for the end user and ultimately lead to a poor experience. By focusing on lean secure code, you will end up with a better and safer product.
