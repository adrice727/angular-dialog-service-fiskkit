This is a version of Michael Conroy's Angular Dialog Service that was modified for Fiskkit.

A 'custom' method was added to the dialog service.  This method accepts three paramters:
  
 - state
 - loggedIn
 - initialVisit

The state paramter is parsed to create 'url' and 'controller' variables which are passed to the existing 'create' function.

The loggenIn and initialVisit parameters are used to determine which modal should be displayed.