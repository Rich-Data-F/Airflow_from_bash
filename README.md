readme.md

# installation of Airflow from bash (or WSL under Windows) terminal
# mkdir airflowtuto && cd airflowtuto (or whatever name)
# python3 -m venv venv
# source venv/bin/activate
# export AIRFLOW_HOME=$(pwd)
# AIRFLOW_VERSION=2.9.3
# PYTHON_VERSION="$(python --version | cut -d " " -f 2 | cut -d "." -f 1-2)"
# (or manually enter PYTHON_VERSION=X.Y - python -- version et garder 3.8 ou 3.9 ou 3.10)
# CONSTRAINT_URL="[https://raw.githubusercontent.com/apache/airflow/constraints-${AIRFLOW_VERSION}/constraints-${PYTHON_VERSION}.txt](https://raw.githubusercontent.com/apache/airflow/constraints-$%7BAIRFLOW_VERSION%7D/constraints-$%7BPYTHON_VERSION%7D.txt)"
# pip install "apache-airflow==${AIRFLOW_VERSION}" --constraint "${CONSTRAINT_URL}"

# post installation, run:
# airflow standalone
