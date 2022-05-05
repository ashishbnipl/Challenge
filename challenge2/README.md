# **Challenge #2**

We need to write code that will query the meta data of an instance
within AWS and provide a json formatted output. The choice of language and
implementation is up to you.

# Approach


> In **Azure** it is fairly easy to retrieve meta data information. On a linux terminal

> curl -H Metadata:true --noproxy "*"  "http://169.254.169.254/metadata/instance?api-version=2020-09-01"

Would give the JSON output of metadata


- The machine that is running this service is configured with right access keys and permissions in IAM.

# Testing

I am going to use Mocha javascript testing framework to do the unit testing

# Bonus Points

The code allows for a particular data key to be retrieved individually

# Prerequisites

Create an  Linux vm  instance on azure.

SSH into the instance

# Installation

Install Python 3 and git on your instance

> sudo yum install python3 git

Clone this repository

Install pipenv

> sudo pip3 install pipenv

Go to directory **challenge2**

> cd challenge2

Install project dependancies

> pipenv install

# Running

Open the src folder

> cd challenges/challenge2/src

Run whichever script you need:

> python3 metadata.py

> python3 querymetadata.py
