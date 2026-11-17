The application is currently deployed and accessible through the following link: https://mmintersect.streamlit.app/
- Select a major and a minor and click the analyze intersection button and profit

Alternatively, if the application is desired to be use offline or needed locally for some reason download the ISProj.html file

The base application was coded in Google colab represented by the ISProj.ipynb file

## Project history
This repository continues the work started by Richard Lin and team in [RichardLin3/InfoSysProj](https://github.com/RichardLin3/InfoSysProj). Full commit history is preserved here. Data URLs in `app.py`, `ISProj.html` and `ISProj.ipynb` now point to `ef2020/InfoSysProj`.

## For new contributors
- The previous team's final report (goals, architecture, logic, hosting, user manual) is in [`docs/FinalReport_Fall2025_Lin_Oubrom_Diaz.pdf`](docs/FinalReport_Fall2025_Lin_Oubrom_Diaz.pdf). Note: the report refers to `minors.json`, `majors.json` and `courses.json`; the actual files are in `data/` (`minors_v3.json`, `all-majors.json`, `gened_v2.json`, `liberal_arts_courses.json`, `ID.json`).
- Run locally: `pip install -r requirements.txt` then `streamlit run app.py`.
- The app reads the JSON files from this repo's `main` branch on GitHub, so data changes appear in the app only after they are merged into `main`.
