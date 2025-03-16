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


# Procedures
