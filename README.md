# Machine Learning Web App

Machine Learning is a fascinating field of computer science. Models are created to mimic human behaviour and assist people with various tasks, making life easier and work faster. However, these models in their base form aren't quite as user-friendly because the average person doesn't know their way around these things. 

To address this, I have extended a lesson from Microsoft's `Machine Learning for beginners` course to build a web app that embeds a machine learning model to make predictions on `where a UFO was likely seen`.

## Project Overview

In this project, we built our model with a dataset from the `The National UFO Reporting Center (NUFORC)` based on UFO sightings of over 70,000 records. The model uses the following features: `Longitude`, `Latitude`, and time in `Seconds` to predict the most likely `Country` where a UFO was seen.

The model was pickled so it can be deserialized for use on the web. We then built the frontend with Flask, a lightweight and popular web framework for Python. The web app serves as an interface for users to interact with the machine learning model trained in the course. We set up API routes to send our inputs into the model to receive our prediction.

## Demo

For a full demo of how this works, please visit the link below: ml-web-app.com

## How to Run the App Locally

1. Clone the repository: `git clone https://github.com/yourusername/your-repository-name.git`
2. Navigate to the project directory: `cd your-repository-name`
3. Install the required packages: `pip install -r requirements.txt`
4. Run the app: `python app.py`
5. Open your web browser and go to `http://localhost:5000`
