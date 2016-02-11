Lenient json parsing that ignores trailing commas, like

    ["foo","bar",]

and

    {
      "foo": "bar",
      "fox": "bax",
    }

Used for [json-cleaner](https://github.com/rubenmoor/json-cleaner), a command-line tool that removes trailing commas.

Forked from [bos/aeson](https://github.com/bos/aeson)