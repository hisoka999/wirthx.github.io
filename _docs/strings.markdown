---
title: Unit strings
permalink: /docs/strings/
---

# Description

Null-terminated string (PChar) routines.

# Overview

## Functions

| Name | Declaration |
| ------ | ------ |
| [CompareStr](#CompareStr) | function CompareStr( S1,S2 : string) : integer; |
| [AnsiCompareStr](#AnsiCompareStr) | function AnsiCompareStr( S1: string; S2: string ):Integer; |
| [strlen](#strlen) | function strlen(str : pchar) : int64; external 'c' name 'strlen'; |
| [stralloc](#stralloc) | function stralloc(L : int64) : pchar; |
| [strcat](#strcat) | function strcat( dest : pchar; src : pchar ): pchar; external 'c' name 'strcat'; |
| [strcomp](#strcomp) | function strcomp( str1 : pchar; str2 : pchar ): integer; external 'c' name 'strcmp'; |
| [strcopy](#strcopy) | function strcopy( dest : pchar; src : pchar ): pchar; external 'c' name 'strcpy'; |
| [strdispose](#strdispose) | function strdispose( str : pchar ): integer; external 'c' name 'free'; |
| [strecopy](#strecopy) | function strecopy( dest : pchar; src : pchar ): pchar; external 'c' name 'strcpy'; |
| [strend](#strend) | function strend( str : pchar ): pchar; external 'c' name 'strend'; |
| [tricomp](#tricomp) | function tricomp( str1 : pchar; str2 : pchar ): integer; external 'c' name 'strcmp'; |
| [stripos](#stripos) | function stripos( str1 : pchar; str2 : pchar ): integer; external 'c' name 'stristr'; |
| [striscan](#striscan) | function striscan( str : pchar; ch : char ): pchar; external 'c' name 'strchr'; |
| [strlcat](#strlcat) | function strlcat( dest : pchar; src : pchar; maxlen : integer ): pchar; external 'c' name 'strncat'; |
| [strlcopy](#strlcopy) | function strlcopy( dest : pchar; src : pchar; maxlen : integer ): pchar; external 'c' name 'strncpy'; |
| [strlen](#strlen) | function strlen( str : pchar ): int64; external 'c' name 'strlen'; |
| [strlicomp](#strlicomp) | function strlicomp( str1: pchar; str2: pchar; l: integer ):integer; external 'c' name 'strncasecmp'; |
| [strlower](#strlower) | function strlower( str : pchar ): pchar; external 'c' name 'strlwr'; |
| [strmove](#strmove) | function strmove( dest: pchar; source: pchar; l: int64 ):pchar; external 'c' name 'memcpy'; |
| [strnew](#strnew) | function strnew( str : pchar ): pchar; external 'c' name 'malloc'; |
| [strpas](#strpas) | function strpas( str : pchar ): string; external 'c' name 'strdup'; |
| [strpcopy](#strpcopy) | function strpcopy( dest : pchar; src : string ): pchar; external 'c' name 'strcpy'; |
| [strpos](#strpos) | function strpos( str1 : pchar; str2 : pchar ): pchar; external 'c' name 'strstr'; |
| [strriscan](#strriscan) | function strriscan( str : pchar; ch : char ): pchar; external 'c' name 'strrchr'; |
| [strrscan](#strrscan) | function strrscan( str : pchar; ch : char ): pchar; external 'c' name 'strchr'; |
| [strscan](#strscan) | function strscan( str : pchar; ch : char ): pchar; external 'c' name 'strchr'; |
| [strupper](#strupper) | function strupper( str : pchar ): pchar; external 'c' name 'strupr'; |

## Structures and Classes

# Functions

## CompareStr
### Description
returns 1 if the string S2 is greater then S1, -1 if the string is smaller and 0 if both are equal   
### Params

| Name | Description |
| ------ | ------ |
| S1 | first string to compare |
| S2 | second string to compare with |

## AnsiCompareStr
### Description
AnsiCompareStr compares two strings and returns the following result:
## strlen
### Description
returns the length of the given pointer to a character 
### Params

| Name | Description |
| ------ | ------ |
| str | null terminated string |

## stralloc
### Description
Allocate memory for a new null-terminated string on the heap 
## strcat
### Description
Concatenate 2 null-terminated strings.   
### Params

| Name | Description |
| ------ | ------ |
| dest | destination string |
| src | source string |

## strcomp
### Description
Compare 2 null-terminated strings, case sensitive.   
### Params

| Name | Description |
| ------ | ------ |
| str1 | first string to compare |
| str2 | second string to compare |

## strcopy
### Description
Copy a null-terminated string 
## strdispose
### Description
disposes of a null-terminated string on the heap
## strecopy
### Description
Copy a null-terminated string, return a pointer to the end.
## strend
### Description
{ Return a pointer to the end of a null-terminated string
## tricomp
### Description
Compare 2 null-terminated strings, case insensitive.
## stripos
### Description
Return the position of a substring in a string, case insensitive.
## striscan
### Description
Scan a string for a character, case-insensitive
## strlcat
### Description
Concatenate 2 null-terminated strings, with length boundary.
## strlcopy
### Description
Copy a null-terminated string, limited in length.
## strlen
### Description
Length of a null-terminated string.
## strlicomp
### Description
Compare limited number of characters in 2 null-terminated strings, ignoring case.
## strlower
### Description
Convert null-terminated string to all-lowercase.
## strmove
### Description
Move a null-terminated string to new location.
## strnew
### Description
Allocate room for new null-terminated string.
## strpas
### Description
Convert a null-terminated string to a shortstring.
## strpcopy
### Description
Copy a pascal string to a null-terminated string
## strpos
### Description
Search for a null-terminated substring in a null-terminated string
## strriscan
### Description
Scan a string reversely for a character, case-insensitive
## strrscan
### Description
Find last occurrence of a character in a null-terminated string.
## strscan
### Description
Find first occurrence of a character in a null-terminated string.
## strupper
### Description
Convert null-terminated string to all-uppercase

# Procedures
