# Financial Analyst Crew

This project uses AI to automate financial analysis tasks. It's built with Python and uses the `crewai` library to manage tasks and processes.

## Installation

This project uses [Poetry](https://python-poetry.org/) for dependency management. To install the project and its dependencies, run:

```bash
poetry install
```
### Usage
To run the project, use the poetry run command followed by the project name:

```bash
poetry run financial_analyst_crew
```
This will start the financial analyst crew, which will perform various tasks such as researching companies and analyzing their stock performance.

### Tasks
The tasks that the financial analyst crew can perform are defined in the tasks.yaml file. Here's a brief overview of each task:

**research_company_task:** <br>
This task uses a search tool to look up a company's stock information. The goal is to prepare enough information to make an informed analysis of the company's stock performance.

**analyze_company_task:** <br>
This task analyzes a company's stock performance and prepares a report of various metrics, including probability metrics, liquidity metrics, efficiency metrics, solvency metrics, market value metrics, cash flow metrics, growth metrics, and risk and return metrics.

### Contributing
Contributions are welcome! 

### License
This project is licensed under the MIT License.