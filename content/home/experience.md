---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Internship Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Quantitative Research Intern
    company: Qingan Investment Management Co., Ltd.
    company_url: 'http://www.qafunds.com/website/w/h'
    #company_logo: qingan
    location: Shanghai, China
    date_start: '2021-01-01'
    date_end: '2021-07-31'
    description: |2-
        Responsibilities include:
        
        * Refactored the back-test code of high-frequency stock trading strategies in Python, increasing the running speedby a factor of over three hundred
        * Used Ridge regression model to develop high-frequency stock trading strategies with Sharpe ratio of over 1.5
        * Developed future CTA strategies based on fundamental data of ferrous metals with Sharpe ratio of over 2.5
        * Collected and processed futures data, including data crawling and data cleaning, and deployed the data on Linux servers for daily updating of tasks
        
  - title: Data Analyst Intern
    company: Tongcheng-Elong Holdings Limited
    company_url: 'https://www.ly.com/'
    #company_logo: org-x
    location: Beijing, China
    date_start: '2020-06-01'
    date_end: '2020-09-01'
    description: |2-
        Responsibilities include:
        
        * Mined user behavior data for marketing businesses to determine if they had been attacked
        * Screened out high-risk users using models such as the GN community discovery algorithm; added users to the blacklist
        * Developed risk control strategies to intercept dangerous users and conduct offline testing.

design:
  columns: '2'
---
