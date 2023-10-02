# horiseon_accessible_v
Brief: Accessibility improvements for the Horiseon homepage.

This projects aim is to refactor the Horiseon homepage to make improvements to accessibility and code.

## Agile statement
This project is complete when
1. Semantic HTML elements can be found throughout the source code
2. HTML elements follow a logical structure independent of styling and positioning
3. Image and icon elements contain accessible alt attributes
4. Heading attributes fall in sequential order
5. Title elements contain a concise, descriptive title

## HTML script
Where appropriate, the project replaces use of non-semantic elements with semantic elements such as 
    <section>
    <footer>
    <title> 

The project further corrects a broken hyperlink in the original code.

HTML head section now includes desriptions and keywords providing summary of page contents and topics.

Alt text is added to all icons and images to provide information to users of screen readers.

Code has been rearranged to provide a logical order- grouping sections of related content and arranging content in a sequence based on browser rendering. The aim of which being to improve readability for subsequent edits.

The project also edits the structure to ensure that semantic elements such as <h> tags follow an order which reflects the precedence and importance of the content.

Comments are employed to help others understand code to aid future development.

## CSS script
The project condenses css code in line with DRY principles.

The project places css code in a logical sequence to increase readability for future edits and code review.

Ambiguous class names are replaced by descriptive class names to further bolster readability.

Comments are employed to help others understand code to aid future development.

Selectors appear in code in order of general to specific- placing the most general selectors towards the top of the style sheet and the most specific selectors towards lower down the style sheet.

## Link to deployed application ##

The following is a link to the outcome of the project hosted on Gitpages: 
    
<a href="https://ag466.github.io/horiseon_accessible_v/#online-reputation-management" target="_blank">Horiseon Homepage Accessible Version</a>

## Screenshots of deployment
The below images show the Horiseon homepage deployed at completion of this project:

![Screenshot 1 of 2 showing deployed webpage](<assets/images/deployment screenshot1.png>)
![Screenshot 2 of 2 showing deployed webpage](<assets/images/deployment screenshot 2.png>)

## Future improvements

The html and css in the project have been optimised for accessibility purposes through the following steps:

[1] Replacement of non-semantic elements with semantic elements
[2] Restructuring of HTML code to conform to logical order relating to browser display and relative importance of content.
[3] Addition of alt elements to images and icons
[4] Amendments to header elements to better link header choice with the importance of the information displayed
[5] Use of concise title tag

Further work may be undertaken to expand accessibility for alternative devices.

Incorporation of audio elements such as sound files or videos would improve the general accessibility of the homepage. Such additions however lie beyond the optimisation of existing content- which was the concern of this project.