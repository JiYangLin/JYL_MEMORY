# XPath

+ nodename  
选取此节点的所有子节点

+ /  
  从根节点选取(根节点为当前node的根节点),只选择当前节点的子节点

+ //
  从匹配选择的当前节点选择文档中的节点，不考虑它们的位置，选择子节点及子节点的任意深度节点

+ .  
  选取当前节点。

+ ..
  选取当前节点的父节点。

+ @  
  选取属性

+ `*`  
  选择所有内容

+ @*  
  选择所有属性

+ //title/text()  
  获取title标签包围的文字

+ //title[@lang]  
  选取所有拥有名为 lang 的属性的 title 元素。

+ //title[@lang='eng']  
  选取所有 title 元素，且这些元素拥有值为 eng 的 lang 属性。

+ //bookstore/book[price>35.00]  
  选取 bookstore 元素的所有 book 元素，且其中的 price 元素的值须大于 35.00。
