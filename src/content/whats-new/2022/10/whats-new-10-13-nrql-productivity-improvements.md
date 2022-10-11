---
title: 'Query with new NRQL improvements such as NRQL variables, anchor parse, and regex multi-capture, to better explore and understand your data'
releaseDate: '2022-10-14'
getStartedLink: 'https://docs.newrelic.com/docs/query-your-data/nrql-new-relic-query-language/get-started/nrql-syntax-clauses-functions'
---

## NRQL productivity improvements makes querying faster, so you can sooner understand your data for better decision making

Making sense of complex data like log messages just got easier! With NRQL variables and the new `aparse()` and `if()` functions, you can obtain useful information from your data more efficiently and gain insights faster for better decision-making.

With NRQL variables, you can assign values to variables and use them multiple times in your query.  The `if()` function lets you select one of two results based on a condition that's either true or false. In addition, we've enhanced our existing regex `capture()` function to allow multiple capture groups, for simpler queries with better performance!

In this example, we extract an item ID, and unit price from a log message, and additionally show which pricing tier the item falls into: 
!["NRQL productivity"](./images/NRQL-Productivity-1.png "NRQL productivity")

The aparse() function is a simpler, faster alternative to capture() for use when you don't require the full power of regular expressions. With aparse(), use "anchor" text and the '*' wildcard to capture the fields you need:
!["NRQL productivity 2"](./images/NRQL-Productivity-2.png "NRQL productivity 2")

You can also see how these NRQL improvements work in this NerdByte:

*link

## Next steps

1. Review the docs for [NRQL variables](/docs/query-your-data/nrql-new-relic-query-language/get-started/nrql-syntax-clauses-functions/#with-as-nrql-var), [aparse()](/docs/query-your-data/nrql-new-relic-query-language/get-started/nrql-syntax-clauses-functions/#func-aparse) and [if()](/docs/query-your-data/nrql-new-relic-query-language/get-started/nrql-syntax-clauses-functions/#func-if) and start writing your own queries!
2. Read our [blog]() post for more tips and examples.
3. Share your feedback, post your own queries, and see even more examples in the [Explorer's Hub discussion]().