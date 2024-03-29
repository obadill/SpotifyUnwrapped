# Spotify UnWrapped

## Revolutionize Your Musical Journey

Spotify UnWrapped offers a unique way for users to interact with their Spotify listening history. With real-time access to personalized listening statistics users can discover and share their musical journey anytime. This application is designed for music enthusiasts eager to explore their listening patterns, preferences, and how these evolve over time.

### Quick Setup Guide

#### How to Use Spotify UnWrapped

1. **Clone the Repository**: Clone this repository into a desired folder on your local machine.
`git clone <repository-url>`

2. **Configure API Keys**: Open the `functions.py` file in the cloned repository. You will find placeholders for Spotify API keys. Follow the steps below to obtain and insert your API keys.

#### How to Get Spotify API Keys

1. Visit the [Spotify Developer Dashboard](https://developer.spotify.com/dashboard/) and log in or create an account if you don't have one.

2. Click on your profile icon, then click `Dashboard`.

3. Click `Create an App` and fill out the form. For this project, you can name it "Spotify UnWrapped".

4. For the redirect URL, use your local host IP followed by `/redirectPage`. This can be found by running a Flask application. Example: `http://127.0.0.1:5000/redirectPage`

5. Select the "Web API" checkbox, agree to the terms, and click "Save".

6. You will receive your `CLIENT_ID` and `CLIENT_SECRET`. Replace the placeholders in `functions.py` with these values.

7. For `SECRET_KEY`, use a random string. This is used to secure your Flask application. For example: `asdf` will work just fine.

8. Ensure all keys are enclosed in quotation marks to be recognized as strings.

### Key Features

- **Real-Time Insights**: Get up-to-date statistics on your most listened to songs, top artists, and favorite genres.
- **Personalized Experience**: Explore a dynamic and interactive visualization of your listening habits.
- **Share Your Musical Story**: Easily share your music insights with friends and followers on social media.
- **Continuous Updates**: Unlike the annual Spotify Wrapped, Spotify UnWrapped provides a constantly evolving view of your musical journey.

### How It Works

1. **User Login**: Log in with your Spotify account to grant Spotify UnWrapped access to your listening history.

2. **Data Retrieval**: The application uses the Spotify API and Spotipy to fetch your specific listening data.

3. **Analysis**: Your listening data is analyzed to generate personalized insights, such as top songs, artists, and listening trends.

4. **Visualization**: Your personalized listening statistics are presented in an engaging and visually appealing format.

5. **User Engagement**: Explore your listening habits, discover new music insights, and share your stats with others.

### Getting Started

To start exploring your Spotify listening history with Spotify UnWrapped, simply log in with your Spotify account through our application. Your musical journey, updated in real-time, awaits you.

### Share and Connect

Spotify UnWrapped is not just about discovering your music preferences; it's also about connecting with others through music. Share your insights and find friends with similar tastes to discover new music together.

### Join Us

Dive deeper into your musical story with Spotify UnWrapped and share your journey with the world.

"""