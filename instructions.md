# Module 11: Play-by-Play Weather
Your task this week is to complete a Weather Forecast API that retrieves a five-day weather forecast for a city using the OpenAI API. The forecast should be written in the style of a sports announcer and returned as a JSON response.
This task is optional. To complete it, you’ll need an OpenAI API key, which may have associated costs. For more details on getting an API key, check the Full-Stack Blog's OpenAI Account Setup Guide.
Starter code for the Weather Forecast API has been provided. Your job is to complete it and integrate the OpenAI API.
Before starting, download and unzip the starter code files and create your own repository.

# User Story:
- As a traveler, I want to see a five-day weather forecast for a city in the style of a sports announcer so I can plan a trip.

# Acceptance Criteria:
- When I search for a city, I receive a five-day weather forecast for that city in the style of a sports announcer.

# Example Input:
json
{
  "location": "Sacramento CA"
}

# Example Output:
json
{
  "result": {
    "day1": "And here we go, folks! Day one in Sacramento is looking like a scorcher with a high of 95 degrees and clear skies. It's going to be a hot one out there!",
    "day2": "Moving on to day two, we've got a slight cool down with a high of 90 degrees and a chance of some afternoon showers. It's going to be a nail-biter to see if the rain holds off for the big game!",
    "day3": "Day three is shaping up to be a beautiful day in Sacramento with a high of 85 degrees and sunny skies. Perfect weather for a day out on the golf course or a picnic in the park!",
    "day4": "As we head into day four, temperatures are on the rise again with a high of 92 degrees and mostly sunny conditions. It's going to be a real sizzler out there on the field!",
    "day5": "And finally, on day five, we're looking at a high of 88 degrees with a mix of sun and clouds. It's going to be a thrilling end to the week as we see if the weather holds up for the big championship game!"
  }
}

# Steps to Complete:
1. Edit the server.ts file to complete the Weather Forecast API.
2. Follow the TODO comments to fill in missing code.
3. Add your OpenAI API key in a .env file.
4. Use Insomnia to test the API.
The POST /forecast endpoint should accept a request body with a location, call the OpenAI API to generate a five-day forecast in a sports announcer style, and return the result in JSON format.
This task is optional and ungraded. You can customize it, such as using a different style for the forecast, like a cartoon character or a famous artist.
If you want, you can compare your code to a provided solution near the end of Module 12 by asking your instructor. Keep in mind that the solution is just one possible approach.

