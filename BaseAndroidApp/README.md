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