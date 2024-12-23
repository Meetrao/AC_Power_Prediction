# AC Power Prediction

This project was developed during a Machine Learning workshop to predict Alternating Current (AC) power generation based on weather conditions and solar panel performance data. It demonstrates the application of data preprocessing, visualization, and machine learning techniques.

## Project Structure

1. **Datasets**
   - `Weather_Sensor_Data.csv`: Contains data on environmental and module conditions like temperature and solar irradiation.
   - `Generation_Data.csv`: Contains data on DC power generation, AC power conversion, and energy yields.

2. **Jupyter Notebook**
   - `AC_Power_Prediction.ipynb`: Processes data, visualizes trends, and trains predictive models using libraries such as `pandas`, `scikit-learn`, and `matplotlib`.

## Dataset Details

### Weather Sensor Data
| Column               | Description                    |
|----------------------|--------------------------------|
| `DATE_TIME`          | Timestamp of data recording   |
| `PLANT_ID`           | Unique identifier for the plant |
| `SOURCE_KEY`         | Data source identifier        |
| `AMBIENT_TEMPERATURE`| Ambient temperature in °C     |
| `MODULE_TEMPERATURE` | Temperature of solar module in °C |
| `IRRADIATION`        | Solar irradiation levels      |

### Generation Data
| Column       | Description                         |
|--------------|-------------------------------------|
| `DATE_TIME`  | Timestamp of data recording         |
| `PLANT_ID`   | Unique identifier for the plant     |
| `SOURCE_KEY` | Data source identifier             |
| `DC_POWER`   | Direct Current power generation (kW)|
| `AC_POWER`   | Alternating Current power conversion (kW) |
| `DAILY_YIELD`| Energy generated in the day (kWh)  |
| `TOTAL_YIELD`| Total energy generated (kWh)       |

## Features of the Notebook
- **Data Preprocessing**: Converts categorical variables to numerical forms and handles missing data.
- **Exploratory Data Analysis**: Visualizes data trends and relationships.
- **Machine Learning**:
  - Splits the data into training and testing sets.
  - Trains models such as Linear Regression.
  - Evaluates model performance using metrics like R².

## Workshop Highlights
This project was designed to:
- Teach participants how to handle real-world datasets.
- Introduce best practices in machine learning workflows.
- Demonstrate the use of Python libraries like `pandas`, `numpy`, and `scikit-learn` in predictive modeling.

## Requirements
- Python 3.x
- Libraries: 
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

## Usage
1. Clone this repository and navigate to the project directory.
2. Install the required dependencies: `pip install -r requirements.txt`.
3. Run the notebook `AC_Power_Prediction.ipynb` to preprocess the data and train the model.
4. Use the trained model to predict AC power based on new weather sensor data.

## Results
The project provides insights into factors affecting power generation and creates a predictive model for future energy outputs based on weather conditions.

## License
This project is licensed under the MIT License.

Let me know if there’s anything else you’d like to include!
