# MySQL Documentation
> Ref: https://www.markdownguide.org/cheat-sheet/
## Creating a database
`CREATE DATABASE [IF NOT EXISTS] database_name;`

## Using a Database
`USE database_name;`

## Permanently Delete (Drop) a Database
`DROP DATABASE [IF EXISTS] database_name;`

## Show all databases
`SHOW DATABASE;`

## Show all tables
`SHOW TABLES;`

## Create new table
```
CREATE TABLE [IF NOT EXISTS] table_name(
  column_list
);
```

## Selecting or Querying Fields
`select field_name`

## Query Distinct Elements
`select distinct field_name`

## Specifying Table
`from table_name`

## Conditioning
`where`

## Arithmetics

- Modulus : `mod(Dividend, Divisor)`
- Finding Even Number : `mod(Dividend, Divisor) = 0`
- Finding Odd Number : `mod(Dividend, Divisor) <> 0`

## Regular Expression
- Pattern Matching Operation
- Syntax : `regexp 'a'`
- Reference : https://www.geeksforgeeks.org/mysql-regular-expressions-regexp/

| Pattern | Description |
| ----------- | ----------- |
|* |	Zero or more instances of string preceding it |
|+ | One or more instances of strings preceding it|
|. | Any single character|
|? |Match zero or one instances of the strings preceding it.|
|^ |caret(^) matches Beginning of string|
|$ |End of string|
|[abc] | Any character listed between the square brackets|
|[^abc]| Any character not listed between the square brackets|
|[A-Z] |match any upper case letter.|
|[a-z] |match any lower case letter|
|[0-9] |match any digit from 0 through to 9.|
|[[:<:]]	|matches the beginning of words.|
|[[:>:]]  |matches the end of words.|
|[:class:]	|matches a character class i.e. [:alpha:] to match letters, [:space:] to match white space, [:punct:] is match punctuations and [:upper:] for upper class letters|
|{n}	|n instances of preceding element|
|{m,n}	|m through n instances of preceding element|
|p1(bar)p2(bar)p3	| Alternation; matches any of the patterns p1, p2, or p3|

## Exit
`exit;`