# scala.react

Scala.react is a reactive programming library for Scala.


This fork is for getting scala.react to run on Android.

## Eclipse setup
Here are my Eclipse 4.2 Update Sites (you can import them like this as well)
```
<?xml version="1.0" encoding="UTF-8"?>
<bookmarks>
   <site url="https://androidproguardscala.s3.amazonaws.com/UpdateSiteForAndroidProguardScala" selected="true" name="Exported Repository"/>
   <site url="http://download.eclipse.org/releases/juno" selected="true" name="Juno"/>
   <site url="http://download.scala-ide.org/ecosystem/dev-master-2.9/site/" selected="true" name="org.scala-ide.ecosystem"/>
   <site url="http://download.scala-ide.org/ecosystem/dev-milestone-milestone/site/" selected="true" name="org.scala-ide.ecosystem"/>
   <site url="http://download.scala-ide.org/nightly-update-juno-master-29x/" selected="true" name="org.scala-ide.sdt.update-site"/>
   <site url="http://download.eclipse.org/eclipse/updates/4.2" selected="true" name="The Eclipse Project Updates"/>
   <site url="https://dl-ssl.google.com/android/eclipse/" selected="true" name="update site: https://dl-ssl.google.com/android/eclipse/"/>
</bookmarks>
```
And here are the plugins that I installed from those sites
```
  Android/Proguard/Scala Feature	0.0.41.201206161034	com.restphone.androidproguardscala.feature.feature.group	null
  Android Development Tools	20.0.3.v201208082019-427395	com.android.ide.eclipse.adt.feature.group	The Android Open Source Project
  JDT Weaving for Scala	2.1.0.nightly-2_09-201211081225-e8d18cb	org.scala-ide.sdt.weaving.feature.feature.group	scala-ide.org
  Scala IDE for Eclipse	2.1.0.nightly-2_09-201211081225-e8d18cb	org.scala-ide.sdt.feature.feature.group	scala-ide.org
```
Then you need to add the following natures to your project
- Scala
- Android
- AndroidProguardScala

