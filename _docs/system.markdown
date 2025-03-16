---
title: Unit system
permalink: /docs/system/
---

# Description

Core System Unit

# Overview

## Functions

| Name | Declaration |
| ------ | ------ |
| [CompareStr](#CompareStr) | function CompareStr( S1,S2 : string) : integer; |
| [Str](#Str) | function Str(value: integer):string; |

## Procedures

| Name | Declaration |
| ------ | ------ |
| [freemem](#freemem) | procedure freemem(var F: PChar); |
| [AssignFile](#AssignFile) | procedure AssignFile(var F: File;FileName: String); external; |
| [CloseFile](#CloseFile) | procedure CloseFile(var F: File); external; |
| [inc](#inc) | Procedure inc(var value: integer); |
| [inc](#inc) | Procedure inc(var value: int64); |
| [dec](#dec) | Procedure dec(var value: integer); |
| [dec](#dec) | Procedure dec(var value: int64); |
| [reset](#reset) | Procedure reset(var F: file); external; |
| [Readln](#Readln) | procedure Readln(var F: File; var value: string); external; |

## Types

| Name | Description |
| ------ | ------ |
| PChar = ^char; |  |

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

## Str
### Description


# Procedures

## freemem
### Description
Releases the given memory
## AssignFile
### Description
assignes the filename to the file F  
### Params

| Name | Description |
| ------ | ------ |
| F | file to be asssigned |
| FileName | name of the file |

## CloseFile
### Description

## inc
### Description

## inc
### Description

## dec
### Description
decreases the value by one 
### Params

| Name | Description |
| ------ | ------ |
| value | to be decreased |

## dec
### Description
decreases the value by one 
### Params

| Name | Description |
| ------ | ------ |
| value | to be decreased |

## reset
### Description
opens the file for reading
## Readln
### Description
 
### Params

| Name | Description |
| ------ | ------ |
| F | file to read |
| value | string to read the file into |
