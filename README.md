# horiseon_accessible_v
Brief: Accessibility improvements for the Horiseon homepage.

This projects aim is to refactor the Horiseon homepage to make improvements to accessibility and code.

## agile statement ##
This project is complete when
1. Semantic HTML elements can be found throughout the source code
2. HTML elements follow a logical structure independent of styling and positioning
3. Image and icon elements contain accessible alt attributes
4. Heading attributes fall in sequential order
5. Title elements contain a concise, descriptive title

## html script##
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

## css script##
The project condenses css code in line with DRY principles.

The project places css code in a logical sequence to increase readability for future edits and code review.

Ambiguous class names are replaced by descriptive class names to further bolster readability.

Comments are employed to help others understand code to aid future development.

Selectors appear in code in order of general to specific- placing the most general selectors towards the top of the style sheet and the most specific selectors towards lower down the style sheet.

## link to deployed application ##

The following is a link to the outcome of the project hosted on Gitpages: 
    
<a href="https://ag466.github.io/horiseon_accessible_v/#online-reputation-management" target="_blank">Horiseon Homepage Accessible Version</a>


