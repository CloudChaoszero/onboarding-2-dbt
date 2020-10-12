# Analytic Engineering & dbt: 0-100

![dbt Logo](https://docs.getdbt.com/img/dbt-logo-full.png)

# Summary

This is a quick guide on how to get started and create your data models using dbt (data build tool).
dbt is a Python-based packaged for managing `Transform`ations in the ELT (Extract, Load, Transform) lifecyle.

You can find a quick slide deck on dbt from [my past Lighting Talk on dbt, here](https://raulingaverage.dev/Presentations/PyBayTalks/2020/dbt/Lighting-Talk-dbt#/).

To see the resulting documentation portal, head to [raulingaverage.dev/dbt-Docs-Tutorial-Portal/)](https://raulingaverage.dev/dbt-Docs-Tutorial-Portal/).

* Tutorial: [dbtOfCourse](https://github.com/CloudChaoszero/dbtOfCourse)
* Code: [Github Repository](https://github.com/CloudChaoszero/customer-analytics)

## Donate

If you would like to support this project, feel free to consider donating to one of the following:

* [PyLadies Donation](https://psfmember.org/civicrm/contribute/transact?reset=1&id=6)
    * Note: [RLadies](https://rladies.org/) too, but I think they have enough funding, compared to PyLadies. Your choice, of course. :D
    * Why? With the recent trend gatekeeping and impact on COVID-19 on women, I feel this is top priority.
* [Delta Analytics](http://www.deltanalytics.org/donate.html)
    * Why? Nonprofit I volunteer for
* [Dev/Mission](https://devmission.org/)
    * Why? I really care about minorities, Blackx and Latinx groups going into tech.
* [NumFocus Donate](https://numfocus.org/donate)
    * Why? <3 Python community

# Installation

## The Tutorial

Go to this repository [customer-analytics](https://github.com/CloudChaoszero/customer-analytics), and enter the following in your CLI (outside of this repo):
```bash
git clone https://github.com/CloudChaoszero/customer-analytics.git
```
* Note: I used a Snowflake Trial to implement this tutorial.

## Environment

```bash
conda create --name dbtcourse
python -m ipykernel install --user --name dbtcourse --display-name "Python (dbt Course)"
```


# Resources

* [dbt Documentation](https://docs.getdbt.com/)
* Tutorial [customer-analytics](https://github.com/CloudChaoszero/customer-analytics)