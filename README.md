# Can Computers Think?

This repository contains all project files relating to NLP/NLU implementations developed for the Can Computers Think project.

## Projects

Simple Sentiment Analysis using Spacy/Sklearn on Amazon and Yelp reviews. (Outdated)

Intermediate Sentiment Analysis using Spacy/Sklearn on Imdb Reviews.

Complex Sentiment Analysis using Spacy/Sklearn on 1.6 million twitter posts.

## Requirements

### Prerequisites

Python version 3.7.1

### Sentiment Analysis Projects Setup + Execution

Step 1 : Run `pip install -r requirements.txt` from the base directory. (ie C:\CanComputersThink\)

Step 2 : Run `python <filename>` from the base directory. (ie `python intermediate_sentiment_analysis_twitter.py`)

### Rasa NLU/NLP Projects Setup + Execution

Step 1 : Run `pip install -r requirements.txt` from the RasaNLU directory. (ie C:\CanComputersThink\RasaNLU\)

Step 2 : Run `rasa run actions` from the RasaNLU directory. (ie `rasa run actions`)

Step 3 : Run `rasa shell --endpoints endpoints.yaml` from the RasaNLU directory. (ie `rasa shell --endpoints endpoints.yaml`)

## Packages Used (Sentiment Analysis)

absl-py==0.9.0

aiofiles==0.4.0

aiohttp==3.6.2

APScheduler==3.6.3

astor==0.8.1

astroid==2.3.3

async-generator==1.10

async-timeout==3.0.1

attrs==19.3.0

Automat==0.8.0

backcall==0.1.0

blis==0.4.1

boto3==1.12.0

botocore==1.15.0

bz2file==0.98

cachetools==4.0.0

catalogue==1.0.0

certifi==2019.11.28

cffi==1.14.0

chardet==3.0.4

Click==7.0

cloudpickle==0.6.1

colorama==0.4.3

colorclass==2.2.0

coloredlogs==10.0

colorhash==1.0.2

ConfigArgParse==1.0

constantly==15.1.0

cryptography==2.8

cycler==0.10.0

cymem==2.0.3

decorator==4.4.1

dill==0.3.1.1

dnspython==1.16.0

docopt==0.6.2

docutils==0.15.2

dopamine-rl==3.0.1

en-core-web-sm==2.2.5

fbmessenger==6.0.0

Flask==1.1.1

future==0.17.1

gast==0.2.2

gevent==1.4.0

gin-config==0.3.0

google-api-python-client==1.7.11

google-auth==1.11.0

google-auth-httplib2==0.0.3

google-auth-oauthlib==0.4.1

google-pasta==0.1.8

googleapis-common-protos==1.51.0

greenlet==0.4.15

grpcio==1.26.0

gunicorn==20.0.4

gym==0.16.0

h11==0.8.1

h2==3.2.0

h5py==2.10.0

hpack==3.0.0

httpcore==0.3.0

httplib2==0.17.0

httptools==0.1.1

humanfriendly==7.0

hyperframe==5.2.0

hyperlink==19.0.0

idna==2.8

importlib-metadata==1.4.0

incremental==17.5.0

ipython==7.12.0

ipython-genutils==0.2.0

isort==4.3.21

itsdangerous==1.1.0

jedi==0.16.0

Jinja2==2.11.1

jmespath==0.9.4

joblib==0.14.1

jsonpickle==1.3

jsonschema==2.6.0

Keras==2.3.1

Keras-Applications==1.0.8

Keras-Preprocessing==1.1.0

kfac==0.2.0

kiwisolver==1.1.0

klein==17.10.0

lazy-object-proxy==1.4.3

Markdown==3.1.1

MarkupSafe==1.1.1

matplotlib==2.2.5

mattermostwrapper==2.1

mccabe==0.6.1

mesh-tensorflow==0.1.9

mpmath==1.1.0

multidict==4.6.1

murmurhash==1.0.2

networkx==2.4

nltk==3.4.5

numpy==1.18.1

oauth2client==4.1.3

oauthlib==3.1.0

opencv-python==4.1.2.30

opt-einsum==3.1.0

packaging==18.0

pandas==1.0.0

parso==0.6.0

pickleshare==0.7.5

pika==1.0.1

Pillow==7.0.0

plac==1.1.3

preshed==3.0.2

promise==2.3

