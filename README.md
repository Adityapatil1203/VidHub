# VidHub

**VidHub** is a YouTube clone built using **React.js** and **Material-UI**, designed to replicate the functionality of YouTube, including video searching, browsing, and viewing. It integrates **RapidAPI** to fetch video data dynamically and ensures a responsive and user-friendly UI.

## Features

- Browse and search for videos in real-time using RapidAPI.
- Responsive design with Material-UI for a modern and clean interface.
- Watch videos directly within the app.
- Dynamic video recommendations based on user input.
- Mobile-friendly layout for seamless user experience across devices.

## Technologies Used

### Frontend:
- **React.js**
- **Material-UI** (Styling and UI Components)

### API Integration:
- **RapidAPI** (for fetching video data and metadata)

### Additional Tools:
- **Vercel** (Frontend Hosting)

## Installation

### Prerequisites:
- Node.js
- RapidAPI Account (for fetching video data)

### Steps to run the project:

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/vidhub.git
    ```

2. Navigate to the project directory and install the dependencies:

    ```bash
    cd vidhub
    npm install
    ```

3. Set up RapidAPI:
   - Go to [RapidAPI](https://rapidapi.com/) and sign up.
   - Subscribe to the necessary YouTube Data API.
   - Create a `.env` file in the root of your project and add your RapidAPI key:

    **.env**:
    ```env
    REACT_APP_RAPIDAPI_KEY=<Your RapidAPI Key>
    ```

4. Start the development server:

    ```bash
    npm start
    ```

5. Open the application in your browser at `http://localhost:3000`.

## Usage

- Enter a search query in the search bar to browse videos.
- Click on any video to watch it directly on the platform.
- Browse related videos in the recommendations section.

## Deployment

You can deploy the application using **Vercel** or any other hosting provider. Follow these steps for deployment on Vercel:

1. Link your GitHub repository to Vercel.
2. Add your environment variable (`REACT_APP_RAPIDAPI_KEY`) in the Vercel dashboard.
3. Deploy the project by following Vercel’s instructions.

## Contribution

Contributions are welcome! Feel free to fork this repository and submit pull requests to improve the project or add new features.

## License

This project is licensed under the MIT License.
