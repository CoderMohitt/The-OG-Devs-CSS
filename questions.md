Here are **50 questions** based on the topics, with a mix of **code-based** and **theory-based** questions:  

---

### **1. Basics of CSS (10 Questions)**  
#### **Code-Based:**  
1. What will be the background color of the paragraph below?  
   ```css
   p {
       background-color: red;
   }
   .box {
       background-color: blue;
   }
   #special {
       background-color: green;
   }
   ```
   ```html
   <p class="box" id="special">Hello CSS!</p>
   ```  
2. What is the output of the following code?  
   ```css
   div {
       width: 100px;
       height: 100px;
       padding: 20px;
       border: 5px solid black;
   }
   ```
   What will be the total width and height of the `div`?  
3. Given this code, what will be the text color of the paragraph?  
   ```css
   body {
       color: blue;
   }
   p {
       color: red !important;
   }
   .text {
       color: green;
   }
   ```
   ```html
   <p class="text">Hello World</p>
   ```  
4. Write a CSS rule to apply **Helvetica** font to all paragraphs.  
5. What does the `inherit` value do in CSS?  

#### **Theory-Based:**  
6. What is the difference between `em`, `rem`, and `px`?  
7. Explain the difference between **relative units** and **absolute units** in CSS.  
8. What is the difference between `rgba(255,0,0,0.5)` and `rgb(255,0,0)`?  
9. What happens if multiple conflicting CSS rules apply to the same element?  
10. What is the difference between `opacity` and `visibility` in CSS?  

---

### **2. Layout Basics (10 Questions)**  
#### **Code-Based:**  
11. What will be the output of the following CSS rule?  
   ```css
   div {
       display: inline-block;
       width: 100px;
       height: 100px;
       background-color: red;
   }
   ```
12. What happens when you set `display: none` on an element?  
13. Write a CSS rule to make all `<div>` elements behave like inline elements.  
14. Predict the output:  
   ```css
   div {
       position: absolute;
       top: 50px;
       left: 50px;
   }
   ```
15. Explain the difference between `static`, `relative`, `absolute`, and `fixed` positioning with an example.  

#### **Theory-Based:**  
16. What does `z-index` do, and how do you use it?  
17. What happens if you set `position: absolute` on a child element but don’t define `position` on the parent?  
18. How can you center a `div` horizontally and vertically using **only** CSS?  
19. What is the default value of the `position` property?  
20. What is `sticky` positioning, and how does it work?  

---

### **3. Width & Height Control (10 Questions)**  
#### **Code-Based:**  
21. What is the difference between `max-width: 100px` and `width: 100px`?  
22. What is the height of the `div` below?  
   ```css
   div {
       height: 50vh;
   }
   ```
23. Given this code, what happens when you resize the window?  
   ```css
   div {
       width: 80vw;
       height: 100px;
   }
   ```
24. Write a CSS rule to make an element take up 100% of the viewport height.  
25. How do you set a minimum height for an element?  

#### **Theory-Based:**  
26. What happens if you set both `min-width` and `max-width` on an element?  
27. What are `vh` and `vw` units?  
28. How can you make an element **expand to fill its parent container**?  
29. How does `min-height: auto` behave?  
30. What is the difference between `height: auto` and `height: 100%`?  

---

### **4. Float & Clear (10 Questions)**  
#### **Code-Based:**  
31. Predict the output:  
   ```css
   div {
       float: left;
       width: 50px;
       height: 50px;
       background: red;
   }
   ```
32. What happens when you float an element without setting its width?  
33. How can you prevent elements from wrapping around a floated element?  
34. How does `overflow: hidden` help clear floats?  
35. Write a CSS rule to make an image float to the right of a paragraph.  

#### **Theory-Based:**  
36. What is the purpose of the `clear` property in CSS?  
37. Why was float originally introduced in CSS?  
38. What is a **clearfix**, and why is it needed?  
39. What happens when a parent element contains only floated children?  
40. What is the difference between `float: left` and `float: right`?  

---

### **5. Inline vs Block Elements (10 Questions)**  
#### **Code-Based:**  
41. What happens when you set `display: block` on an `<a>` element?  
42. Predict the output of this CSS rule:  
   ```css
   span {
       display: block;
   }
   ```
43. How can you make a block element behave like an inline element?  
44. Given this code, explain why elements appear on separate lines:  
   ```html
   <div>Hello</div>
   <div>World</div>
   ```
45. How do you prevent an element from breaking onto a new line?  

#### **Theory-Based:**  
46. What is the difference between **inline** and **block** elements?  
47. What is an **inline-block** element, and how is it different from inline elements?  
48. Give three examples of block-level elements and three inline elements.  
49. Why does `display: inline` not allow setting `width` and `height`?  
50. What is the default `display` value of a `<span>` element?  

---

### **Final Notes**  
- Most questions are **code-based**, requiring practical understanding.  
- Some **theory-based** questions ensure conceptual clarity.  