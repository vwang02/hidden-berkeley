# Hidden Berkeley: HW2 starter

Create your own public website from this starter, then use a Jupyter notebook to edit the data it displays.

**Start here:** on the [HW2 template repository](https://github.com/macss-berkeley/hw2-hidden-berkeley-template), choose **Use this template → Create a new repository**. Name your copy `hidden-berkeley` and make it public. Clone your copy with GitHub Desktop and open its folder in VS Code. Follow [hw2_hidden_berkeley.ipynb](hw2_hidden_berkeley.ipynb).

## What is in this repository?

| File | What it does |
| --- | --- |
| `hw2_hidden_berkeley.ipynb` | Your instructions, data edits, and submission evidence. |
| `docs/_data/locations.csv` | The resource data. The notebook edits this file; the website reads it. |
| `docs/index.md` | The page heading, introduction, and supplied loop that displays the CSV rows. |
| `docs/_config.yml` and `docs/_layouts/default.html` | Supplied website settings and layout. |

GitHub Pages builds the website from `main` and `/docs`. After you push a changed CSV, GitHub rebuilds the page using the new data. Jupyter only edits and saves the data; it does not build the website. The `_data` folder name is required by the website builder.

## Purpose and sources

The website provides some brief info of UC Berkeley campus resources. Newly admitted students can refer to this website to navigate locations to study and fulfill basic needs, and places of interest. Besides the first 8 resources, I added Campanile to the page, because it is an iconic symbol of UC Berkeley. Its website is confirmed to be https://visit.berkeley.edu/campus-attractions/campanile, under the UC Berkeley domain.

## Website checks

The website is live at https://vwang02.github.io/hidden-berkeley/. I updated Morrison Library's info to reflect detailed entry policies and the Library's specific website. For Campanile, the new resource I added to the website, I checked its official website and added admission pricing to the page. The displayed values match my CSV. The official link for BAMPFA Film Library & Study Center is not specific enough; I replaced the original with https://bampfa.org/about/film-library-study-center.
