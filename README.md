# Erlang web crawler

This repository contains code of a learning project called: "Erlang web crawler".

It's purpose is to build a web crawler in Erlang that extracts all links from a page.

## Idea

In this project, you’ll build a Distributed Web Crawler using Erlang. You’ll start by creating a function to fetch the content of a URL using the httpc module. Then, you’ll extract all the links from the fetched webpage using regular expressions. The core of your project will be using multiple Erlang processes to concurrently fetch and extract links, communicating between processes using Erlang’s message passing. You’ll also incorporate Erlang’s error handling features to ensure your crawler is fault-tolerant and continues operation even if a URL fetch fails. Data from your crawl will be stored, either simply in a file or using a database system like mnesia. Lastly, you’ll add rate limiting features using Erlang’s timer module to prevent server overload or getting blocked. This project will give you hands-on experience with Erlang’s concurrency, fault-tolerance, and real-time system capabilities.

## Learning

- Erlang
- Httpc
- Regular expressions
- Mnesia
- Rate limiting
- Concurrency
- Fault-tolerance

## Requirements

- The application must extract all links from a page.
- The application must be able to crawl multiple pages at the same time.
- The application must never stop crawling out of itself.
- The application must have rate limiting features to make sure all pages can be retrieved.
