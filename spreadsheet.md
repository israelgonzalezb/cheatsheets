---
title: Spreadsheet functions
layout: 2017/sheet
---

### If

    =IF(test, then, else)
    =IF(EQ(A1, "paid"), "true", "false")

### Comparators

    =EQ(a,b) NE()
    =GT() GTE() LT() LTE()
    
### Math

    =POW(2, 32)   # 2^32
    =SIN() ACOS() etc
    =CEILING(n,sig,mode)
    =FLOOR(n,sig,mode)
    =INT(n)

    =SUM(range)

    =SUMIF(range, criteria, sum_range)
    =SUMIF(A1:A5, ">300", B1:B5)          # if A# is >300, use B#

### Core

    =TO_DATE(number)

### Vlook

    =VLOOKUP(value, range, column_index)

