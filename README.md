
Asynchronous scraping tool to fetch LinkedIn-learning's courses videos.

Dependencies:
- Python
- aiohttp
- lxml

#### Usage
> pip install -r requirements.txt

Copy and edit `config.py.example` (username, password, and courses slugs)

```Course's slug can be obtained using its url
e.g:
COURSE URL: https://www.linkedin.com/learning/python-working-with-predictive-analytics
->
SLUG: python-working-with-predictive-analytics
```
Run script
