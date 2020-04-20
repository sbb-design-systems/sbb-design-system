## 1. What does the component do?
It scrolls through a list of elements or pages.

## 2. When should the component be used?
For long lists of elements or pages.

## 3. Rules
* The number of elements per page must be defined on a context-specific basis.

## 4. Variants and statuses 
### 4.1 Numbers
The component has the following statuses:
* First
* Middle
* Last
* Hover

![Image of the pagination component with numbers](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/pagination/images/pagination_numbers.png 'class: image')
* A maximum of five page numbers are shown.
* Keyboard operation:
    * The active page cannot be jumped to.
    * Tab sequence: Arrow back, first page that can be jumped to, next page that can be jumped to etc., arrow forward.
    * The abbreviated form ‘…’ for hidden pages cannot be jumped to.

#### Design specification
* [First](https://sbb.invisionapp.com/d/main#/console/15744722/328136679/inspect)
* [Middle](https://sbb.invisionapp.com/d/main#/console/15744722/328136680/inspect)
* [Last](https://sbb.invisionapp.com/d/main#/console/15744722/328136681/inspect)
* [Hover](https://sbb.invisionapp.com/d/main#/console/15744722/328136682/inspect)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/content/pagination)

### 4.2 Page names
This variant has the following statuses:
* Default
* Hover

![Image of the pagination component with page names](https://raw.githubusercontent.com/sbb-design-systems/design-system-website-documentation/master/documentation/components/pagination/images/pagination_pages.png 'class: image')
* Can contain ‘forward’ and ‘back’ link, or optionally just ‘forward’ or ‘back’ (when the first or last page is active).
* The pagination links with the title of the page to be jumped to are labelled.
* The link text has a maximum width in line with the layout. Longer texts are cut using ‘…’.

#### Design specification
* [Default](https://sbb.invisionapp.com/d/main#/console/15744722/328136683/inspect)
* [Hover](https://sbb.invisionapp.com/d/main#/console/15744722/328136684/inspect)

#### Code specification
* [SBB Angular Component Library](https://sbb-angular.app.sbb.ch/latest/content/pagination)