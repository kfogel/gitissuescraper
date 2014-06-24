gitissuescraper
===============

A tool to help extract some issue information from a GitHub project.  The output for each scanned project is a four-column CVS written to a file named `OWNER_REPOS.csv` (where OWNER and REPOS are what you think they are).  The four columns are:

        issue title, issue body, issue URL, tags

The output is meant to be used in <a href="https://www.overviewproject.org/">Overview,</a> which allows for batch-tagging and visualization of common words.
