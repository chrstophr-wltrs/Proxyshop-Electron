# User Actions

Below is a table of the actions which I've identified that I believe users will perform within Proxyshop.

- `Task` = Name of the user action
- `Casual` = How often most users perform this action
- `Power` = How often "power users" perform this action
- `Score` = A weighted average of the `Casual` and `Power` users scores, to determine how easily accessible the feature should be
  - I'm project that 20% of the total users are "power users"

The values under `Casual` and `Power` use an arbitrary scoring system. To demonstrate this works, here are some examples

- `100` - Feature is used every time the software is opened, but usually not more than once per session
- `300` - Feature is used multiple times per session
- `50` - Feature is used maybe once every other session
- `1` - Feature is used maybe once ever, if it is used at all

| Task                                               | Casual | Power | Score |
| :------------------------------------------------- | -----: | ----: | ----: |
| Choose an image > Smart-find                       |    300 |   300 |   300 |
| Render card(s)                                     |    250 |   250 |   250 |
| Choose an image > Custom                           |     70 |   150 |    86 |
| Enter custom card information                      |     70 |   150 |    86 |
| Generate showcase image                            |     80 |   100 |    84 |
| Continue a job                                     |     50 |   200 |    80 |
| Abort a running job                                |     60 |    60 |    60 |
| Check error logs                                   |     40 |    80 |    48 |
| Modify Settings > Use generative fill              |     40 |    75 |    47 |
| Override template for a card                       |     35 |    75 |    43 |
| Copy-paste error logs                              |     30 |    80 |    40 |
| Modify Render settings > Enable flavor divider     |     30 |    75 |    39 |
| Modify Render settings > Enable flavor text        |     30 |    75 |    39 |
| Modify Render settings > Enable reminder text      |     30 |    75 |    39 |
| Modify Settings > Fullart vertical framing         |     15 |    35 |    19 |
| Update a template                                  |     10 |    30 |    14 |
| Modify Settings > Force Snow Template              |     10 |    25 |    13 |
| Modify Settings > Force Miracle Template           |     10 |    25 |    13 |
| Modify Settings > Force Basic Land Template        |     10 |    25 |    13 |
| Add template plugin                                |      8 |    15 |     9 |
| Choose default template > All                      |      5 |    10 |     6 |
| Choose default template > Basic Land               |      5 |    10 |     6 |
| Choose default template > Token                    |      5 |    10 |     6 |
| Choose fallback template                           |      5 |    10 |     6 |
| Modify Settings > skip failed cards                |      5 |    10 |     6 |
| Modify Render settings > Collector mode            |      2 |    20 |     6 |
| Modify Render settings > Collector promo star      |      2 |    20 |     6 |
| Modify Render settings > symbol render mode        |      2 |    20 |     6 |
| Modify Render settings > default expansion symbol  |      2 |    20 |     6 |
| Modify Render settings > Override expansion symbol |      2 |    20 |     6 |
| Modify Render settings > Expansion symbol stroke   |      2 |    20 |     6 |
| Modify Render settings > Enable watermark          |      2 |    20 |     6 |
| Modify Render settings > Watermark opacity         |      2 |    20 |     6 |
| Modify Render settings > Pause for manual editing  |      2 |    20 |     6 |
| Modify Render settings > Import scryfall scan      |      2 |    20 |     6 |
| Modify Render settings > Border color              |      2 |    20 |     6 |
| Reset render settings for a specific template      |      1 |    20 |     5 |
| Screenshot proxyshop                               |      4 |     8 |     5 |
| Modify Settings > artist in filename               |      3 |     8 |     4 |
| Override render settings for a specific template   |      1 |    15 |     4 |
| Modify Settings > Hot reload plugin templates      |      1 |    10 |     3 |
| Modify Settings > Testing mode                     |      1 |    10 |     3 |
| Choose default template > Standard                 |      1 |     5 |     2 |
| Choose default template > Standard > Modal         |      1 |     5 |     2 |
| Choose default template > Standard > Transform     |      1 |     5 |     2 |
| Choose default template > Standard > Saga          |      1 |     5 |     2 |
| Choose default template > Standard > Class         |      1 |     5 |     2 |
| Choose default template > Planeswalker             |      1 |     5 |     2 |
| Choose default template > Planeswalker > Modal     |      1 |     5 |     2 |
| Choose default template > Planeswalker > Transform |      1 |     5 |     2 |
| Modify Settings > overwrite duplicates             |      1 |     4 |     2 |
| Modify Settings > force english formatting         |      1 |     3 |     1 |
| Modify Settings > output filetype                  |      1 |     2 |     1 |
| Modify Settings > Scryfall language                |      1 |     2 |     1 |
| Modify Settings > Scryfall sorting                 |      1 |     2 |     1 |
| Modify Settings > Scryfall sort order              |      1 |     2 |     1 |
| Modify Settings > scryfall extras                  |      1 |     2 |     1 |
| Modify Settings > scryfall unique                  |      1 |     2 |     1 |
