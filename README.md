
# Learn-to-Race Workshop Website


## About

This website was built [Jekyll](https://jekyllrb.com/) and uses the [Jekyll TeXt Theme](https://tianqi.name/jekyll-TeXt-theme/docs/en/quick-start). This site is hosted on AWS S3, which I find easier to use than Github pages.

## URL

We can also choose to buy a domain name and link this. http://www.learn-to-race-challenge.com.s3-website-us-east-1.amazonaws.com/


## Local Hosting

Make sure you have the following installed:

* [Ruby](https://www.ruby-lang.org/en/documentation/installation/)
* [Jekyll](https://jekyllrb.com/)

Then simply navigate to the ```src``` directory and run the following command:

```bash
$ bundle exec jekyll serve
```

## Modifications

Most all modifications to the site are just in the respective ``src/*.md`` files. Calling ```bundle exec jekyll serve``` will rebuild the site and place the public site files in the ```_site``` directory which can just be uploaded into the AWS S3 bucket to modify the public site.
