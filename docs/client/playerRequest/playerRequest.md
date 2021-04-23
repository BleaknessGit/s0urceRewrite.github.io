## Name

Tasking Packet

## Description

Used by the client to perform actions


## Raw Packet

`42["playerRequest",{"task":?,...}]`

## JSON

``` json
[
    "playerRequest",
    {
        "task": ?,
        ...
    }
]
```

## JSON Definition

!!! Note
    Refer to the [Tasks](/client/playerRequest/tasks/index.md) section for individual Task documentation
##### Main Object
| Key  | Type   | Example | Description     |
|------|--------|---------|-----------------|
| task | Number | ?       | Task ID         |
| ...  | ?      | ?       | Additional Data |