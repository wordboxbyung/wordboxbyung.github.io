---
layout: page
permalink: /faq_import_words_from_file/
---
**How to import words from file?**
1. Create a file containing words for `WordBox` with extension `json` or `ung`. `Example.json` below contains `amicable`, `bellicose`, etc..
{
    "roots": [
        {
            "key": "AM",
            "info": "From the Latin amare, meaning 'to love.'"
        },
        {
            "key": "BELL",
            "info": "From Latin word, meaning 'war.'"
        },
        ...
    ],
    "words":[
        {
            "name": "amicable",
            "root": "AM",
        },
        {
            "name": "bellicose",
            "root": "BELL",
        },
        ...
    ]
}
