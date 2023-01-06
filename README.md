This is the Goals Manager project for the first Web Assignment (currently in phase one).
We have introduced some hardwired data into the html to evaluate the layout (since some functionalities can't be coded yet without JS).
These hardcoded bits will be removed in the following assignments.
Another thing would be the fact that we initially tried to use forms to navigate to other pages and send the necessary input data, but unfortunately the github.io service does not support the POST method (405 Not Allowed, while PUT is not supported by the FORM) and the GET method would insert the input information in the URL (which wasn't a choice - for the user credentials it is unacceptable and for the other use cases it would be messy). Since we removed the forms the information won't be validated locally, but it will be validated later through JS code.
