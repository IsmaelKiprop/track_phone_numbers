# Phone Number Location Finder

This Python script allows you to enter a phone number with a country code, and it will provide you with information about the phone number, including its location, service provider, and display its location on an interactive map.

## Prerequisites

Before running the script, make sure you have the following dependencies installed:

- `phonenumbers`: A Python library for working with phone numbers. You can install it using `pip`:

  ```bash
  pip install phonenumbers

### folium: A Python library for creating interactive maps. You can install it using pip:

pip install folium

### opencagegeocode: A Python library for geocoding. You can install it using pip:

pip install opencagegeocode

### Usage

Run the script by executing python your_script_name.py in your terminal.

You will be prompted to enter a phone number with a country code.

The script will then:

Parse the phone number.
Determine the country where the phone number is registered.
Identify the service provider (carrier) for the phone number.
Fetch the location (latitude and longitude) of the country using geocoding.
Display the location on an interactive map.
The map will be saved as an HTML file named "location.html" in the project directory.

### Configuration

To configure the script for your needs, you can update the key variable with your own API key for geocoding. Replace "YOUR_API_KEY" with your actual API key.

key = "YOUR_API_KEY"

### Acknowledgments

This project uses the phonenumbers library for phone number parsing.
It utilizes the folium library for creating interactive maps.
Geocoding is performed using the opencagegeocode library.