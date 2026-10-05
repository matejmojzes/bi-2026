# 18BI — Business Intelligence

FNSPE CTU in Prague · 2026 · Matej Mojzeš

One 100-minute session per week, lecture and exercise combined. Materials are
Jupyter notebooks, and everything runs on your own laptop.

> **Materials appear here after each session**, not before. If `lectures/` looks
> emptier than you expected, that is why. Run `git pull` after the session.

## Setup

From the repository root:

```bash
uv sync
uv run jupyter lab
```

Then open `exercises/00_hello_world.ipynb` and run it. It checks that Jupyter runs on the
project's Python and that the packages are there, and ends with `ALL GOOD` or a short list
of what is missing.

No `uv`? `python -m venv .venv && .venv/bin/pip install -r requirements.txt`, then
`.venv/bin/jupyter lab`, does the same job, just more slowly.

## Layout

```
lectures/     the talk, one notebook per week
exercises/    the hands-on part, runnable
handouts/     printable material used in the sessions
data/         the data the exercises work with
files/        images and diagrams
```

More appears week by week, after each session.

## Weekly rhythm

| week | lecture | exercise |
|---|---|---|
| 1 | BI in the age of AI | the revenue example, on paper |
| 2 | production vs analytical systems | first queries |
| 3 | data integration, ETL / ELT | integration and transformation |
| 4 | the data warehouse | warehouse and analytical layer |
| 5 | data marts and domain analytics | metrics and the semantic layer |
| 6 | reporting, dashboards, storytelling | reports and basic dashboards |
| 7 | OLAP and interactive analytics | advanced visualisation, storytelling |
| 8 | data mining | exploratory analytical methods |
| 9 | AI-augmented analytics | anomalies, insight discovery, NLQ |
| 10 | integrating advanced analytics | BI as a consumer of analytics |
| 11 | BI, knowledge and decisions | metadata and governance |
| 12 | metadata, governance, responsible BI | data quality monitoring |
| 13 | data quality assurance | **student project presentations** |

## Assessment

A project plus a presentation to your classmates in week 13. Topic and
specification to be agreed during the first weeks of the semester.

## Reference

* Ralph Kimball, [*The Data Warehouse Toolkit*](https://www.kimballgroup.com/data-warehouse-business-intelligence-resources/books/)
* [dbt documentation](https://docs.getdbt.com/) · [DuckDB documentation](https://duckdb.org/docs/)
