# algorithm assignment

### Knight positions

### Problem
Write a function which accepts an array of chess pawns on the board, and returns an array of possible positions for [the knight](https://en.wikipedia.org/wiki/Knight_(chess)) that it is able to capture the most chess pawns.

```
function knightPositions(pawnPositions) {

}
```

#### Example 1
**Input:** `["a1", "b6", "c3", "e5", "f8", "h4"]`<br/>
**Output:** `["g6"]`<br/>
<img width="537" alt="Screen Shot 2021-08-31 at 11 51 42" src="https://user-images.githubusercontent.com/1154740/131465593-9f1c7e60-8e4d-4b41-87ca-7d5f4c196f07.png">
<br/>
**Explanation:** g6 is the best position because that position allows the knight to capture 3 pawns.
<br/>
#### Example 2
**Input:** `["a1", "b6", "c3", "f8", "h4"]`<br/>
**Output:** `["a4", "d5", "d7", "g6"]`<br/>
<img width="544" alt="Screen Shot 2021-08-31 at 15 15 44" src="https://user-images.githubusercontent.com/1154740/131467537-4dff72f3-661b-49de-b01c-1cb04a585968.png">
<br/>
**Explanation:** the output is `["a4", "d5", "d7", "g6"]` because these positions allow the knight to capture 2 pawns.


