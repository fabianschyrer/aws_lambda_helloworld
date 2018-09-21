# aws_lambda_helloworld
AWS Lambda Hello World test using AWS SAM Local

git clone https://github.com/boto/boto3.git <br />
cd boto3 <br />
virtualenv /Users/fabian/virtualenv/boto3 <br />
. /Users/fabian/virtualenv/boto3/bin/activate <br />
pip install -r requirements.txt <br />
pip install -e . <br />

pip install -r requirements-docs.txt <br />
cd docs <br />
make html <br />

npm install -g aws-sam-local <br />
sam --version <br />
npm update -g aws-sam-local <br />

sam local start-lambda <br />
python3 lambda_function.py <br />
