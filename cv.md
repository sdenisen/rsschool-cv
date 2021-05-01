## Sergey Denisenko 

#### Contact Info:
* tel.: +7 (920) 254-93-94  — preferred means of communication
* e-mail: sdenisen@ymail.com
* city: Nizhny Novgorod, willing to relocate (Moscow, Saint Petersburg, Novosibirsk), prepared for business trips

#### Summary: 
I have a good experience with IT, including commercial software product development and some types of software test 
automation like Regression, Load and Component. Usually use development best design principles like __KISS__, __SOLID__.
Good practical experience within an agile software development environment (preferably _Scrum_). 
Self-starter with the ability to learn new things quickly. I'm a relentless learner. I try to find the best courses, 
where I can get new experience in software development that improve my skills. 

#### Skills:  
- Personal skills and competences:
Knowledge of Design patterns for software development. TDD. Unit Tests, SOLID design and other principles.
- Programming Languages: _Python_, _JavaScript_, _C#_, _Java_;
- Operating Systems: _MS Windows_, _MacOS_, _Linux(for testing purpose); 
- DB: _MySQL_, _MSSQL_;
- Dev Env: JetBrains Software like: _PyCharm_, _ReSharper_, _IntelliJ IDEA_; MS Visual Studio;
- Tools: _CVN_, _Perforce_, _GitLab_; _Jira_, _Rally Software_;
- Frameworks/Technology: _Django_, _jQuery_, _React_, _Selenium_, _pytest_, _.Net_, _Asp.Net_;
- Methodologies: Ajile (SCRUM, KANBAN), pair programming.

#### Code examples: 
[Link to code example (Python)](https://github.com/sdenisen/searchApp)
```import sqlite3
from pathlib import Path

import pandas as pd

print(Path(__file__).resolve().parent.parent)

df = pd.read_excel(f"{Path(__file__).resolve().parent.parent}/data/excel_data.xlsx")

db_conn = sqlite3.connect(f"{Path(__file__).resolve().parent.parent.parent}/db.sqlite3")

c = db_conn.cursor()

c.execute("CREATE TABLE details (id INTEGER primary key, asv_id INTEGER , full_name TEXT NOT NULL);")

df.to_sql('details', db_conn, if_exists='append', index=False)
```

#### Experience:
company: Five9 Inc.
position: Test Automation Engineer
Project Name: "CRM Integration"
Project Abstract:
“CRM Integration”. Five9 Integration with RightNow, Salesforce, MS Dynamics 365, Zendesk, and other SaaS. CRM Integration project is one of the main areas for development of our company. 

#### Education: 
Nizhny Novgorod State University, "Calculus Mathematics and Cybernetics Faculty, Master in Informatics". (2007)
Passed "Google Cloud Platform" trainings on coursera.org (2020).
Hackathon team member:
- "Sibur Challenge" participant (2019)
- "Digital Breakthrough" (qualifying round and final) (2019)
- "Teplo-Energo" - winner of the hackaton (2021)

#### English:
Good reading and writing skills; but need some more practice with speaking; 