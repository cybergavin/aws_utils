### AWS Utils

These are utility scripts used for AWS.

#### arl_posts.py

This script retrieves a list of **AWS re:Invent launch** blog posts for a given year. The output is written to an HTML file `arl_posts_<YYYY>.html`.

USAGE:
```
python arl_posts.py [YYYY]
```

where YYYY is optional and is the year for which you want to retrieve blog posts. If no argument is specified, a list of blog posts will be generated for the current year.

---