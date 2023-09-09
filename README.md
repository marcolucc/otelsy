# otelsy

Otelsy is a platform that simplifies the hotel check-in and room access process for guests and hotel staff. It uses QR codes to identify and authenticate guests, and to unlock their room doors. It also integrates with the main management software for hotels, to streamline the booking and billing operations.

## Features

- **Fast and easy check-in**: Guests can check in to any hotel that uses Otelsy by scanning their QR code at the reception. No need to fill out forms, show ID, or wait in line.
- **Secure and dynamic QR codes**: Each guest is assigned a unique and dynamic QR code, which changes every time using rolling code technology and has an expiration time. This ensures that the QR codes are secure and reliable, and cannot be copied or reused by unauthorized parties.
- **Seamless room access**: Guests can unlock their room doors by scanning their QR code at the door lock. No need to carry keys or cards, or worry about losing them.
- **Integration with hotel management software**: Otelsy integrates with the main management software for hotels, such as Opera, Protel, or Cloudbeds. This allows hotel staff to manage bookings, payments, and guest profiles from a single interface.

## How it works

Otelsy consists of three main components:

- **Otelsy app**: This is the mobile app that guests use to generate their QR codes and access their room details. The app is available for both iOS and Android devices.
- **Otelsy server**: This is the backend server that handles the communication between the app, the hotel management software, and the door lock system. The server is hosted on AWS.
- **Otelsy lock**: This is the hardware device that recognizes the QR codes and grants access to the rooms. The lock is compatible with most standard hotel door locks and uses Arduino, Ethernet shield, and SIM shield.

## Installation

To install Otelsy on your hotel, you need to follow these steps:

- **Register your hotel**: Contact us to register your hotel and get your API key and secret.
- **Install the Otelsy lock**: Install the Otelsy lock on each room door that you want to enable for Otelsy. Connect the lock to your hotel's Wi-Fi network and configure it with your API key and secret.
- **Integrate with your hotel management software**: Integrate your hotel management software with the Otelsy server using our RESTful API. You can find the API documentation here.
- **Promote Otelsy to your guests**: Encourage your guests to download the Otelsy app from the App Store or Google Play and use it for their next stay.

## License

Otelsy is licensed under the MIT License. You are free to use, modify, and distribute it as long as you give credit to the original author.