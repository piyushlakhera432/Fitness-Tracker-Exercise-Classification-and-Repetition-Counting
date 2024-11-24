 ## Fitness Tracker: Exercise Classification and Repetition Counting ##


Overview

This project demonstrates the development of a fitness tracker that classifies exercises and counts repetitions using accelerometer and gyroscope sensor data. The model achieves high accuracy by leveraging advanced data processing, feature engineering, and predictive modeling techniques. The project is aimed at beginners to intermediate learners in data science and machine learning, providing a hands-on introduction to working with sensor data.


Features

 Exercise Classification: Classifies exercises such as squats, deadlifts, bench presses, and more, with up to 99% accuracy.
 Repetition Counting: Accurately counts repetitions using custom algorithms based on peak detection in sensor data.
 Data Processing and Visualization: Processes raw sensor data into actionable features and visualizes unique exercise patterns.
 Feature Engineering: Implements techniques such as noise filtering, Principal Component Analysis (PCA), and temporal abstraction.
 Outlier Detection: Ensures data integrity using methods like Interquartile Range (IQR) and Local Outlier Factor (LOF).

 
Project Structure

Data Collection-   Raw accelerometer and gyroscope data collected from wrist sensors during gym exercises.
Data Preprocessing- Merging, resampling, and transforming raw sensor data for supervised learning.
                  -Handling missing values and outliers to improve model reliability.
Feature Engineering- Applying low-pass filtering and PCA to enhance feature quality.
                   -Temporal and frequency-based abstraction for advanced insights.
Predictive Modeling- Training machine learning models for exercise classification.
                   - Hyperparameter tuning using grid search to optimize performance.
Repetition Counting- Developing custom algorithms to detect and count exercise repetitions.



Installation

Clone this repository:
bash

Copy code
git clone https://github.com/your-username/fitness-tracker.git  
cd fitness-tracker  


Create and activate a virtual environment:
bash
Copy code
conda create -n fitness-tracker python=3.9  
conda activate fitness-tracker  


Install the required dependencies:
bash
Copy code
pip install -r requirements.txt  

Download and place the dataset in the data/ folder as instructed in the project directory.


Usage

Data Preprocessing: Use the scripts in the preprocessing/ folder to clean and prepare the data for analysis.
Feature Engineering: Run the feature_engineering.py script to extract relevant features.
Model Training: Execute train_model.py to train and evaluate classification models.
Repetition Counting: Use count_reps.py to test the repetition counting algorithm on sample data.


Results

Achieved 99% classification accuracy across multiple exercises.
Repetition counting algorithm demonstrates a low mean absolute error across datasets.


Technologies Used

Programming Language: Python
Libraries: pandas, NumPy, scikit-learn, Matplotlib, Seaborn
Environment: Conda, Visual Studio Code


Future Enhancements

Integration with real-time tracking devices like fitness bands and smartwatches.
Deployment of the model in mobile or web applications.
Expanding to include more complex exercises and tracking metrics such as speed and power.


Contributing

Contributions are welcome! Feel free to fork this repository, make changes, and submit a pull request.


License

This project is licensed under the MIT License. See the LICENSE file for details.


Acknowledgments
Inspired by the Quantified Self movement and real-world gym data.
Special thanks to contributors who participated in data collection and project design.



 
