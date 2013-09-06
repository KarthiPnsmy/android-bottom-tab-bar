android-bottom-tab-bar
======================

Appcelerator Titanium Android Bottom Tab Bar

###Bottom Tabgroup will be supported up to Titanium 3.0 only,  it will not be work for Titanium 3.X**

**Reason:**

    Before SDK 3.0, we used TabActivity to implement the TabGroup. Since TabActivity is deprecated, we now use TabHost to implement the TabGroup for API level < 11 in SDK 3.0. We define the TabHost layout in the code. That's why the custom TabHost layout xml file does not work anymore.
    Based on the guideline of Pure Android, the bottom tab bars are not recommended. In addition, for API level >= 11 we use ActionBar to implement the TabGroup, in which case tab bars can only be on the top. In order to provide a consistent experience, we don't recommend using bottom tab bars.

    AppC Jira Link : https://jira.appcelerator.org/browse/TIMOB-12220
