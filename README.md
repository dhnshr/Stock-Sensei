# Stock Sensei
This is a Flask application that allows users to perform two main functions related to stock analysis: plotting candlestick graphs and finding patterns in a list of stocks. This application has not been deployed yet and can be run locally on your machine.
## Features
The Flask Stock Analysis Application provides the following features:

1. Candlestick Graph Plotting: Users can visualize the historical price data of a stock using candlestick graphs. Candlestick graphs provide information about the      opening, closing, highest, and lowest prices for a given time period.

2. Pattern Detection: Users can input a list of stocks, and the application will analyze the data to detect any patterns. These patterns could include trends,          reversals, or specific chart patterns like head and shoulders, double tops, etc.

## Installation
To run the Flask Stock Analysis Application locally, follow the steps below:/

1. Clone the repository:
    ```bash
    git clone https://github.com/Ace-9136/flask_app
    
2. Change to the project directory:
    ```bash
    cd flask-app

3. Set up a virtual environment (recommended):
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    
4. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
5. Install the technical analysis library:\
        [Click here](https://blog.quantinsti.com/install-ta-lib-python/) for guide to download TA-lib.

6. Start the Flask application:
    ```bash
    python app.py

7. Open your browser and navigate to http://localhost:5000 to access the application.
## Usage
Once you have the Flask application running, you can access the following endpoints:

* Candlestick Graph Plotting: To plot a candlestick graph, navigate to http://localhost:5000/ in your browser. Select the company name from the dropdown menu and click the submit button. This will redirect you to a new page on which the graph on the selected company is displayed for the duration of approx 1 year.

* Pattern Detection: To find patterns in a list of stocks, go to http://localhost:5000/screener in your browser. Input the name of pattern from the dropdown and click scan button. This will get you the name of companies in which the pattern has been found within last 10 days.
## Contributing
Contributions are welcome! If you encounter any issues or have suggestions for improvements, please submit an issue or a pull request.

## License
This project is licensed under the MIT License.
