# Uber Car Fare Prediction 🚖

Welcome to the Uber Car Fare Prediction repository! 🚀

This repository contains the code and resources for predicting Uber ride fares using machine learning algorithms. The project was developed during my AI & ML internship and demonstrates the application of various data science techniques to a real-world problem.

## Repository Structure

All components of the project are organized as follows:

- **`data/`**: Contains the dataset used for training and testing the model.
  - `cab_rides.csv`: The main dataset used for predictions.
- **`models/`**: Includes the trained machine learning model.
  - `model.pkl`: The trained model file.
- **`templates/`**: Holds the HTML files used in the Flask web application.
  - `index.html`: The main HTML template for the web interface.
- **`static/images/`**: Contains images used in the web interface.
  - `book.jpg`, `c1.jpg`, `c2.jpg`, `pic.jpg`: Images used in the web interface.
- **`Algorithms.ipynb`**: Jupyter Notebook containing the core project code and analysis.
- **`app.py`**: The Flask application script that runs the web interface for fare predictions.
- **`requirements.txt`**: List of dependencies required to run the project.
- **`README.md`**: Project overview and instructions (this file).
- **`LICENSE`**: The project license.

## Features

- **Machine Learning Model**: Utilizes algorithms to predict Uber fares based on historical data.
- **Flask Web Interface**: A user-friendly web interface built with Flask to input ride details and receive fare predictions.
- **Data-Driven Approach**: The model is trained on a real-world dataset to ensure accuracy and reliability.
- **Well-Organized Structure**: The project is neatly organized into directories, making it easy to navigate and understand.

## How to Use

1. **Clone the Repository**: Clone this repository to your local machine using the following command:
    ```bash
    git clone https://github.com/VangaLasyaSri/Uber_Car_Fare_Prediction.git
    ```

2. **Set Up the Environment**: Navigate to the project directory and create a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On macOS/Linux
    venv\Scripts\activate  # On Windows
    ```

3. **Install Dependencies**: Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Flask Application**: Start the Flask app to interact with the model through a web interface:
    ```bash
    python app.py
    ```

5. **Access the Web Interface**: Open your browser and go to `http://localhost:5000` to use the fare prediction tool.

## Contributing

If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request. Contributions are always welcome!

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

This project was developed during my AI & ML internship, and I would like to thank all the mentors and peers who supported and guided me throughout the process.

Feel free to use this project to understand or explore machine learning applications. Happy coding! 🎉
