# ML-Model-API

Simple API from a machine learning model in Python using Flask.

## References

This project is based on the tutorial from DataCamp:  
[Turning Machine Learning Models into APIs in Python](https://www.datacamp.com/tutorial/machine-learning-models-api-python)

## Installation and Running the Application

Follow these steps to install and run the application:

1. Clone the repository from GitHub

   ```bash
   git clone https://github.com/xNatthapol/ML-Model-API.git
   ```

2. Navigate to the project directory

   ```bash
   cd ML-Model-API
   ```

3. Create a Virtual Environment

   ```bash
   python -m venv venv
   ```

4. Activate the Virtual Environment

- On MacOS or Linux
  ```bash
  source venv/bin/activate
  ```
- On Windows
  ```cmd
  venv\Scripts\activate
  ```

5. Install dependencies

   ```bash
   pip install -r requirements.txt
   ```

6. Run the API

   Run the `model.py` first

   ```bash
   python model.py
   ```

   And then run the `api.py`

   ```bash
   python api.py
   ```
