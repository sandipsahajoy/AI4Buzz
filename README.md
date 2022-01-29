# AI4Buzz

## Project Summary
This project is to develop a web service to allow researchers to gain insight into the meanings and semantics of what makes a social media post more influential. Specifically, this project will expose a web REST API to allow researchers at AI4Society to upload images and retrieve a summary of an analysis of that photo. This analysis may contain anything from a color scheme analysis to sentiment classification of the photo.
- Demo: https://cmput401.ca/projects/a3bc8e93-1275-434e-9e88-f4af38bb276c

## Project Documentation
- https://sandipsahajoy.xyz/AI4Buzz/

## Active Deployment - Cybera
- Frontend URL: http://[2605:fd00:4:1001:f816:3eff:fe67:1ff9]
- Backend API URL: http://[2605:fd00:4:1001:f816:3eff:fe26:70dd]
- API Documentation: http://[2605:fd00:4:1001:f816:3eff:fe26:70dd]/docs

## Local Setup
### Prerequisites
- Python 3.9
- Yarn and Nodejs

### API
1. clone the repo
2. `cd` into the `api` directory
3. generate virtual environment with `python3 -m venv env`
4. activate virtual env with `source env/bin/activate`
5. install requirements with `pip install -r requirements.txt`
6. run app with `uvicorn api.main:app --reload`

### Web Client
1. clone the repo if you haven't already
2. `cd` into `frontend` directory
3. use `yarn start` to start app locally

## Testing
### Backend
- Endpoint test API: `pytest api/tests/test_endpoints.py`
- Unit test models: `python -m unittest discover -p "*__test.py"`

### Frontend
- snap shot test: `yarn test`