prompt-toolkit==2.0.10

protobuf==3.11.2

pyasn1==0.4.8

pyasn1-modules==0.2.8

pycparser==2.19

pydot==1.4.1

pyglet==1.4.10

Pygments==2.5.2

PyHamcrest==2.0.0

PyJWT==1.7.1

pykwalify==1.7.0

pylint==2.4.4

pymongo==3.10.1

pyparsing==2.4.6

pypng==0.0.20

pyreadline==2.1

pyrsistent==0.15.7

python-crfsuite==0.9.6

python-dateutil==2.8.1

python-engineio==3.11.2

python-socketio==4.4.0

python-telegram-bot==11.1.0

pytz==2019.3

PyYAML==5.3

questionary==1.5.1

rasa==1.7.2

rasa-nlu==0.15.1

rasa-sdk==1.7.0

redis==3.3.11

requests==2.22.0

requests-async==0.5.0

requests-oauthlib==1.3.0

requests-toolbelt==0.9.1

rfc3986==1.3.2

rocketchat-API==0.6.36

rsa==4.0

ruamel.yaml==0.15.100

s3transfer==0.3.3

sanic==19.9.0

Sanic-Cors==0.9.9.post1

sanic-jwt==1.4.0

Sanic-Plugins-Framework==0.8.2.post1

scikit-learn==0.20.4

scipy==1.4.1

simplejson==3.17.0

six==1.14.0

sklearn-crfsuite==0.3.6

slackclient==1.3.2

spacy==2.2.3

spacy-lookups-data==0.2.0

SQLAlchemy==1.3.13

srsly==1.0.1

sympy==1.5.1

tabulate==0.8.6

tensor2tensor==1.14.1

tensorboard==1.14.0

tensorflow==1.14.0

tensorflow-cpu==1.15.0

tensorflow-cpu-estimator==1.15.1

tensorflow-datasets==2.0.0

tensorflow-estimator==1.14.0

tensorflow-gan==2.0.0

tensorflow-hub==0.7.0

tensorflow-metadata==0.21.1

tensorflow-probability==0.7.0

termcolor==1.1.0

terminaltables==3.1.0

textblob==0.15.3

tflearn==0.3.2

thinc==7.3.1

tqdm==4.42.0

traitlets==4.3.3

twilio==6.35.4

Twisted==19.10.0

typed-ast==1.4.1

typing==3.7.4.1

tzlocal==2.0.0

uritemplate==3.0.1

urllib3==1.25.8

wasabi==0.6.0

wcwidth==0.1.8

webexteamssdk==1.2

websocket-client==0.54.0

websockets==8.1

Werkzeug==0.16.1

wrapt==1.11.2

xgboost==0.90

yarl==1.4.2

zipp==2.1.0

zope.interface==4.7.1


## Packages Used (Rasa NLU)

absl-py==0.9.0

aiofiles==0.4.0

aiohttp==3.6.2

APScheduler==3.6.3

astor==0.8.1

astroid==2.3.3

async-generator==1.10

async-timeout==3.0.1

attrs==19.3.0

Automat==0.8.0

backcall==0.1.0

blis==0.4.1

boto3==1.12.0

botocore==1.15.0

bz2file==0.98

cachetools==4.0.0

catalogue==1.0.0

certifi==2019.11.28

cffi==1.14.0

chardet==3.0.4

Click==7.0

cloudpickle==0.6.1

colorama==0.4.3

colorclass==2.2.0

coloredlogs==10.0

colorhash==1.0.2

ConfigArgParse==1.0

constantly==15.1.0

cryptography==2.8

cycler==0.10.0

cymem==2.0.3

decorator==4.4.1

dill==0.3.1.1

dnspython==1.16.0

docopt==0.6.2

docutils==0.15.2

dopamine-rl==3.0.1

en-core-web-sm==2.2.5

fbmessenger==6.0.0

Flask==1.1.1

future==0.17.1

gast==0.2.2

gevent==1.4.0

gin-config==0.3.0

google-api-python-client==1.7.11

google-auth==1.11.0

google-auth-httplib2==0.0.3

google-auth-oauthlib==0.4.1

google-pasta==0.1.8

googleapis-common-protos==1.51.0

greenlet==0.4.15

grpcio==1.26.0

gunicorn==20.0.4

gym==0.16.0

