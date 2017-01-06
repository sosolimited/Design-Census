# Design Census 2016
Data visualization of AIGA's design census results.

## How to run this

- Run a localhost webserver, so you can run the website locally
	- On Mac:
		- Assuming this repo is in your user folder called `Downloads`
		- Open the application `Terminal`, type `cd ~/Downloads/Design-Census/`
		- Then type `python -m SimpleHTTPServer 9000`
		- Open a browser window and go to `http://localhost:9000/`, the site should display
	- On Windows:
		- Install a local webserver app like [MAMP](https://www.mamp.info/en/downloads/)
		- Run MAMP and check what the default port is in its settings (example: 8080, 9000, etc)
		- Open a browser at localhost with whatever port is used by MAMP (example: `http://localhost:8080/`)

## Notes on the code

- The data (in the `data/` folder):
	- `PRODUCTION-questions_cleaned.json` : file containing the questions from the census
	- `PRODUCTION-us_cleaned.csv` : file containing the answers in the US from the census
- The code for the graph:
	- All the code is in `index.html`
	- The graph uses the Javascript library [D3.js](https://d3js.org/). It's a bit difficult to learn, but this might be a good place to start learning it!
