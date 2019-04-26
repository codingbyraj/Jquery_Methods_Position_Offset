

The .position() method allows us to retrieve the current position of an element (specifically its margin box) relative to the offset parent (specifically its padding box, which excludes margins and borders).


The .offset() method allows us to retrieve the current position of an element (specifically its border box, which excludes margins) relative to the document. Contrast this with .position(), which retrieves the current position relative to the offset parent. When positioning a new element on top of an existing one for global manipulation (in particular, for implementing drag-and-drop), .offset() is more useful.





https://api.jquery.com/position/#position


### Position():

#### v1.10.2

pos.top-- 257.7099914550781

pos.left-- 1331.5

pos.top-- 257.5099792480469

pos.left-- 1331.5


#### v3.4.0

pos.top -- 0

pos.left -- 565

pos.top -- 0

pos.left -- 565





### Offset():

### v1.10.2

pos.top-- 257.7099914550781

pos.left-- 1331.5

pos.top-- 257.5099792480469

pos.left-- 1331.5


#### v3.4.0

pos.top-- 256

pos.left-- 1331.5

pos.top-- 256

pos.left-- 1331.5
