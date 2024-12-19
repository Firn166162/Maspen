# Moroccan News CLI

This project is a command-line interface (CLI) application that fetches and displays the latest news from Morocco. It utilizes TypeScript for development and Axios for making HTTP requests to a news API.

## Project Structure

```
moroccan-news-cli
├── src
│   ├── main.ts          # Entry point of the application
│   └── services
│       └── newsService.ts # Service for fetching and displaying news
├── package.json         # NPM package configuration
├── tsconfig.json        # TypeScript configuration
└── README.md            # Project documentation
```

## Setup Instructions

1. **Clone the repository:**
   ```
   git clone <repository-url>
   cd moroccan-news-cli
   ```

2. **Install dependencies:**
   ```
   npm install
   ```

3. **Configure the news API:**
   - Update the `newsService.ts` file with your news API key and endpoint.

## Usage

To run the application, use the following command:

```
npm start
```

This will execute the `main.ts` file, which fetches the latest Moroccan news and displays it in the command line interface.

## Dependencies

- **axios**: For making HTTP requests to fetch news data.

## License

This project is licensed under the MIT License. See the LICENSE file for details.