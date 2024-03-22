
# Gemini Health App

The Gemini Health App is a web application built with Streamlit and integrates the Google Gemini Pro Vision API to analyze food items from images and calculate their total calorie content. It provides detailed insights into the calorie count of individual food items and offers nutritional advice.

## Features

- **Image Upload**: Users can upload images of food items to be analyzed.
- **Calorie Calculation**: The app calculates the total calories of the food items in the image.
- **Detailed Breakdown**: Provides a detailed breakdown of calories for each food item.
- **Nutritional Insights**: Offers insights into the healthiness of the food items and their nutritional content.

## Installation

To run the Gemini Health App, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/gemini-health-app.git
   ```
2. Navigate to the project directory:
   ```bash
   cd gemini-health-app
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

Start the application with Streamlit:

```bash
streamlit run app.py
```

Access the web interface by navigating to `http://localhost:8501` in your web browser.

## How It Works

1. **Enter Prompt**: Users provide a prompt to guide the analysis.
2. **Upload Image**: Users upload an image of the food items to be analyzed.
3. **Analysis**: Upon clicking the "Tell me the total calories" button, the app processes the image and the input prompt, sending them to the Google Gemini Pro Vision API.
4. **Results**: The app displays the total calorie count along with a detailed breakdown for each food item.

## Configuration

Ensure you have the following environment variable set in your `.env` file:

```plaintext
GOOGLE_API_KEY=your_api_key_here
```

The app uses this key to authenticate with the Google Gemini Pro Vision API.

## Contributing

Contributions are welcome! Please fork the repository and submit pull requests with your suggested changes.
