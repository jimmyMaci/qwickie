## This is an eclipse plugin for the Java Webframework Wicket from apache.org ##
**qwickie needs the IDE for Java EE Developers package (html editor)**

here's the eclipse update site: (!changed! since git migration)
```
http://qwickie.googlecode.com/git/qwickie.updatesite/
```
~~or for those who want to install manually look into the [downloads](http://code.google.com/p/qwickie/downloads/list) tab or~~<a href='http://marketplace.eclipse.org/marketplace-client-intro?mpc_install=1166' title='Drag and drop into a running Eclipse Indigo workspace to install qwickie'><img src='http://marketplace.eclipse.org/misc/installbutton.png' align='middle' /></a>~~Google Source downloads~~<a href='http://thenextweb.com/google/2013/05/22/google-codes-download-option-deprecated-due-to-misuse-only-existing-project-downloads-to-be-kept-after-january-15/'>are not supported anymore</a>

**Google Source ist shutting down!**

Current version: **1.1.8** 

Usage:

Just mouse click on the wicket:id while pressing ctrl in the java code editor<br>
<img src='http://qwickie.googlecode.com/git/qwickie.updatesite/doc/images/java.png' /><br>
<img src='http://qwickie.googlecode.com/git/qwickie.updatesite/doc/images/wicketcomponenthyperlink.png' />
<br>to open the default html editor and mark the clicked wicket:id.<br>
<br>
And - vice versa - mouse click on the wicket:id while pressing ctrl in the default html eclipse editor<br>
<img src='http://qwickie.googlecode.com/git/qwickie.updatesite/doc/images/html.png' /><br>
<img src='http://qwickie.googlecode.com/git/qwickie.updatesite/doc/images/wicket_message.png' />

Mouseover shows the line in html file<br>
<img src='http://qwickie.googlecode.com/git/qwickie.updatesite/doc/images/hover.png' />

Anyone having problems with mouseover on mac, please see <a href='http://code.google.com/p/qwickie/issues/detail?id=24&can=1'>http://code.google.com/p/qwickie/issues/detail?id=24&amp;can=1</a>


<h3>Features:</h3>

<ul><li>Navigate from java code elements to the corresponding html element via wicket:id<br>
</li><li>Show the corresponding html fragment from the java code element<br>
</li><li>Show the wicket:id line in the html file on mouse over<br>
</li><li>Rename HTML and properties (with variations) when renaming a wicketized java file (supertype Component)<br>
</li><li><a href='http://code.google.com/p/qwickie/issues/detail?id=8'>http://code.google.com/p/qwickie/issues/detail?id=8</a>  (find html files in other locations)<br>
</li><li><a href='http://code.google.com/p/qwickie/issues/detail?id=11'>http://code.google.com/p/qwickie/issues/detail?id=11</a> (jump to properties files)<br>
</li><li><a href='http://code.google.com/p/qwickie/issues/detail?id=21'>http://code.google.com/p/qwickie/issues/detail?id=21</a> (jump to xml files)<br>
</li><li><a href='http://code.google.com/p/qwickie/issues/detail?id=22'>http://code.google.com/p/qwickie/issues/detail?id=22</a> (support for other wicket namespaces)<br>
</li><li><a href='http://code.google.com/p/qwickie/issues/detail?id=17'>http://code.google.com/p/qwickie/issues/detail?id=17</a> (Wizard for new wicket pages)<br>
</li><li><a href='http://code.google.com/p/qwickie/issues/detail?id=23'>http://code.google.com/p/qwickie/issues/detail?id=23</a> (Quickfix to add missing components to onInitialize)<br>
</li><li><a href='http://code.google.com/p/qwickie/issues/detail?id=38'>http://code.google.com/p/qwickie/issues/detail?id=38</a> configure wicket id errors to be shown as error/warning/info.<br>
</li><li><a href='http://code.google.com/p/qwickie/issues/detail?id=38'>http://code.google.com/p/qwickie/issues/detail?id=38</a> configure wicket id check exclude paths. This is a per project setting. You can define a set of paths (comma separated) where qwickie doesn't check your wicket ids.<br>
</li><li>Code assist for wicket:id in Wicket Java files. e.g. new Label("<press Ctrl-Space>")<br>
<img src='http://qwickie.googlecode.com/git/qwickie.updatesite/doc/images/javaproposal.png' />
</li><li>Rename wicket:id and wicket id in a wicket component when renaming a property of a bean that is used as model. When a property with the same name is used in more than one bean, than it get's renamed too. Be careful when using this refactoring! It's just "like updating textual occurrences in comments and strings" and needs a preview.<br>
</li><li><a href='http://code.google.com/p/qwickie/issues/detail?id=42&can=1'>http://code.google.com/p/qwickie/issues/detail?id=42&amp;can=1</a> (control-option-1 to jump to the java file and control-option-2 to jump to the related HTML file.)<br>
</li><li>Fixed <a href='http://code.google.com/p/qwickie/issues/detail?id=34'>http://code.google.com/p/qwickie/issues/detail?id=34</a>. Thanks to Willem Voogd!<br>
</li><li>Autosave feature when deactivating eclipse and refreshing the browser window. (so no ctrl-s is needed). Removed to a <a href='http://code.google.com/p/eclatosa/'>new project</a>, because it's useful even not for wicket development.</li></ul>


<br>
There is a QWickie Nature available (now put in the project - configure menu), that checks if wicket:ids in html and java files are matching.<br>There where some errors reported and maintaining this thing is pretty time consuming so I decided to give you some settings.<br>
<img src='http://qwickie.googlecode.com/git/qwickie.updatesite/doc/images/nature.png' /><br>
<img src='http://qwickie.googlecode.com/git/qwickie.updatesite/doc/images/id_not_found.png' />
<img src='http://qwickie.googlecode.com/git/qwickie.updatesite/doc/images/id_not_found2.png' />
<img src='http://qwickie.googlecode.com/git/qwickie.updatesite/doc/images/quickfix.png' />
<br>
<br>
The preferences page (Window - Preferences - Web - QWickie)<br>
<br>
<img src='http://qwickie.googlecode.com/git/qwickie.updatesite/doc/images/project_settings.png' />