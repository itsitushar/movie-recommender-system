#movie recommendation system using content based filtering

## Get started

Step 1. Navigate to the project directory

`cd movie-recommender-system`

Step 2. Create a virtual environment

`python3 -m venv .venv`

If virtual environment is not installed, install it first

`apt install python3.10-venv`

Step 3. Activate virtual environment within the project directory

`source .venv/bin/activate`

Step 4. Install git lfs

`sudo apt-get install git-lfs`

Step 5. Fetch large files from lfs

`git lfs fetch --all`
`git lfs pull`

Step 6. Run the application

`streamlit run app.py --server.port 8012`
