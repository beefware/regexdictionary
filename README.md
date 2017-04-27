# regexdictionary
my regex dict-

MGPH:
^(?P<id>[\d]+)\s+(?P<username>.*?)?[\s\?]+(?P<email>[\S]+\@[\S]*)?\s+(?P<ip>\d{1,3}(?:\.\d{1,3}){3})?\s+(?P<hash>[a-zA-Z0-9]{32})[\:](?P<salt>.+?)$
