#Instagram Spider
Scrapy spider used for saving all the photos and videos from an instagram account without using Instagram API.

##Requirements :
Scrapy

##Usage
To use this spider,
make sure that you have Python and Scrapy installed,
then use the following command :

```python
scrapy runspider instagram_spider.py -a account=<name of the account> -a videos=<y or n>
```

If you don't precise those parameters, they will be asked when you launched the spider.

All the photos and videos will be saved in folder with the name of the account.
