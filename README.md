# Social media trend analyzer

## Summary

The tool will gather information about social media posts using Twitter API and predict social media topic trends peak volumes and durations based on early signals.

## Background

The tool can be used for many purposes such as
* by companies and politicians for responding to and managing discusion trending discussion themes relevant to them, 
* by journalists to recognize impactful stories, and
* by advertisers to react to new trends.

## How is it used?

The tool is deployed to a cloud compute platform, such as AWS or Azure environment. A serverless solution will be used to run the code in the cloud in connection with a database solution for the data storage and processing.

The tool is by nature always on and processing the social media posts. There will be a way for the user to define topics about which to receive alerts from when they are predicted to be trending in a short future.

## Data sources and AI methods

Sources:
* Twitter API
* todo

AI methods:
* Unsupervised learning

## Challenges

A key challenge is to identify posts that are part of a cenrtain trending topic. Trivial solutions are to look for hashtags and linked posts (replies), and posts that includes links to the same news articles. This is expected not to be enough. To meaninfully identify trends some words and/or phrases should be automatically classified as belonging to the same trending phenomenon.

## What next?

Lorem ipsum

## Acknowledgments

Lorem ipsum
