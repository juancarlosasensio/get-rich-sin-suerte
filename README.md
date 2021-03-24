# How to Get Rich (without getting lucky)
## The original Twitter thread by [@naval](http://github.com) can be found [here](https://twitter.com/naval/status/1002103360646823936)

This website is live here: https://get-rich-sin-suerte.netlify.app/

## About this project

This modest little project presents a nice Twitter thread in a fun new format. Thoughts on wealth are Naval Ravikant's. The tweets in Spanish were written by yours truly.

The styling was first crafted by writer and programmer [Robin Sloan](https://www.robinsloan.com/), who was kind enough to let me use the styles he used [here](https://platforms.fyi/), 
and to modify them slightly for the purpose of this project. 

## How it was built

The website is a simple Jekyll project hosted on Netlify. It uses Jekyll's multiple languages plugin for internationalization, currently available in English and Spanish. 

I used a tiny utility plugin I wrote in Ruby to convert the thread data from JSON (which came from https://threader.app/) into a .yml file.
