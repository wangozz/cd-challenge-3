# FlatIron Movie Theatre

This is a movie website for FlatIron Movie Theatre. It displays a list of movies along with their details and allows users to purchase tickets for the available movies.

## Preview

To see a live preview of the website, follow the steps below:

1. Clone the repository: `git clone <https://github.com/wangozz/cd-challenge-3>`
2. Navigate to the project directory: `cd <cd-challenge-3>`
3. Open the index.html file in a web browser.

## Features

- Sidebar menu displaying a list of movie titles
- Movie posters and details in the main content area
- Ticket purchasing functionality with ticket availability tracking

## Technologies Used

- HTML
- CSS
- JavaScript

## Getting Started

To run the website locally, follow these steps:

1. Clone the repository: `git clone <https://github.com/wangozz/cd-challenge-3>`
2. Navigate to the project directory: `cd <cd-challenge-3>`
3. Open the index.html file in a web browser.

## How It Works

The website fetches movie data from a JSON server at http://localhost:3000/films. It then renders the movie titles in the sidebar and the corresponding movie posters and details in the main content area.

Users can click the "Buy a ticket" button to purchase a ticket for a movie. The button updates its content and style based on ticket availability. When a ticket is purchased, the available ticket count decreases, the ticket details are updated, and the server is updated with the modified film data.

## Movie Data

The movie data is stored in a JSON format. Here are a few examples of movies included in the data:

- The Giant Gila Monster
- Manos: The Hands Of Fate
- Time Chasers
- The Touch Of Satan
- Santa Claus Conquers The Martians
- Track Of The Moon Beast
- The Skydivers
- The Killer Shrews
- Project Moon Base
- The Giant Spider Invasion
- Catalina Caper
- Secret Agent Super Dragon
- Wild Rebels
- Danger: Diabolik
- Village Of The Giants

Each movie includes details such as the title, runtime, capacity, showtime, tickets sold, description, and poster image URL.

## Contributing

Contributions to the project are welcome! If you find any issues or have suggestions for improvement, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
