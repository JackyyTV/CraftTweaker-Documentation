# MCBlock

## Importing the class

It might be required for you to import the package if you encounter any issues (like casting an Array), so better be safe than sorry and add the import at the very top of the file.
```zenscript
import crafttweaker.api.blocks.MCBlock;
```


## Caster

| Tipo Risultato | Implicito |
| -------------- | --------- |
| string         | false     |

## Methods

### canSpawnInBlock

Return Type: boolean

```zenscript
MCBlock.canSpawnInBlock() as boolean
myMCBlock.canSpawnInBlock();
```
### getDefaultState

Return Type: [MCBlockState](/vanilla/api/blocks/MCBlockState)

```zenscript
MCBlock.getDefaultState() as MCBlockState
myMCBlock.getDefaultState();
```

## Properties

| Name           | Type   | Ha Getter | Ha Setter |
| -------------- | ------ | --------- | --------- |
| commandString  | string | true      | false     |
| lootTable      | string | true      | false     |
| translationKey | string | true      | false     |
