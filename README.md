# ionic-unnamed-tabs
Test repo to show issue with unnamed tabs route

## The issue
I want to use ionic tabs, but I don't want the route to "tabs" to have the name "tabs".  
I don't want `myapp.com/tabs/tab1`, I want `myapp.com/tab1`.

Remove the name "tabs" from all the routing causes the tabs to not work.

I can navigate directly to the tab urls and the component will load, but the tab buttons don't activate, and they will go to the wrong url.

If I'm on tab1, the tab2 link will try to route to "tab1/tab2" which fails, instead of just going to the route "tab2".

Is there no way to have the main tabs route be "unnamed"?
