# Dmitry Petelin

## Contacts

- [Github: @petelin79](https://github.com/petelin79)
- <petelin.dmitry@gmail.com>
- Moscow, RU

## About me

Results-driven professional with a proven track record of achieving goals, and a diverse background in technical consulting, sales, and marketing, with outstanding performance in providing exceptional technical support, streamlining processes, and implementing automation solutions. Strong collaboration and engagement skills with customers. High quality blend of technical expertise, strategic thinking, and cross-functional collaboration to deliver impactful results at FinTech, MedTech and consumer markets.

## Experience

### <span>Technical consultant | 24 Exchange Bermuda Limited, Bermuda</span> <span>Oct 2022 -- now</span>
-	Building ECN venue with top tier banks for FX SPOT / NDF /SWAPS
-	Real-time trading monitoring and exposure representation via analytic tools
-	Market data analysis and automatization of processes related to daily operations.
-	Facilitate smooth onboarding of FIX clients and providers, ensuring seamless connectivity and efficient integration into the trading systems.
-	Response promptly and effectively to inquiries regarding FIX protocol, addressing questions, providing specifications, and offering support with connectivity issues.
-	Collaborate closely with cross-functional teams, including developers, quality assurance, operations, and sales, to troubleshoot and resolve complex technical problems related to trading system, post trading, credit distribution and back-office applications.
-	Conduct a thorough technical conformance to ensure the stability and reliability of trading systems, identifying, and resolving any potential issues.
-	Actively contribute to process improvements by identifying areas for enhancement and suggesting innovative solutions to optimize efficiency and minimize downtime.
-	Maintain comprehensive documentation of support activities, procedures, and troubleshooting steps to facilitate knowledge sharing and ensure consistent service delivery.


### <span>Business Sales&Marketing Leader, Sleep and Respiratory Care RCA market</span> <span>Jul 2018 -- Oct 2022</span>

- Sales and marketing development of Sleep and Respiratory Care business across RCA market in D2C, B2C and B2B sales channels.
- Strategic marketing and operations planning.
- Develop, coordinate and implement plans designed to increase existing business and capture new opportunities
- Setting objectives and identifying methods to reach those goals: CSG%, MS%, IGM%, WoCa

### <span>Sales Director Special channels</span> <span>Jul 2017 -- Jun 2018</span>

- Non-electronic channels sales management: Baby specialists, Pharma retail, Dental channel, FMCG hypermarkets (top 6) with overall yearly turnover > 30 mln euros
- Business development through opportunities in Loyalty and Incentive deals realization,integration within Beauty retail and TV shop sales
- Sales process development, distribution and promotion for Health and Personal care portfolio
- Sales team management: Sales leads and GKAMs
- Define of channels strategy, sales and distribution plan
- Commercial policy set up and realization
- Costs and budget efficiency control
- Motivation and development scheme build up

## Skills

-	Languages: Python, JavaScript / TypeScript
-	Programing platform: Node JS
-	Frameworks: Flask, Express, Angular  
-	Data analytics and visualization: Pandas, NumPy, Matplotlib, Qlik, Power BI, Grafana
-	Databases: PostgreSQL, SQLite, ClickHouse, MongoDB
-	WEB: HTML, CSS, SASS, Bootstrap, Figma, web-scrapping
-	Module bundler: Webpack, Gulp
-	API: FIX, REST
-	Version control: GIT, GitHub
-	Operation System: Linux


## Code sample

```
def can_exit(matrix: list) -> bool:

    def inner(row, col):
        for row,col in ((row,col-1), (row-1,col), (row,col+1), (row+1,col)):
            if not temp_matrix[row][col]:
                temp_matrix[row][col] = 1
                inner(row,col)

    if matrix[-1][-1]:
        return False

    temp_matrix: list = [[char for char in row] for row in matrix]
    for col in temp_matrix:
        col.insert(0,1)
        col.append(1)
    temp_matrix.append([1 for _ in temp_matrix[0]])
    temp_matrix.insert(0,[1 for _ in temp_matrix[0]])

    inner(1,1)
    return temp_matrix[-2][-2] == True

```

## Education

- Master degree, Omsk state technical university, Omsk

## Languages

- **Russian** - С2
- **English** - B2