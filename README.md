## Weather App - Android Studio Project

This project is a weather app built for Android Studio. It retrieves and displays weather information for a specific location or the user's current location.

Features:

* Displays current weather for a specific location (user input)
* Retrieves current location and displays weather for that location
* Shows current day weather forecast for different times (morning, afternoon, evening)
* Uses Picasso library for efficient image loading
* Uses Volley library for JSON parsing of weather data
* Leverages Google Play Services for accessing current location
* Fetches weather data from the weatherapi.com API (requires API key)

Setup Instructions:

1. Download and Install Android Studio:[https://developer.android.com/studio](https://developer.android.com/studio)
2. Clone or Download Project: (Replace with instructions on how to obtain your project)
3. Obtain API Key:
    * Create an account on weatherapi.com
    * Generate an API key from your account dashboard
4. Configure API Key:
    * Open `app/build.gradle` file
    * Find the section with `BuildConfig` and add the following line, replacing `YOUR_API_KEY` with your actual key:

        BuildConfig.WEATHER_API_KEY = "YOUR_API_KEY"
        
5. Run the App:
    * Connect your Android device or launch an emulator
    * Click the "Run" button in Android Studio

Additional Notes:

* This project uses libraries like Picasso and Volley. These libraries are likely already included in the project dependencies, but you may need to check and add them if necessary.
* Reference documentation for the used libraries (Picasso, Volley, Google Play Services) can be found online for further details on their functionalities.
* Weatherapi.com offers free and paid API tiers. This project likely uses the free tier, which may have limitations on usage.
........................................................................................................................................................................................................................................................



