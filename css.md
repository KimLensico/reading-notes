# CSS Notes

## About CSS
- CSS allows you to create rules that control the way that each individual box (and contents of that box) is presented.
- Works by associating rules with HTML elements. 
  - rules govern how the content of spevified elements should be displayed
- CSS rule contains two parts:
    1. **selector** - indicates which element the rule applies to. can apply to more than one element.
    2. **declaration** - indicate how the elements referred to in the selector should be styled.
        - split into two parts: a property and a value. they are seperated by a colon. 
        - can specify several properties by a semi-colon
- can include CSS within an html page by placing them inside a ```<style>```  element. 
### How Rules Cascade
> if there are two or more rules that apply to the same element, it is important to understand which will take precedence!
- **last rule** - if the two selectors are identical, the latter of the two will take precidence. 
- **specify** - if one selector is more specific than the others, the more specific rule will take precedence over more general ones
- **important** - yyou can add ```!important``` after any property value to indicate that it should be considered more important than other rules that apply to the same element. 
### Inheritance
- you can force a lot of properties to inherit values from their parent elements by using ```inherit``` for the value of the properties.
### Style Sheets
- all web pages can share the same style sheet
- achieved by using the ```<link>``` element on each HTML page of your site to link to the same CSS doc. 
- this means that **the same code does not need to be repeated on every page!!** 
- allows the site to load faster 
- it's recommended that CSS should be put in a separate file 
