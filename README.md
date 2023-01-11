# gconfig
A very simple shell command for switching between gcloud configurations

Creating gcloud configurations is very simple:

1. run `gcloud config configurations create <CONFIG-NAME>`
2. run `gcloud auth login` to set the user account for the configuration
3. [OPTIONAL] run `gcloud config set project <PROJECT-ID>`

Then you setup the `gconfig` shell script into your path so you can just run `gconfig` to change your gcloud context at anytime.
