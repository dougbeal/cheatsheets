---
title: Ledger CSV format
category: Ledger
layout: 2017/sheet
---

## Ledger CSV format
{: .-one-column}

```
$ ledger csv
```
{: .-setup}

```csv
date         , code , desc     , account            , currency , amt     , pending/cleared , metadata
"2013/09/02" , ""   , "things" , "Assets:Cash"      , "P"      , "-2000" , "*"             , ""
"2013/09/02" , ""   , "things" , "Liabilities:Card" , "P"      , "-200"  , "*"             , ""
"2013/09/02" , ""   , "things" , "Expenses:Things"  , "P"      , "2200"  , "*"             , ""
"2013/09/04" , ""   , "stuff"  , "Assets:Cash"      , "P"      , "-20"   , "*"             , ""
"2013/09/04" , ""   , "stuff"  , "Expenses:Others"  , "P"      , "20"    , "*"             , ""
"2013/09/05" , "42" , "Check"  , "Assets:Checking"  , "P"      , "-20"   , "*"             , ""
"2013/09/05" , "42" , "Check"  , "Expenses:Pizza"   , "P"      , "20"    , "*"             , "
:FOOD:"
```
