#Initial steps and Setup from scratch:
>npm init -f
>npm install --save-dev serverless-wsgi serverless-python-requirements
>virtualenv venv --python=python3
>source venv/bin/activate
>pip install flask
>pip freeze > requirements.txt

#Adding DB Layer
>pip install boto3
>pip freeze > requirements.txt
>npm install --save-dev serverless-dynamodb-local