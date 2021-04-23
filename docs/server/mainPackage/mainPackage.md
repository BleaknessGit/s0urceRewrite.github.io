## Name

Tasking Packet

## Description

Used by the client to perform actions


## Raw Packet

`42["mainPackage",{"unique":[{"task":?,...},...]}]`

## JSON

``` json
[
    "mainPackage",
    {
        "unique": [
            {
                "task": ?,
                ...
            },
            ...
        ]
    }
]
```

## JSON Definition

!!! Note
    Refer to the [Tasks](/server/mainPackage/tasks/index.md) section for individual Task documentation
##### Main Object
| Key    | Type  | Example | Description            |
|--------|-------|---------|------------------------|
| unique | Array | ...     | Array of Task Object's |

##### Task Object
| Key  | Type   | Example | Description     |
|------|--------|---------|-----------------|
| task | Number | ?       | Task ID         |
| ...  | ?      | ?       | Additional Data |