# Broken Hash
50 points
> Those are a lot of hashes on the OwnForAll site

## Solving it

We are given a web page that looks like this:

![Hashes](https://github.com/DigiBrkr/csaw_hsf_qualifier_2017_BrokenHash_50/blob/master/hashes.PNG?raw=true)

After looking through it for a moment we see a hash that is like no other:
`flag{33C5D4954DA881814420F3BA39772644}`.
It looks like it could be an [MD5](https://en.wikipedia.org/wiki/MD5) hash, so the first thing to try is an MD5 [decoder](http://www.md5online.org/). Running `33C5D4954DA881814420F3BA39772644` through the decoder gets us this:
`crackme`. And there is our flag:

`flag{crackme}`  
