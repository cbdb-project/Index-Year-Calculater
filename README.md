# Index-Year-Calculater

The index year generator for China Biographical Database project

# Description

We regard the birth year or calculated birth year as the index year for a historical figure. You can find the detail rules in Misc/*

# Requirements

Python >=3.6 (for f-string)

pandas

# Getting Started

Run Index Year Program.ipynb first, then you will get the output:

**output.csv** - the result for the index year calculation.

**error report.csv** - potential problematic data. For example, father's index year - son's index year >=100.

# How to generate INPUT files

**BIOG_MAIN**

c_personid

c_female 0,1>FALSE,TRUE

c_birthyear

c_deathyear

c_death_age

c_index_year

**ENTRY_DATA**

c_entry_code:

34

36

37

39

47

124

165

173

c_year:

not 0

not blank

**KIN_DATA**

c_personid

c_kin_code

c_kin_id



# Creator

Haoyuan Gao


# Contributors

Peter Bol, Michael Fuller, Song Chen, Hongsu Wang
