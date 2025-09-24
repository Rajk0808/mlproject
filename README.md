<<<<<<< HEAD
# END to END machine learning project
=======
## End to End Data Sciene Project

import dagshub
dagshub.init(repo_owner='Rajk0808', repo_name='mlproject', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)