# Weather App - Jetpack Compose

A simple yet elegant Weather App built using **Jetpack Compose**. This application follows best practices for modern Android development, leveraging **Retrofit** for API calls, **Coil** for image loading, and a clean architecture with distinct UI and Data layers.

## Features

- Real-time weather data fetched from a weather API
- Responsive UI built with Jetpack Compose
- Dynamic weather icons loaded using Coil
- Separation of concerns with proper architecture (UI layer and Data layer)
- Followed best practices for Kotlin and Android development

## Tech Stack

- **Kotlin** - Primary programming language
- **Jetpack Compose** - Modern UI toolkit
- **Retrofit** - For API communication
- **Coil** - For image loading
- **Hilt** - For Dependency Injection
- **Coroutines** - For asynchronous programming
- **Flow** - For reactive streams

## Architecture

The app follows a clean architecture with two main layers:

1. **UI Layer**:
   - Fully built using Jetpack Compose.
   - ViewModel interacts with the data layer to fetch weather data.
   - Observes LiveData/StateFlow to render the UI reactively.

2. **Data Layer**:
   - Repository pattern for data handling.
   - Retrofit for API calls.
   - Network models mapped to domain models for decoupling.

## Setup

### Prerequisites

- Android Studio Flamingo or later
- Minimum SDK 21
- Internet connection for fetching weather data

### Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/weather-app-compose.git
   ```

2. Open the project in Android Studio.

3. Add your weather API key:
   - Go to `local.properties`.
   - Add the following line:
     ```properties
     WEATHER_API_KEY=your_api_key_here
     ```

4. Sync the project and run the app.

## Key Libraries Used

- [Jetpack Compose](https://developer.android.com/jetpack/compose) - For building native UI.
- [Retrofit](https://square.github.io/retrofit/) - For making API calls.
- [Coil](https://coil-kt.github.io/coil/) - For image loading.
- [Hilt](https://dagger.dev/hilt/) - For dependency injection.
- [Kotlin Coroutines](https://kotlinlang.org/docs/coroutines-overview.html) - For managing asynchronous tasks.

## Screenshots

![Home Screen](https://via.placeholder.com/400x800?text=Home+Screen)
![Weather Details](https://via.placeholder.com/400x800?text=Weather+Details)

## Best Practices Followed

- **Separation of Concerns**: Clear distinction between UI and data handling.
- **Reactive Streams**: Used StateFlow/LiveData for reactive UI updates.
- **Dependency Injection**: Managed with Hilt for clean and testable code.
- **Error Handling**: Graceful error handling for network calls.
- **Modularization**: Structured code into distinct modules and packages.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Submit a pull request.


## Contact

For any queries or issues, feel free to contact me:

- **Email**: arifewucse2016@gmail.com
- **GitHub**: https://github.com/Ariful2016/Weather-App-Compose.git
