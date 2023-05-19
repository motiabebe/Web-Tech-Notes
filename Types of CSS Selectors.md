# Types of CSS Selectors

# 

CSS (Cascading Style Sheets) Selectors are used to select HTML elements that we want to style. There are several types of CSS selectors which are as follows:

1. **Element Selector:** This type of selector selects all HTML elements that have the same name as the one given in the selector. For example, if we want to style all the paragraphs on a webpage, we can use the following selector:
    
    ```
    p {
      color: red;
    }
    
    ```
    
2. **Class Selector:** This type of selector selects all HTML elements that have the same class attribute as the one given in the selector. For example, if we want to style all the elements with the class name "btn", we can use the following selector:
    
    ```
    .btn {
      background-color: black;
    	color: white;
    }
    
    ```
    
3. **ID Selector:** This type of selector selects the HTML element that has the same ID attribute as the one given in the selector. For example, if we want to style the element with the ID "header", we can use the following selector:
    
    ```
    #header {
      width: 100%
    	background-color: black
    }
    
    ```
    
4. **Universal Selector:** This type of selector selects all HTML elements on the page. For example, if we want to set the default font size for all elements on the page, we can use the following selector:
    
    ```
    * {
      font-size: 16px;
    }
    
    ```
    
5. **Attribute Selector:** This type of selector selects all HTML elements that have the same attribute and attribute value as the one given in the selector. For example, if we want to style all the elements with "href" attribute value as "[https://www.example.com](https://www.example.com/)", we can use the following selector:
    
    ```
    [href="<https://www.example.com>"] {
      color: black;
    	text-decoration: none;
    }
    
    ```
    
6. **Pseudo-class Selector:** This type of selector selects an HTML element based on its state or position in the document. For example, if we want to style the link when it is hovered over by the user, we can use the following selector:
    
    ```
    a:hover {
      text-decoration: underline;
    }
    
    ```