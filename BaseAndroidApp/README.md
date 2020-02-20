# Base Android APP

Documentations

## Modify

filename

```AppleScript

Abhijeets-MacBook-Air:BaseAndroidApp abhijeet$ find . -name "BaseAndroidApp*"
./BaseAndroidApp.iml
./.idea/BaseAndroidApp.iml

```
update below files with correct App name

```AppleScript

Abhijeets-MacBook-Air:BaseAndroidApp abhijeet$ grep -R "BaseAndroidApp" *
BaseAndroidApp.iml:<module external.linked.project.id="BaseAndroidApp" external.linked.project.path="$MODULE_DIR$" external.root.project.path="$MODULE_DIR$" external.system.id="GRADLE" type="JAVA_MODULE" version="4">
app/src/main/res/values/strings.xml:    <string name="app_name">BaseAndroidApp</string>
settings.gradle:rootProject.name='BaseAndroidApp'

```

some more files

```AppleScript

Abhijeets-MacBook-Air:BaseAndroidApp abhijeet$ grep -R --exclude-dir="app/build" "myfirstandroidapp" *
app/build.gradle:        applicationId "fit.crushit.myfirstandroidapp"
app/src/androidTest/java/fit/crushit/myfirstandroidapp/ExampleInstrumentedTest.java:package fit.crushit.myfirstandroidapp;
app/src/androidTest/java/fit/crushit/myfirstandroidapp/ExampleInstrumentedTest.java:        assertEquals("fit.crushit.myfirstandroidapp", appContext.getPackageName());
app/src/test/java/fit/crushit/myfirstandroidapp/ExampleUnitTest.java:package fit.crushit.myfirstandroidapp;
app/src/main/AndroidManifest.xml:    package="fit.crushit.myfirstandroidapp">
app/src/main/java/fit/crushit/myfirstandroidapp/MainActivity.java:package fit.crushit.myfirstandroidapp;

```

some more folders

```AppleScript

Abhijeets-MacBook-Air:BaseAndroidApp abhijeet$ find . -name "myfirstandroidapp"
./app/src/main/java/fit/crushit/myfirstandroidapp
./app/src/androidTest/java/fit/crushit/myfirstandroidapp
./app/src/test/java/fit/crushit/myfirstandroidapp

```

