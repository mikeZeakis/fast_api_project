open terminal and create the virtul environment as below:
python -m venv venv-name
Activate venv using venv-name\Scripts\activate

Install Libraries:
pip install pandas
pip install numpy
pip install sklearn
pip install pickle
pip install FastAPI
pip install requests

Run server:
uvicorn main:app --reload