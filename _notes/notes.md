

Make the DOM object draggable
```
 <div class="fill" draggable="false"> </div>
``` 

Add css for drop-drop
```
.hold {
  border: solid 5px #ccc;
}

.hovered {
  background: #f4f4f4;
  border-style: dashed;
}
```


Add event handler for drag
```
  fill.addEventListener("dragstart", dragStart);
  fill.addEventListener("dragend", dragEnd);
```


Add event handler for drop
```
  empty.addEventListener("dragover", dragOver);
  empty.addEventListener("dragenter", dragEnter);
  empty.addEventListener("dragleave", dragLeave);
  empty.addEventListener("drop", dragDrop);
```