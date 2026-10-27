# Where Do College Softball Players Call Home?

An interactive map of the hometowns of NCAA Division I softball players: 305 programs and about 6,900 players, taken from each school's official roster (2027 rosters where posted, otherwise 2026).

- **Hometowns:** every player's hometown and school, filterable by conference and home state.
- **Players per Capita: States / Metros:** players per 100,000 residents, using U.S. Census Bureau population estimates (ACS 2020-2024 5-year, table B01003).

The whole site is the single file `index.html`. It loads d3, topojson and datamaps from cdnjs.

## Publishing with GitHub Pages
In the repository go to **Settings → Pages**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, and save. The site appears at `https://<your-username>.github.io/<repository-name>/` within a minute or two.

## Updating
Rebuild the page in the project folder (`build_data.py`, then assemble `site/softball-hometowns.html`), copy it here as `index.html`, and commit.
