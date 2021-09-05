# Improvement #
* In "libs\books\feature\src\lib\book-search\book-search.component.ts" file Unsubscribe for subscribe observable in nnDestory lifecyle hook. Or we shoul duse async pipe. A Subscription essentially just has an unsubscribe() function to release resources or cancel Observable executions.
* Component function should be arrange alphabetacally or public private order. It will help out to developer to reach out easily.
* All the template string should be come from constant/json file. So that later if we required we can implement translations 

**Note** First Improvement fixed in "libs\books\feature\src\lib\book-search\book-search.component.ts" by using async pipe

# Accessibility Lighthouse # 
* Names and labelsThese are opportunities to improve the semantics of the controls in your application. This may enhance the experience for users of     assistive technology, like a screen reader.
* Buttons do not have an accessible name
ContrastThese are opportunities to improve the legibility of your content. Background and foreground colors do not have a sufficient contrast ratio.

# Accessibility manually # 
* Alternate text or role for search book image 
* Mat-Drawer content landmarks
* Color ratio issue on h1 title on backdrop open.


**Note** All Above Accessibility issue fixed.

