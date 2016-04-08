## Create a navigation bar ##

uicontrols.createNavigationBar();
## Hide a navigation bar ##

uicontrols.hideNavigationBar();
## Set a navigation bar title ##

uicontrols.setNavigationBarTitle("Hello World");
## Create a left button ##

uicontrols.setNavigationBarLeftButton({
> buttonType:"system",
> buttonId:navigationButton.SystemItemRefresh,
> onTap:function() {
> > alert("Left button was clicked");

> }
});
## Create a right button ##

uicontrols.setNavigationBarLeftButton({
> buttonType:"system",
> buttonId:navigationButton.SystemItemRefresh,
> onTap:function() {
> > alert("Right button was clicked");

> }
});
## Remove the left button ##

uicontrols.removeNavigationBarLeftButton();
## Remove the right button ##

uicontrols.removeNavigationBarRightButton();