# HN Ratio

Hacker News top 50 stories ranked by Comment/Score ratio.

See stories that attract a lot of attention and comments, and stories that attract a lot of attention but few comments.

## Sample output (top 20)

```
Billionaire Mike Novogratz says 10% of his money is in Bitcoin and Ether
https://news.ycombinator.com/item?id=14164523

|############################################      | S: 99 C: 89 R: 0.899


Louisiana’s Governor Declares State Of Emergency Over Disappearing Coastline
https://news.ycombinator.com/item?id=14164541

|##########################################        | S: 115 C: 98 R: 0.852


'Fight Inequality' Is a Poor Rallying Cry
https://news.ycombinator.com/item?id=14166239

|#################################                 | S: 28 C: 19 R: 0.679


Caddy 0.10 Released
https://news.ycombinator.com/item?id=14164712

|#############################                     | S: 106 C: 63 R: 0.594


The Evolution of Container Usage at Netflix
https://news.ycombinator.com/item?id=14163526

|############################                      | S: 128 C: 72 R: 0.562


Robots.txt meant for search engines don’t work well for web archives
https://news.ycombinator.com/item?id=14163216

|#####################                             | S: 237 C: 104 R: 0.439


Mice treated with a protein from umbilical cord plasma showed improved memory
https://news.ycombinator.com/item?id=14163395

|##################                                | S: 122 C: 46 R: 0.377


The First-Ever Banner Ad on the Web
https://news.ycombinator.com/item?id=14165719

|##################                                | S: 24 C: 9 R: 0.375


Metaprogramming is less fun in D
https://news.ycombinator.com/item?id=14165198

|##################                                | S: 30 C: 11 R: 0.367


Scalable, Lie-Detecting Timeserving with Roughtime
https://news.ycombinator.com/item?id=14164662

|################                                  | S: 15 C: 5 R: 0.333


Introducing Token
https://news.ycombinator.com/item?id=14164018

|##############                                    | S: 303 C: 86 R: 0.284


Calculus Made Easy (1914) [pdf]
https://news.ycombinator.com/item?id=14161876

|#########                                         | S: 761 C: 140 R: 0.184


Intel Shuts Down Lustre File System Business
https://news.ycombinator.com/item?id=14165785

|#####                                             | S: 19 C: 2 R: 0.105


Automatic compilation of partially available C source code
https://news.ycombinator.com/item?id=14164495

|#####                                             | S: 78 C: 8 R: 0.103


Rarepepe is [one of] the most innovative projects in crypto/blockchain
https://news.ycombinator.com/item?id=14166331

|####                                              | S: 11 C: 1 R: 0.091


Raw Linux Threads via System Calls (2015)
https://news.ycombinator.com/item?id=14162423

|###                                               | S: 166 C: 12 R: 0.072


Most people prosecuted for terrorism since 9/11 never committed a violent act
https://news.ycombinator.com/item?id=14166003

|##                                                | S: 43 C: 2 R: 0.047

```

Note that new "promoted" stories with low votes and job listings are filtered.

## How to see result

Go to `results/result-xxx.txt` to see the result of a certain day

## How to run the script

`$ pip install -r requirements.txt`

Then

`$ python hn-ratio.py > results/result-xxx.txt`