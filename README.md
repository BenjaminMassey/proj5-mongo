# Project 5: Brevet time calculator with Ajax and MongoDB

A project by Ben Massey (benjamin.w.massey@gmail.com) for CIS 322

## What is it?

A brevet calculator table that can be saved and loaded to a mongoDB database

## How to use it

Create a MongoDB database - I used mLab

Create a collection named "times" in that database

Create a credentials.ini in /DockerMongo/ that matches credentials-skel.ini

Then do one of the following:

Just run flask_brevets.py through Python with "python flask_brevets.py"

Build and run with Docker standardly with "docker build -t NAME ." and "docker run -p PORT:PORT NAME"

Run using the fancy Docker-Compose with "docker-compose up"

## Test

To make sure you set up your database right, run test_cases.py with "python test_cases.py"