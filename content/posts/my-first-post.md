+++
title = "Test Post"
author = ["lou."]
tags = ["test"]
categories = ["testposts"]
draft = false
+++

this is a post in `which` i'll ~~try~~ ~~out~~ all <span class="underline">kinds</span> of stuff _relating_ to **hugo**

> test quote

```common-lisp
(defun test (str)
  (declare ignore str)
  (print "Hello World"))
```


## let's also add a heading {#let-s-also-add-a-heading}

It's kinda impotant to know how those work


## embedding stuff {#embedding-stuff}

(and also subheadings. note that this style doesn't seem to distinguish between
levels of subheadings.)


### tweets {#tweets}

Adding an embedded tweet.

https://twitter.com/einsiedlerspiel/status/1207715089224220672?s=20&t=ZFQCPYp2tQAQosb1f-vQXg

{{< tweet user="SanDiegoZoo" id="1453110110599868418" >}}


#### toots {#toots}

Embedding toots is implemented via a custom shortcode

{{< toot link="https://todon.nl/@einsiedlerspiel/109557532922888143" >}}

<!--list-separator-->

-  and more!

    as I'm writing this in org mode and export with ox-hugo 5\* subehadeings become lists.


## here's a table {#here-s-a-table}

| first | second | third |
|-------|--------|-------|
| test  | test2  | test3 |
| test4 |        |       |

and a slightly different one

| key | value |
|-----|-------|
| 1   | 2     |
|     |       |


## lists {#lists}

we've already seen that lists can be created with org header but org also has
support for lists so how are those handled?


### test 1 {#test-1}

-   first
-   try
-   with
-   -


### test 2 {#test-2}

-   second
-   try
-   with +


### test 3 {#test-3}

1.  numbered
2.  lists
3.  are
4.  cool