h11==0.8.1

h2==3.2.0

h5py==2.10.0

hpack==3.0.0

httpcore==0.3.0

httplib2==0.17.0

httptools==0.1.1

humanfriendly==7.0

hyperframe==5.2.0

hyperlink==19.0.0

idna==2.8

importlib-metadata==1.4.0

incremental==17.5.0

ipython==7.12.0

ipython-genutils==0.2.0

isort==4.3.21

itsdangerous==1.1.0

jedi==0.16.0

Jinja2==2.11.1

jmespath==0.9.4

joblib==0.14.1

jsonpickle==1.3

jsonschema==2.6.0

Keras==2.3.1

Keras-Applications==1.0.8

Keras-Preprocessing==1.1.0

kfac==0.2.0

kiwisolver==1.1.0

klein==17.10.0

lazy-object-proxy==1.4.3

Markdown==3.1.1

MarkupSafe==1.1.1

matplotlib==2.2.5

mattermostwrapper==2.1

mccabe==0.6.1

mesh-tensorflow==0.1.9

mpmath==1.1.0

multidict==4.6.1

murmurhash==1.0.2

networkx==2.4

nltk==3.4.5

numpy==1.18.1

oauth2client==4.1.3

oauthlib==3.1.0

opencv-python==4.1.2.30

opt-einsum==3.1.0

packaging==18.0

pandas==1.0.0

parso==0.6.0

pickleshare==0.7.5

pika==1.0.1

Pillow==7.0.0

plac==1.1.3

preshed==3.0.2

promise==2.3

prompt-toolkit==2.0.10

protobuf==3.11.2

pyasn1==0.4.8

pyasn1-modules==0.2.8

pycparser==2.19

pydot==1.4.1

pyglet==1.4.10

Pygments==2.5.2

PyHamcrest==2.0.0

PyJWT==1.7.1

pykwalify==1.7.0

pylint==2.4.4

pymongo==3.10.1

pyparsing==2.4.6

pypng==0.0.20

pyreadline==2.1

pyrsistent==0.15.7

python-crfsuite==0.9.6

python-dateutil==2.8.1

python-engineio==3.11.2

python-socketio==4.4.0

python-telegram-bot==11.1.0

pytz==2019.3

PyYAML==5.3

questionary==1.5.1

rasa==1.7.2

rasa-nlu==0.15.1

rasa-sdk==1.7.0

redis==3.3.11

requests==2.22.0

requests-async==0.5.0

requests-oauthlib==1.3.0

requests-toolbelt==0.9.1

rfc3986==1.3.2

rocketchat-API==0.6.36

rsa==4.0

ruamel.yaml==0.15.100

s3transfer==0.3.3

sanic==19.9.0

Sanic-Cors==0.9.9.post1

sanic-jwt==1.4.0

Sanic-Plugins-Framework==0.8.2.post1

scikit-learn==0.20.4

scipy==1.4.1

simplejson==3.17.0

six==1.14.0

sklearn-crfsuite==0.3.6

slackclient==1.3.2

spacy==2.2.3

spacy-lookups-data==0.2.0

SQLAlchemy==1.3.13

srsly==1.0.1

sympy==1.5.1

tabulate==0.8.6

tensor2tensor==1.14.1

tensorboard==1.14.0

tensorflow==1.14.0

tensorflow-cpu==1.15.0

tensorflow-cpu-estimator==1.15.1

tensorflow-datasets==2.0.0

tensorflow-estimator==1.14.0

tensorflow-gan==2.0.0

tensorflow-hub==0.7.0

tensorflow-metadata==0.21.1

tensorflow-probability==0.7.0

termcolor==1.1.0

terminaltables==3.1.0

textblob==0.15.3

tflearn==0.3.2


thinc==7.3.1

tqdm==4.42.0

traitlets==4.3.3

twilio==6.35.4

Twisted==19.10.0

typed-ast==1.4.1

typing==3.7.4.1

tzlocal==2.0.0

uritemplate==3.0.1

urllib3==1.25.8

wasabi==0.6.0

wcwidth==0.1.8

webexteamssdk==1.2

websocket-client==0.54.0

websockets==8.1

Werkzeug==0.16.1

wrapt==1.11.2

xgboost==0.90

yarl==1.4.2

zipp==2.1.0

zope.interface==4.7.1
