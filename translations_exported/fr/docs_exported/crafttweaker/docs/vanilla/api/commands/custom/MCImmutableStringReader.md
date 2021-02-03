# Lecteur de chaînes de caractères MCImmutable

## Importing the class

It might be required for you to import the package if you encounter any issues (like casting an Array), so better be safe than sorry and add the import at the very top of the file.
```zenscript
import crafttweaker.api.commands.custom.MCImmutableStringReader;
```


## Methods

### canRead

Return Type: boolean

```zenscript
MCImmutableStringReader.canRead() as boolean
myMCImmutableStringReader.canRead();
```
Return Type: boolean

```zenscript
MCImmutableStringReader.canRead(arg0 as int) as boolean
```
| Parameter | Type | Description             |
| --------- | ---- | ----------------------- |
| arg0      | int  | No Description Provided |

### getCursor

Return Type: int

```zenscript
MCImmutableStringReader.getCursor() as int
myMCImmutableStringReader.getCursor();
```
### getRead

Return Type: string

```zenscript
MCImmutableStringReader.getRead() as string
myMCImmutableStringReader.getRead();
```
### Rester en cours

Return Type: string

```zenscript
MCImmutableStringReader.getRemaining() as string
myMCImmutableStringReader.getRemaining();
```
### Obtenir la longueur restante

Return Type: int

```zenscript
MCImmutableStringReader.getRemainingLength() as int
myMCImmutableStringReader.getRemainingLength();
```
### getString

Return Type: string

```zenscript
MCImmutableStringReader.getString() as string
myMCImmutableStringReader.getString();
```
### Durée totale de lecture

Return Type: int

```zenscript
MCImmutableStringReader.getTotalLength() as int
myMCImmutableStringReader.getTotalLength();
```
### coup d'œil

Return Type: char

```zenscript
MCImmutableStringReader.peek() as char
myMCImmutableStringReader.peek();
```
Return Type: char

```zenscript
MCImmutableStringReader.peek(arg0 as int) as char
```
| Parameter | Type | Description             |
| --------- | ---- | ----------------------- |
| arg0      | int  | No Description Provided |

