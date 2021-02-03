# MCEvent

## Importing the class

It might be required for you to import the package if you encounter any issues (like casting an Array), so better be safe than sorry and add the import at the very top of the file.
```zenscript
import crafttweaker.api.event.MCEvent;
```


## Methods

### hasResult

Return Type: boolean

```zenscript
MCEvent.hasResult() as boolean
myMCEvent.hasResult();
```
### isCancelable

Return Type: boolean

```zenscript
MCEvent.isCancelable() as boolean
myMCEvent.isCancelable();
```
### isCanceled

Return Type: boolean

```zenscript
MCEvent.isCanceled() as boolean
myMCEvent.isCanceled();
```
### setCanceled

Return Type: void

```zenscript
MCEvent.setCanceled(cancel as boolean) as void
```
| Parameter | Type     | Description             |
| --------- | -------- | ----------------------- |
| cancel    | boolean型 | No Description Provided |


## Properties

| 名称         | Type     | Has Getter | Has Setter |
| ---------- | -------- | ---------- | ---------- |
| cancelable | boolean型 | true       | false      |
| canceled   | boolean型 | true       | true       |
| hasResult  | boolean型 | true       | false      |
