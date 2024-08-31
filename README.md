Bitcoin Ticker Flutter App

This Flutter application provides real-time exchange rates of various cryptocurrencies, such as Bitcoin (BTC), Ethereum (ETH), and Litecoin (LTC), against different fiat currencies (e.g., USD, EUR, AUD). The app is designed to be cross-platform, with specific UI adaptations for Android and iOS, ensuring a great user experience on both platforms.


Installation Instructions
To get the app up and running on your local machine, follow these steps:

1. Clone the Repository
First, clone the repository to your local machine:

git clone https://github.com/your-username/bitcoin-ticker-flutter.git
cd bitcoin-ticker-flutter

2. Install Flutter Dependencies
Next, you'll need to install the dependencies listed in the pubspec.yaml file. Flutter manages these dependencies using the flutter pub get command. Run the following command in your terminal:

flutter pub get

This command will automatically download and install all the necessary packages specified in the pubspec.yaml file.

3. Set Up Environment Variables
Create a .env file in the root directory of your project. This file will contain sensitive information like your API key. Use the following format:

COIN_API_KEY=your_api_key_here
BASE_URL=https://rest.coinapi.io/v1/exchangerate
Replace your_api_key_here with your actual API key from CoinAPI.

4. Run the Application
With all dependencies installed and environment variables configured, you can run the application using:

flutter run