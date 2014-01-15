folding-layout-library
======================

Source repository for Android Folding Layout library, written by Daniel Olshansky

Building
----------------------
First, make sure that your local.properties file has been updated with the current
location of your Android SDK.

You can build the library by running:
<code>
  $ ant clean jar
</code>

This will generate a 'FoldingLayout.jar' file in bin/ which can be imported into
other applications for use. Note that the library itself does not require anything
later than API version 11 for use, but the corresponding test application requires
version 17.

Test Application
----------------------
<TBD>
