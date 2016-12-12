#Code 201 day 8

## Dec 7, 2016

Today we reviewed tables, and how to write them using the DOM in Js scripts. The HTML structure was supposed to look in this manner: the header & footer were both <th> and each row has a <tr> with it's appended <td>. So, first we needed to make a <tr> row ID <th>/<td>, then a for (array) => for that loops through an array. To do this we need the following code in this specific order:

    Each Row:

    Create tr

    Make row ID (th/td)

    for (array) => for that loops through an array {

    Create:         var el = document.createElement('')
    Give content:   el.textContent = ?content here?
    Append:         parent.appendChild(Child)
                    tr.appendChild(td)
                    table.appendChild(row)  
    }

    Make total cell: Create / Give Content / Append

    Append <tr> to table.

###How to set up to Use a form: (could be used for yesterday's lab)

####Code Organization (macro pattern)

####Set Up data
  Var declarations
  Constructor & Instances (Object Constructors and Objects)

####Define Behaviors/Actions
  Functions declarations

####Execute/call/invoke Actions
  Function calls

####How this sets up to use a form:

#####Add HTML form

#####Add Js Listener

#####Add Js Event
  Invoke Handler
  Harvests form data
  runs data through constructor
  re-renders entire table
