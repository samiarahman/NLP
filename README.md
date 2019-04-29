## Installation

To install the required python modules you can create a virtual environment and install all the required dependecies there using a requirements.txt file provided in this repo:

1. Create a conda environment:
`conda create -n nlp python=3.6.8`

2. Activate the environment:
`conda activate nlp`

3. Install the requirements:
`pip install -r requirements.txt`

4. Install python mpg321 mp3 player:
`brew install mpg321`

5. Install ffmpeg for mp3 to wav conversion:
`brew install ffmpeg`

6. Install ps to png converter
`brew install imagemagick`
`brew install gs`

## API Keys

In order to use the google knowledge graph create an api key and store it in .api_key file

Follow instructions at `https://developers.google.com/knowledge-graph/prereqs`
