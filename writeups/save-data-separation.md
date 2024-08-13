# Separating player save data from player state
TODO
```luau
type PlayerEntity = {
    player: Player,
    isDataLoaded: bool,
    onChanged: Signal,
}

local PlayerEntity = {}

function PlayerEntity.new(player: Player): PlayerEntity

local PlayerSaveData = {}

function PlayerSaveData.loadData(playerEntity: PlayerEntity, saveData: PlayerSaveData)
function PlayerSaveData.fromEntity(playerEntity: PlayerEntity): PlayerSaveData
```

## Turning PlayerEntity into save data
TODO

## Turning save data into PlayerEntity
TODO

## Saving and autosaving
TODO

## Session locking
TODO
