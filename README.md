## HtmlParser

Js library for parsing html document at document object model (DOM) with search support

### Features

* Not depends from any other libs;
* Compact size;
* Support css selectors (jQuery like queries).

### Api
Document::querySelectorAll()
Document::querySelector()
NodeElement::querySelectorAll()
NodeElement::querySelector()

Support: 
-	CSS selectors: >>, ' ', ~, >, +
-	pseudo classes: `:first-child()`, `:last-child()`, `:nth-child(even)`, `:nth-child(odd)`, `:nth-child(2n-1)`, `:nth-child(3)`,
-	attribute selectors: `[data]`, `[data=abc]`, `[data="abc"]`, `[data*=abc]`, `[data~=abc]`, `[data^=abc]`, `[data$=abc]`, `[data|=abc]`



## Implements of pseudo classes
Implemented:
- `:last-child`
- `:first-child`
- `:nth-child`
	
Not implemented:
- `:not()` - TODO;
- `:checked` - similar [checked];
- `:disabled` - similar [disabled].

examples:
* `li:nth-child(4-n)` - take first 4 nodes
* `:nth-child(2n+1)`
* `:nth-child(3)`
* `:nth-child(even)`
* `:nth-child(odd)`
