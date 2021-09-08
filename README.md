# Will_Paginate Styling to look like Bootstrap

The styling in the file is the exact styling to make it look like bootstrap.

Most people also want to center the pagination as well. 

If that is the case then do following. 

Give the div surrounding Will_Paginate an id of paginate and then add the css below to your file:

Example div:

        <div id="paginate">
          <%= will_paginate @articles %>
        </div>
        
Css to add to your file:      

#paginate nav {
  margin-left:auto;
  margin-right:auto;
}
