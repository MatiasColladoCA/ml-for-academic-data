FROM apache/airflow:2.9.2

USER airflow
RUN pip install --no-cache-dir scikit-learn

COPY requirements.txt /
RUN pip install --no-cache-dir -r /requirements.txt

USER airflow
