Instructions
A New Repository named MindArc

-----
Work1
-----
Build a responsive page based on the designs.

Solution:
--------

Developed responive design for both Desktop and Mobile devices. I have also added accessiblity attributes to the HTML Tags to be accessed by all users.

Just to avoid the performance issues, I haven't used background Images as that's best coding practice.

The layout has been designed using Flex Box.

No External libraries been used as its been Designed using only HTML and CSS so this can run directly on the browser without need for any servers.


-----
Work2
-----
Read the data.json file and display the data as tabs on desktop and an accordion on mobile.

Solution:
--------

The Implementation was performed using JQuery and CSS. The same container is being used as Tab in Desktop and accordion for Mobile.

The effects has been provided using JQuery for accordion. 

The animation effects are Implemented using CSS. 

Here I have provided two Index file ( Internal Json Data that can be access directly on the browser and an External Data that requires a server to be accessed) 


Bonus Question
Explain why the result of ('b' + 'a' + + 'a' + 'a').toLowerCase() is banana.

Explanation
-----------

- Values within quotes are always a string and + is a concatenation operator to combine strings.

- First two values 'b' and 'a' are concatenated to become ba

- The Next two plus(++) operator are called unary operator which represents an Increment sign but the string 'a' next to it will be considered not a number and an error output is thrown as NaN. [++ 'a']

- Now, the third string 'a' with the plus(+) operator combines it with the previous results. Hence it becomes (baNaNa).toLowercase()

- Finally, the toLowercase() method in Javascript returns the string into lower case making the resultant as banana.


-- Angika
