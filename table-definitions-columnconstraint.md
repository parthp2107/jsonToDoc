---
layout: default
title: Bigquery Property Id
permalink: /bigquery-properties-id.md/
---
# Untitled string in Table entity Schema

```txt
https://streaminlinedata.ai/entity/data/table.json#/definitions/column/properties/columnConstraint
```

Column constraint

| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                   |
| :------------------ | :--------- | :------------- | :---------------------- | :---------------- | :-------------------- | :------------------ | :----------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [table.json*](table.md "open original schema") |

## columnConstraint Type

`string`

## columnConstraint Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value           | Explanation |
| :-------------- | :---------- |
| `"NULL"`        |             |
| `"NOT_NULL"`    |             |
| `"UNIQUE"`      |             |
| `"PRIMARY_KEY"` |             |

## columnConstraint Default Value

The default value is:

```json
"NULL"
```
