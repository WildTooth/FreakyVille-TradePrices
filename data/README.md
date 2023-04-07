# How to contribute to the file

## Rules

#### 1. Do not change prices which are untrue, it'll be checked anyways.
#### 2. Do not add items you are not certain there are "duplicates" of (E.g. Heads with the same name). It will be fixed later, but until then this rule still applies.

## Value Meanings?

#### 1. String[name]         | This describes the displayname of the Item.
#### 2. int[minPrice]        | This describes the minimal value of the Item.
#### 3. int[maxPrice]        | This describes the maximum value of the Item.
#### 4. boolean[isSkullItem] | This describes wether or not the item is a skull.
#### 5. boolean[isInBlocks]  | This describes wether the items price is disclosed in diamond blocks or pure diamonds.

## Example

```csv
Diamond Sword,1,9,false,false
```

## What not to do

```
Dirt,10 Stacks,20 Stacks,true,false
```
