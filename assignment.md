## Assignment

In this assignment, you will learn to use the developer's tool to inspect the elements of [this](https://nznznh.csb.app/) webpage.

1. What is the right margin of the first element? 
```
50px
```

2. What is the top padding of the second element?
```
100px
```

3. What is the class name of the third element and the content of the css?
```
elementThree
```

4. What is the css selector of the fourth element?
```
The :nth-child () pseudo-class selector
```

5. What is the code you use to keep the blue box within the purple?
```
.parent {
        border: purple 8px solid;
        margin: 0;
        width: 500px;
      }

.child {
        width: 200px; /* Or any desired width */
        height: 100px; /* Or any desired height */
        box-sizing: border-box;
        border: 2px solid blue; /* Example border */
      }
<div class="parent">
      <div class="child">
        Keep the blue box within the purple box using the box-sizing property.
        You can edit the css code on the developer's tool.
      </div>
</div>
```

> hint: you should apply box-sizing property to the `.child` class. Make the changes on the developer's tool to see immediate UI change.



### Submission 

- Submit the URL of the GitHub Repository that contains your work to NTU black board.
- Always store your assignments in the `assignments` folder or `assignment.md` file.
- Should you reference the work of your classmate(s) or online resources, give them credit by adding either the name of your classmate or URL. 
