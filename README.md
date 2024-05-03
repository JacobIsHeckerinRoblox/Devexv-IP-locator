# Devexv's IP locator

## Overview
The IP Locator is a console application written in C# that allows users to input an IP address and retrieves its geolocation information using the IPInfo.io API. It displays details such as city, region, country, coordinates, postal code, and ASN (Autonomous System Number). Additionally, it provides a Google Maps link for the exact location.

## Prerequisites
- .NET Core SDK
- Newtonsoft.Json package (installed via NuGet)

## Usage
1. Clone the repository to your local machine.
2. Open the solution in your preferred C# IDE.
3. Build the solution to restore dependencies.
4. Run the application.
5. Enter the target IP address when prompted.
6. The application will fetch and display the geolocation information.
7. Press any key to close the application.

## Dependencies
- Newtonsoft.Json: This library is used for deserializing JSON responses from the IPInfo.io API.

## Notes
- This application utilizes the IPInfo.io API to retrieve geolocation information. Ensure you have a stable internet connection to fetch the data.
- Error handling is implemented to handle cases where the IP address is invalid or the API request fails.

# Made with C# 12 .NET 8.0

# The owner doesn't take any responsibility

# If you are aware of virus you can check it through dnSpy : https://github.com/dnSpy/dnSpy/releases/tag/v6.1.8
