# WatchMe
## Componentizing the application
### Module 1 - Challenge 2 - RocketSeat - Ignite ReactJS 🔥
---
<p>
  <a href="https://rocketseat.com.br">
    <img alt="Made by Rocketseat" src="https://img.shields.io/badge/made%20by-Rocketseat-blueviolet?style=plastic">
  </a>
  <img src="https://img.shields.io/badge/solved%20by-Jorge%20Eder-blueviolet?style=plastic">
  <img alt="GitHub Top Language" src="https://img.shields.io/github/languages/top/jorgeeder/ignite-challenge-02?color=blue&style=plastic">
  <a href="https://opensource.org/licenses/MIT">
    <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen?style=plastic">
  </a>
</p>

An application for listing movies by genre, developed during the first challenge of Ignite, Rocketseat's bootcamp, specifically, from the ReactJS Trail. The project was developed from a previously available template.

The main goal of the challenge was to refactor the `App` component, stripping all the logic and HTML inside it, splitting them into **three components**:

- `Sidebar`: In the sidebar it is possible to select which category of movies should be listed;
- `Header`: The application header has only the name of the selected category which must dynamically change.
- `Content`: The content contains the list of cards of the movies that are contained in the selected category.

## Application in Use

![Application in Use](public/preview.gif)

<br>

## Running The Project

```bash
# Open a terminal and copy this repository with the command
git clone https://github.com/jorgeeder/watchme-ignite-challenge-02

# or use the download option.

# Enter the folder with
cd watchme-ignite-challenge-02

# Install dependencies
yarn install
or
npm install

# Start Fake API
yarn server
or
npm server

# Run the application
yarn dev
or 
npm dev

# Access http://localhost:8080 in your browser
```

<br>

## License

This project is under the MIT license. See the [LICENSE](/LICENSE) file for more details.

Made with 💜 by [Jorge Eder](https://github.com/jorgeeder)

[![Linkedin Badge](https://img.shields.io/badge/-Jorge%20Eder-blue?style=plastic&logo=linkedin&link=https://www.linkedin.com/in/jorgeeder/)](https://www.linkedin.com/in/jorgeeder/)

[![Gmail Badge](https://img.shields.io/badge/-jorgeeder.dev@gmail.com-ff512f?style=plastic&logo=Gmail&logoColor=white&link=mailto:jorgeeder.dev@gmail.com)](mailto:jorgeeder.dev@gmail.com/)