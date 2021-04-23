## Name

Start Packet

## Description

Used to connect the client to the game.<br>
Sent after Login button is pressed


## Raw Packet

`42["signIn",{"name":"waftest"}]`

## JSON

``` json
[
    "signIn",
    {
        "name": "TheWaffle"
    }
]
```

## JSON Definition

##### Main Object
| Key  | Type   | Example   | Description     |
|------|--------|-----------|-----------------|
| name | String | TheWaffle | Client Username |