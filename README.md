# News module for SilverStripe 3
A module to add a news page (like a blog) for SilverStripe 3. It uses DataObjects for individual
news articles, mapping each one to an individual URL using $url_handlers.

## Features
* DataObjects instead of SiteTree for news articles (much neater than adding every article into SiteTree)
* Controller $url_handlers to provide each article it's own page /<newspage>/article/id/<article-name>/ (auto-generated)
* Individual article date & time - will not show if in the future allowing schedules posts
* Custom Breadcrumbs() function to add articles to breadcrumbs
* RSS feed
* Pagination

## Requirements
* SilverStripe 3+
