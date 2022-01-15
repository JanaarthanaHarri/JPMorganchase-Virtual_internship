## Introduction
Experience Technology at JP Morgan Chase & Co
Try out what real work is like in the technology team at JP Morgan Chase & Co. Fast track to the tech team with your work.

## Module 1 Task Overview
Interface with a stock price data feed and set up your system for analysis of the data

Aim: We want to process the data feed of stock A and stock B’s price to enable us to analyse when trading for the stock should occur.

1. Please clone this repository to start the task
2. Adjust the getRatio, getDataPoint and main functions
3. Bonus: Pass all unit tests and add more to cover edge cases
4. Upload a git patch file as the submission to this task

## Set up / Installation
In order to get the server and client application code working on your machine, [follow the setup here](https://insidesherpa.s3.amazonaws.com/vinternships/companyassets/Sj7temL583QAYpHXD/setup_devenv_m1_v6.pdf)

Note:This is the Python 3 version of the JPM 1 exercise. The Python 2.7 version is in this [other repo](https://github.com/insidesherpa/JPMC-tech-task-1)

## How to Run
To start the server, run

`python server3.py`

this will create random market called 'test.csv' in your working directory if one does not already exist.

If you encounter an issue with datautil.parser, run this command:

`pip install python-dateutil`

If you don't have pip yet, you can install it from: https://pip.pypa.io/en/stable/installing/

To start the example client, run:

`python client3.py`

To unit test the example client, run: python client_test.py

## How to request from the server using curl
Query:

```Curl
$ curl 'http://localhost:8080/query?id=1'
{"id": "1", "top_ask": {"price": 129.18, "size": 70}, "timestamp": "2016-08-06 12:32:11.821574", "top_bid": {"price": 128.79, "size": 61}} 
```

## How to fix the code to meet objectives
To make the changes necessary to complete the objectives of this task, [follow this guide.](https://insidesherpa.s3.amazonaws.com/vinternships/companyassets/Sj7temL583QAYpHXD/making_changes_m1_v4a.pdf)

To do the bonus task, [read this.](https://insidesherpa.s3.amazonaws.com/vinternships/companyassets/Sj7temL583QAYpHXD/client_test_m1_v1a.pdf)

## How to submit your work
A patch file is what is required from you to submit. To create a patch file, [follow this guide.](https://insidesherpa.s3.amazonaws.com/vinternships/companyassets/Sj7temL583QAYpHXD/create_patch_file_v3a.pdf) Then submit the patch file in the JPM Module 1 Page.
