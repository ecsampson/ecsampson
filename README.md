# 👋 Hi, I'm Ethan Sampson

**Aspiring Data Engineer | CS Grad (Michigan Tech) | SQL, Python, AWS, Power BI**

I'm a Computer Science graduate working toward my first role in Data Engineering. Day to day I work in IT (Rapid Resolution Specialist at Marco Technologies), but my focus outside of that is building pipelines, modeling data, and getting hands-on with the AWS data stack. I like the end-to-end problem: getting messy data in, structuring it so it's trustworthy, and making it usable for analysis.

📫 ethancsampson@outlook.com&nbsp;&nbsp;|&nbsp;&nbsp;[LinkedIn](https://www.linkedin.com/in/ethan-sampson-94ab3b261)

---

## 🧰 Tech Stack

**Languages:** Python · SQL (PostgreSQL, SQLite) · Java · C/C++
**Data & Cloud:** AWS (S3, Lambda, Athena) · PostgreSQL · Parquet · dbt *(in progress)*
**Analytics/BI:** Power BI
**Tools:** GitHub · VS Code · DBeaver

**Currently learning:** Apache Airflow, Snowflake, Docker, PySpark, Terraform

---

## 🛠️ Featured Project

### NOAA Weather ETL Pipeline
An end-to-end ETL pipeline that ingests weather data, stores it in S3, and makes it queryable via Athena and Power BI.

- Designed a star schema for the weather data model and made the call to load incrementally rather than full-refresh
- Built an S3 → Lambda ingestion flow triggered on a schedule, landing data in both Parquet and CSV
- Diagnosed and fixed a `date_id` collision bug in the incremental load logic
- Wrote analytical SQL against Athena (CTEs, window functions) for trend and performance queries surfaced in Power BI
- dbt integration in progress, layering tested, documented transformations on top of the raw ingestion

**A note on how this was built:** I used AI assistance to help write parts of the implementation. I own the architecture and design decisions — the schema, the incremental loading approach, the bug diagnosis — and can walk through and explain all of it. I'm being upfront that I'm not yet at the point where I could rebuild every line of the implementation from scratch unaided, and I'd rather say that plainly than overstate it.

`Python` `AWS S3` `AWS Lambda` `Athena` `Power BI` `dbt` `Parquet`

*([NOAA Weather ETL Pipeline](https://github.com/ecsampson/flagship_project))*

---

## 📚 Other Projects

**Houghton County Historical Society Kiosk** — *Team Lead*
Led a sponsored team project building a museum kiosk app: a photo slideshow plus a searchable database of local veterans.
`Kotlin` `SQLite` `Android Studio` `GitHub`

**SLS Admin Website** — *Senior Developer*
Maintained and extended the admin site for Michigan Tech's Sound and Lights Service, including a new page for improved database querying.
`PHP` `SQL` `HTML`

**Database Final Project** — *Full Stack Developer*
Built a site for storing/viewing student evaluations of teachers; implemented auth and hardened it against SQL injection.
`PHP` `SQL` `HTML`

<details>
<summary><b>More projects</b></summary>
<br>

**Underwater Image Enhancement AI Classification** — Ablation study evaluating how different image enhancement techniques (Ucolor, GLN-HE) affect YOLOv7 classification accuracy on underwater invasive plant imagery.

**Restart Robot** — Game dev project (7-person team); built enemy pathfinding algorithms and designed levels in Unity.

</details>

---

## 🎓 Background

B.S. Computer Science, Minor in Spanish — Michigan Technological University (2024)
Relevant coursework: Databases, AI, Systems Programming, Computer Networks, Security

**Certifications:** CJIS Security Certification (Minnesota Bureau of Criminal Apprehension)

---

## 📊 GitHub Stats

![Ethan's GitHub stats](https://github-readme-stats.vercel.app/api?username=ecsampson&show_icons=true&theme=synthwave)
<summary><h3>🗺️ Ethan's Coding Journey</h3></summary>
    I got an interest in coding through video games and wanting to learn how to make my very own. My parents then bought me a Python Minecraft coding book in middle school and I started there. I didn't start coding in classes until my senior year in high school when I took AP Computer Science. I graduated from high school in 2020 during Covid and during that summer I started attending Michigan Technological University pursuing a computer science degree. During my time in college, I was able to work on several projects that were sponsored such as Houghton County Historical Society (HCHS) and Sound and Lights Service (SLS). During projects such as those and also my Underwater Image Enhancement AI Classification project, I really began to develop and interest in data and how I can analyze data to enhance customer experience's and how data interacts with the world. I have just graduated from Michigan Tech in August 2024, since then I have been pursuing my knowledge in data, while working on projects like developing websites in order to gain real world experience as I pursue a job in the technical side of the world.
