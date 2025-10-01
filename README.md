# Search

cli tool example of using [taybart/rest](https://github.com/taybart/rest) to search kagi's fastgpt and search apis.

```sh

$ search -h
Usage: search [options] [query]
Options:
  -b                  Show balance
  -t                  terse, append "make it short and sweet" for fastgpt
  -l 5                Limit number of results from search api (default 5)
  -s                  Use search api instead of fastgpt
  -h                  Show help

$ search -s -l 2 ken thompson
-> ken thompson

[1] Ken Thompson - Wikipedia
    Kenneth Lane Thompson (born February 4, 1943) is an American pioneer of computer science. Thompson worked at Bell Labs for most of his career.
[2] Ken Thompson - UNIX memoir, in first person - YouTube
    UNIX memoir, in first person - Ken Thompson · Comments. 44. There's a special room in heaven with a sign above the door that says "Dennis and ...

$ search -t what was ken thompons best piece of software

-> what was ken thompons best piece of software please make it short and sweet

Ken Thompson's most impactful piece of software is widely considered to be Unix, which he co-created. [1]

[1] Dennis Ritchie - Wikipedia
```


### installation

1) clone into ~/.kagi
2) add ~/.kagi/bin to your $PATH
3) get an api token from your kagi account and put it in ~/.kagi/auth

