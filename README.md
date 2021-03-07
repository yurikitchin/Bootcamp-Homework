# 01 HTML, CSS, and Git: Code Refactor mini assignment

<h1 align="center">Horiseon Refactoring</h1>

<h2>Purpose of Refactoring</h2>
<p> Horiseon has requested that our marketing agency refactor their existing code base to meet accesability standards so that their website is optimised for search engines. This requires the addition of alt attributes to imformative images, a refactoring of the code to make the elements semantic and easier to follow, a removal of repeated code in the HTML and CSS, and also to ensure all links function correctly </p> 

<h2> Method </h2>
<p>1. The first step was, starting from the top, to rename the div classes to accurately reflect their function

 change the div class="header", to the header element, add a section, and change ul to nav<br>
 Original code
![](2021-03-07-13-59-57.png)
Refactored code
![](2021-03-07-14-02-08.png)
</p>
<p>2. chavge div class content to main class content, to reflect main section of html, Alt attributes were also added to the img's to meet accessability standards.<br>
Original code
![](2021-03-07-14-08-42.png)
![](2021-03-07-14-08-55.png)
![](2021-03-07-14-09-06.png)
Refactored code
![](2021-03-07-14-09-44.png)
![](2021-03-07-14-09-53.png)
![](2021-03-07-14-10-06.png)
</p> 
<p>3. change dis class benefits, to an aside to represent the side bar, also added null alt attributes to the decorative imgs on all 3 sections.<br>
Original code
![](2021-03-07-14-13-26.png)
Refactored code
![](2021-03-07-14-14-26.png)
</p>
<p>4. changed div class footer, to footer element<br>
original code
![](2021-03-07-14-16-45.png)
refactored code
![](2021-03-07-14-17-11.png)
</p>

<p>5. fixed broken link for serach engine optimization, div was incorrectly labbeled as a class instead of an ID.<br>
Original code
![](2021-03-07-14-19-16.png)
![](2021-03-07-14-19-40.png)
Refactored code
![](2021-03-07-14-20-15.png)
![](2021-03-07-14-20-42.png)
</p>
<p>6. Split original CSS stylesheet into 3 new style sheets and remove duplicate code, to improve function and ease of interpertaion.


