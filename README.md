HushURL: Covert Channel Communication through URL Shorteners via Short Message Service (SMS)

Sam Mason, Rebecca Mattie, Patrick Sacchet, and Dustin Spencer
Johns Hopkins University, Whiting School of Engineering, Maryland, US
22 August 2023

HushURL

HushURL is an innovative Android application designed to enable covert communication through URL shorteners using the Short Message Service (SMS). Developed by a team of researchers and engineers from Johns Hopkins University's Whiting School of Engineering, HushURL showcases the unique capability of sending and receiving SMS messages while leveraging the inherent anonymity of URL shorteners. This cutting-edge technology opens up new possibilities for discreet information exchange.

Key Features

- **Covert Communication:** HushURL facilitates hidden communication by embedding messages within SMS messages sent via URL shorteners.
- **Message Metadata Display:** The application offers comprehensive message metadata, including originating address, timestamp, protocol, and display originating address.
- **User-Friendly Interface:** With a simple and intuitive interface, users can seamlessly engage in covert communication without the need for advanced technical skills.

Prerequisites

To utilize HushURL, you need an Android device or emulator running Android OS version X.X or higher.

Permissions:

- **android.permission.RECEIVE_SMS:** Required to receive incoming SMS messages.
- **android.permission.SEND_SMS:** Required to send SMS messages.

Please note that it is recommended to use Android API 30 or earlier for virtual Android devices, as newer versions might not handle SMS routing correctly.

Installation

Follow these steps to set up HushURL:

1. Clone the repository or download the source code.
2. Open the project in Android Studio.
3. Build and run the application on your Android device or emulator.

Usage

Engage in covert communication effortlessly using HushURL:

1. Launch the HushURL App on your Android device or emulator.
2. Grant the necessary permissions (RECEIVE_SMS and SEND_SMS) when prompted.
3. On the main screen, input the recipient's phone number and the intended message in the provided fields.
4. Tap the "Send" button to transmit the encrypted SMS message.
5. The application's interface will display essential message metadata, including originating address, timestamp, protocol, and display originating address.
6. If an SMS message is received while the app is active, the incoming message's metadata will be shown within the app.

Known Bugs

- **Permission Issue:** There is a known bug related to permission checking, which might require you to open, close, and then re-open the app on a real device to successfully send SMS messages. If you encounter the "SMS failed to send" error message, attempt closing and re-opening the app.

Contributing

HushURL warmly welcomes contributions from the community. If you wish to enhance the project, please adhere to these guidelines:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Apply your changes and commit them to your branch.
4. Push your changes to your forked repository.
5. Submit a pull request along with a detailed description of your modifications.

License

HushURL operates under the open-source MIT License, allowing for widespread utilization and modification.

Acknowledgments

HushURL owes its existence to the dedicated work within Android Studio and the utilization of the Android SDK for SMS message handling.

Contact

For inquiries, issues, or feedback, feel free to reach out to Dustin Spencer via email: dspenc18@jhu.edu.
