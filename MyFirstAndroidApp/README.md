# My First Android APP

Documentations

## Files

list files

```AppleScript
Abhijeets-MacBook-Air:MyFirstAndroidApp abhijeet$ pwd
/Users/abhijeet/AndroidStudioProjects/MyFirstAndroidApp
Abhijeets-MacBook-Air:MyFirstAndroidApp abhijeet$ ls -lrt
total 72
-rw-r--r--  1 abhijeet  staff   558 Feb 20 11:01 build.gradle
drwxr-xr-x  3 abhijeet  staff    96 Feb 20 11:01 gradle
-rwxr--r--  1 abhijeet  staff  5296 Feb 20 11:01 gradlew
-rw-r--r--  1 abhijeet  staff  2260 Feb 20 11:01 gradlew.bat
-rw-r--r--  1 abhijeet  staff   438 Feb 20 11:01 local.properties
-rw-r--r--  1 abhijeet  staff    52 Feb 20 11:01 settings.gradle
-rw-r--r--  1 abhijeet  staff   950 Feb 20 11:01 MyFirstAndroidApp.iml
-rw-r--r--  1 abhijeet  staff  1073 Feb 20 11:02 gradle.properties
drwxr-xr-x  9 abhijeet  staff   288 Feb 20 11:02 app
-rwxr-xr-x  1 abhijeet  staff  3712 Feb 20 13:07 README.md

Abhijeets-MacBook-Air:MyFirstAndroidApp abhijeet$ cd app/
Abhijeets-MacBook-Air:app abhijeet$ ls -lrt
total 40
drwxr-xr-x  2 abhijeet  staff     64 Feb 20 11:01 libs
drwxr-xr-x  5 abhijeet  staff    160 Feb 20 11:01 src
-rw-r--r--  1 abhijeet  staff    751 Feb 20 11:01 proguard-rules.pro
-rw-r--r--  1 abhijeet  staff    937 Feb 20 11:01 build.gradle
drwxr-xr-x  5 abhijeet  staff    160 Feb 20 11:01 build
-rw-r--r--  1 abhijeet  staff  12127 Feb 20 11:02 app.iml

Abhijeets-MacBook-Air:app abhijeet$ cd src/
Abhijeets-MacBook-Air:src abhijeet$ ls -lrt
total 0
drwxr-xr-x  3 abhijeet  staff   96 Feb 20 11:01 androidTest
drwxr-xr-x  3 abhijeet  staff   96 Feb 20 11:01 test
drwxr-xr-x  5 abhijeet  staff  160 Feb 20 11:02 main

Abhijeets-MacBook-Air:src abhijeet$ cd main/
Abhijeets-MacBook-Air:main abhijeet$ ls -lrt
total 8
drwxr-xr-x   3 abhijeet  staff   96 Feb 20 11:01 java
drwxr-xr-x  12 abhijeet  staff  384 Feb 20 11:01 res
-rw-r--r--   1 abhijeet  staff  723 Feb 20 11:02 AndroidManifest.xml
Abhijeets-MacBook-Air:main abhijeet$

Abhijeets-MacBook-Air:main abhijeet$ cd java/
Abhijeets-MacBook-Air:java abhijeet$ ls -lrt
total 0
drwxr-xr-x  3 abhijeet  staff  96 Feb 20 11:01 fit

Abhijeets-MacBook-Air:fit abhijeet$ ls -lrt
total 0
drwxr-xr-x  3 abhijeet  staff  96 Feb 20 11:01 crushit

Abhijeets-MacBook-Air:fit abhijeet$ cd crushit/
Abhijeets-MacBook-Air:crushit abhijeet$ ls -lrt
total 0
drwxr-xr-x  3 abhijeet  staff  96 Feb 20 11:02 myfirstandroidapp

Abhijeets-MacBook-Air:myfirstandroidapp abhijeet$ ls -lrt
total 8
-rw-r--r--  1 abhijeet  staff  343 Feb 20 11:02 MainActivity.java

```
All files

```AppleScript

Abhijeets-MacBook-Air:MyFirstAndroidApp abhijeet$ find . -name "*"
.
./app
./app/app.iml
./app/proguard-rules.pro
./app/libs
./app/.gitignore
./app/build.gradle
./app/build
./app/build/generated
./app/build/generated/source
./app/build/generated/source/buildConfig
./app/build/generated/source/buildConfig/androidTest
./app/build/generated/source/buildConfig/androidTest/debug
./app/build/generated/source/buildConfig/androidTest/debug/fit
./app/build/generated/source/buildConfig/androidTest/debug/fit/crushit
./app/build/generated/source/buildConfig/androidTest/debug/fit/crushit/myfirstandroidapp
./app/build/generated/source/buildConfig/androidTest/debug/fit/crushit/myfirstandroidapp/test
./app/build/generated/source/buildConfig/androidTest/debug/fit/crushit/myfirstandroidapp/test/BuildConfig.java
./app/build/generated/source/buildConfig/debug
./app/build/generated/source/buildConfig/debug/fit
./app/build/generated/source/buildConfig/debug/fit/crushit
./app/build/generated/source/buildConfig/debug/fit/crushit/myfirstandroidapp
./app/build/generated/source/buildConfig/debug/fit/crushit/myfirstandroidapp/BuildConfig.java
./app/build/intermediates
./app/build/intermediates/bundle_manifest
./app/build/intermediates/bundle_manifest/debug
./app/build/intermediates/bundle_manifest/debug/processDebugManifest
./app/build/intermediates/bundle_manifest/debug/processDebugManifest/bundle-manifest
./app/build/intermediates/bundle_manifest/debug/processDebugManifest/bundle-manifest/output.json
./app/build/intermediates/bundle_manifest/debug/processDebugManifest/bundle-manifest/AndroidManifest.xml
./app/build/intermediates/lint_jar
./app/build/intermediates/lint_jar/global
./app/build/intermediates/lint_jar/global/prepareLintJar
./app/build/intermediates/merged_manifests
./app/build/intermediates/merged_manifests/debugAndroidTest
./app/build/intermediates/merged_manifests/debugAndroidTest/output.json
./app/build/intermediates/merged_manifests/debugAndroidTest/AndroidManifest.xml
./app/build/intermediates/merged_manifests/debug
./app/build/intermediates/merged_manifests/debug/output.json
./app/build/intermediates/merged_manifests/debug/AndroidManifest.xml
./app/build/intermediates/compatible_screen_manifest
./app/build/intermediates/compatible_screen_manifest/debug
./app/build/intermediates/compatible_screen_manifest/debug/createDebugCompatibleScreenManifests
./app/build/intermediates/compatible_screen_manifest/debug/createDebugCompatibleScreenManifests/out
./app/build/intermediates/compatible_screen_manifest/debug/createDebugCompatibleScreenManifests/out/output.json
./app/build/intermediates/instant_app_manifest
./app/build/intermediates/instant_app_manifest/debug
./app/build/intermediates/instant_app_manifest/debug/output.json
./app/build/intermediates/instant_app_manifest/debug/AndroidManifest.xml
./app/build/intermediates/metadata_feature_manifest
./app/build/intermediates/metadata_feature_manifest/debug
./app/build/intermediates/metadata_feature_manifest/debug/processDebugManifest
./app/build/intermediates/metadata_feature_manifest/debug/processDebugManifest/metadata-feature
./app/build/intermediates/metadata_feature_manifest/debug/processDebugManifest/metadata-feature/output.json
./app/build/intermediates/lint_publish_jar
./app/build/intermediates/lint_publish_jar/global
./app/build/intermediates/lint_publish_jar/global/prepareLintJarForPublish
./app/build/intermediates/apk_list
./app/build/intermediates/apk_list/debug
./app/build/intermediates/apk_list/debug/mainApkListPersistenceDebug
./app/build/intermediates/apk_list/debug/mainApkListPersistenceDebug/apk-list.gson
./app/build/intermediates/manifest_merge_blame_file
./app/build/intermediates/manifest_merge_blame_file/debugAndroidTest
./app/build/intermediates/manifest_merge_blame_file/debugAndroidTest/manifest-merger-blame-debug-androidTest-report.txt
./app/build/intermediates/manifest_merge_blame_file/debug
./app/build/intermediates/manifest_merge_blame_file/debug/manifest-merger-blame-debug-report.txt
./app/build/intermediates/tmp
./app/build/intermediates/tmp/manifest
./app/build/intermediates/tmp/manifest/androidTest
./app/build/intermediates/tmp/manifest/androidTest/debug
./app/build/intermediates/check_manifest_result
./app/build/intermediates/check_manifest_result/debug
./app/build/intermediates/check_manifest_result/debug/checkDebugManifest
./app/build/intermediates/check_manifest_result/debug/checkDebugManifest/out
./app/build/outputs
./app/build/outputs/logs
./app/build/outputs/logs/manifest-merger-debug-report.txt
./app/src
./app/src/androidTest
./app/src/androidTest/java
./app/src/androidTest/java/fit
./app/src/androidTest/java/fit/crushit
./app/src/androidTest/java/fit/crushit/myfirstandroidapp
./app/src/androidTest/java/fit/crushit/myfirstandroidapp/ExampleInstrumentedTest.java
./app/src/test
./app/src/test/java
./app/src/test/java/fit
./app/src/test/java/fit/crushit
./app/src/test/java/fit/crushit/myfirstandroidapp
./app/src/test/java/fit/crushit/myfirstandroidapp/ExampleUnitTest.java
./app/src/main
./app/src/main/res
./app/src/main/res/mipmap-mdpi
./app/src/main/res/mipmap-mdpi/ic_launcher.png
./app/src/main/res/mipmap-mdpi/ic_launcher_round.png
./app/src/main/res/drawable-v24
./app/src/main/res/drawable-v24/ic_launcher_foreground.xml
./app/src/main/res/mipmap-hdpi
./app/src/main/res/mipmap-hdpi/ic_launcher.png
./app/src/main/res/mipmap-hdpi/ic_launcher_round.png
./app/src/main/res/drawable
./app/src/main/res/drawable/ic_launcher_background.xml
./app/src/main/res/mipmap-xxxhdpi
./app/src/main/res/mipmap-xxxhdpi/ic_launcher.png
./app/src/main/res/mipmap-xxxhdpi/ic_launcher_round.png
./app/src/main/res/layout
./app/src/main/res/layout/activity_main.xml
./app/src/main/res/mipmap-xxhdpi
./app/src/main/res/mipmap-xxhdpi/ic_launcher.png
./app/src/main/res/mipmap-xxhdpi/ic_launcher_round.png
./app/src/main/res/values
./app/src/main/res/values/colors.xml
./app/src/main/res/values/styles.xml
./app/src/main/res/values/strings.xml
./app/src/main/res/mipmap-xhdpi
./app/src/main/res/mipmap-xhdpi/ic_launcher.png
./app/src/main/res/mipmap-xhdpi/ic_launcher_round.png
./app/src/main/res/mipmap-anydpi-v26
./app/src/main/res/mipmap-anydpi-v26/ic_launcher.xml
./app/src/main/res/mipmap-anydpi-v26/ic_launcher_round.xml
./app/src/main/AndroidManifest.xml
./app/src/main/java
./app/src/main/java/fit
./app/src/main/java/fit/crushit
./app/src/main/java/fit/crushit/myfirstandroidapp
./app/src/main/java/fit/crushit/myfirstandroidapp/MainActivity.java
./local.properties
./README.md
./gradle
./gradle/wrapper
./gradle/wrapper/gradle-wrapper.jar
./gradle/wrapper/gradle-wrapper.properties
./gradlew
./.gitignore
./build.gradle
./.gradle
./.gradle/vcs-1
./.gradle/vcs-1/gc.properties
./.gradle/5.4.1
./.gradle/5.4.1/executionHistory
./.gradle/5.4.1/executionHistory/executionHistory.lock
./.gradle/5.4.1/executionHistory/executionHistory.bin
./.gradle/5.4.1/vcsMetadata-1
./.gradle/5.4.1/gc.properties
./.gradle/5.4.1/fileChanges
./.gradle/5.4.1/fileChanges/last-build.bin
./.gradle/5.4.1/fileHashes
./.gradle/5.4.1/fileHashes/fileHashes.lock
./.gradle/5.4.1/fileHashes/fileHashes.bin
./.gradle/buildOutputCleanup
./.gradle/buildOutputCleanup/cache.properties
./.gradle/buildOutputCleanup/outputFiles.bin
./.gradle/buildOutputCleanup/buildOutputCleanup.lock
./gradle.properties
./gradlew.bat
./settings.gradle
./MyFirstAndroidApp.iml
./.idea
./.idea/runConfigurations.xml
./.idea/codeStyles
./.idea/codeStyles/Project.xml
./.idea/libraries
./.idea/libraries/Gradle__androidx_lifecycle_lifecycle_common_2_1_0_jar.xml
./.idea/libraries/Gradle__androidx_arch_core_core_runtime_2_0_0_aar.xml
./.idea/libraries/Gradle__androidx_activity_activity_1_0_0_aar.xml
./.idea/libraries/Gradle__org_hamcrest_hamcrest_integration_1_3_jar.xml
./.idea/libraries/Gradle__androidx_core_core_1_1_0_aar.xml
./.idea/libraries/Gradle__androidx_vectordrawable_vectordrawable_animated_1_1_0_aar.xml
./.idea/libraries/Gradle__androidx_lifecycle_lifecycle_livedata_2_0_0_aar.xml
./.idea/libraries/Gradle__com_squareup_javawriter_2_1_1_jar.xml
./.idea/libraries/Gradle__androidx_lifecycle_lifecycle_livedata_core_2_0_0_aar.xml
./.idea/libraries/Gradle__androidx_constraintlayout_constraintlayout_1_1_3_aar.xml
./.idea/libraries/Gradle__androidx_viewpager_viewpager_1_0_0_aar.xml
./.idea/libraries/Gradle__androidx_customview_customview_1_0_0_aar.xml
./.idea/libraries/Gradle__androidx_lifecycle_lifecycle_viewmodel_2_1_0_aar.xml
./.idea/libraries/Gradle__androidx_constraintlayout_constraintlayout_solver_1_1_3_jar.xml
./.idea/libraries/Gradle__androidx_annotation_annotation_1_1_0_jar.xml
./.idea/libraries/Gradle__net_sf_kxml_kxml2_2_3_0_jar.xml
./.idea/libraries/Gradle__javax_inject_javax_inject_1_jar.xml
./.idea/libraries/Gradle__androidx_appcompat_appcompat_1_1_0_aar.xml
./.idea/libraries/Gradle__androidx_appcompat_appcompat_resources_1_1_0_aar.xml
./.idea/libraries/Gradle__androidx_collection_collection_1_1_0_jar.xml
./.idea/libraries/Gradle__androidx_loader_loader_1_0_0_aar.xml
./.idea/libraries/Gradle__androidx_test_runner_1_2_0_aar.xml
./.idea/libraries/Gradle__junit_junit_4_12_jar.xml
./.idea/libraries/Gradle__org_hamcrest_hamcrest_core_1_3_jar.xml
./.idea/libraries/Gradle__org_hamcrest_hamcrest_library_1_3_jar.xml
./.idea/libraries/Gradle__androidx_test_espresso_espresso_core_3_2_0_aar.xml
./.idea/libraries/Gradle__androidx_lifecycle_lifecycle_runtime_2_1_0_aar.xml
./.idea/libraries/Gradle__androidx_arch_core_core_common_2_1_0_jar.xml
./.idea/libraries/Gradle__androidx_test_monitor_1_2_0_aar.xml
./.idea/libraries/Gradle__androidx_interpolator_interpolator_1_0_0_aar.xml
./.idea/libraries/Gradle__androidx_test_espresso_espresso_idling_resource_3_2_0_aar.xml
./.idea/libraries/Gradle__androidx_test_ext_junit_1_1_1_aar.xml
./.idea/libraries/Gradle__androidx_cursoradapter_cursoradapter_1_0_0_aar.xml
./.idea/libraries/Gradle__com_google_code_findbugs_jsr305_2_0_1_jar.xml
./.idea/libraries/Gradle__androidx_savedstate_savedstate_1_0_0_aar.xml
./.idea/libraries/Gradle__androidx_drawerlayout_drawerlayout_1_0_0_aar.xml
./.idea/libraries/Gradle__androidx_versionedparcelable_versionedparcelable_1_1_0_aar.xml
./.idea/libraries/Gradle__androidx_vectordrawable_vectordrawable_1_1_0_aar.xml
./.idea/libraries/Gradle__androidx_fragment_fragment_1_1_0_aar.xml
./.idea/libraries/Gradle__androidx_test_core_1_2_0_aar.xml
./.idea/gradle.xml
./.idea/vcs.xml
./.idea/workspace.xml
./.idea/modules.xml
./.idea/misc.xml
./.idea/caches
./.idea/caches/build_file_checksums.ser
./.idea/caches/gradle_models.ser

```

##AndroidManifest.xml

```AppleScript

cd /Users/abhijeet/AndroidStudioProjects/MyFirstAndroidApp/app/src/main/
cat AndroidManifest.xml

```

```XML

<?xml version="1.0" encoding="utf-8"?>
<manifest xmlns:android="http://schemas.android.com/apk/res/android"
    package="fit.crushit.myfirstandroidapp">

    <application
        android:allowBackup="true"
        android:icon="@mipmap/ic_launcher"
        android:label="@string/app_name"
        android:roundIcon="@mipmap/ic_launcher_round"
        android:supportsRtl="true"
        android:theme="@style/AppTheme">
        <activity android:name=".MainActivity">
            <intent-filter>
                <action android:name="android.intent.action.MAIN" />

                <category android:name="android.intent.category.LAUNCHER" />
            </intent-filter>
        </activity>
    </application>

</manifest>

```
## MainActivity.java

```AppleScript

cd /Users/abhijeet/AndroidStudioProjects/MyFirstAndroidApp/app/src/main/java/fit/crushit/myfirstandroidapp/
cat MainActivity.java

```

```java

package fit.crushit.myfirstandroidapp;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
    }
}

```

## activity_main.xml

```AppleScript

cd /Users/abhijeet/AndroidStudioProjects/MyFirstAndroidApp/app/src/main/res/layout/
cat activity_main.xml

```

```XML

<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Hello World!"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

</androidx.constraintlayout.widget.ConstraintLayout>

```
## Gradle

settings.gradle

```AppleScript

cd /Users/abhijeet/AndroidStudioProjects/MyFirstAndroidApp
Abhijeets-MacBook-Air:MyFirstAndroidApp abhijeet$ cat settings.gradle
include ':app'
rootProject.name='MyFirstAndroidApp'

```

build.gradle

```AppleScript

Abhijeets-MacBook-Air:app abhijeet$ cd /Users/abhijeet/AndroidStudioProjects/MyFirstAndroidApp/app
Abhijeets-MacBook-Air:app abhijeet$ cat build.gradle
apply plugin: 'com.android.application'

android {
    compileSdkVersion 29
    buildToolsVersion "29.0.3"
    defaultConfig {
        applicationId "fit.crushit.myfirstandroidapp"
        minSdkVersion 15
        targetSdkVersion 29
        versionCode 1
        versionName "1.0"
        testInstrumentationRunner "androidx.test.runner.AndroidJUnitRunner"
    }
    buildTypes {
        release {
            minifyEnabled false
            proguardFiles getDefaultProguardFile('proguard-android-optimize.txt'), 'proguard-rules.pro'
        }
    }
}

dependencies {
    implementation fileTree(dir: 'libs', include: ['*.jar'])
    implementation 'androidx.appcompat:appcompat:1.1.0'
    implementation 'androidx.constraintlayout:constraintlayout:1.1.3'
    testImplementation 'junit:junit:4.12'
    androidTestImplementation 'androidx.test.ext:junit:1.1.1'
    androidTestImplementation 'androidx.test.espresso:espresso-core:3.2.0'
}
Abhijeets-MacBook-Air:app abhijeet$

```
## app.iml

```AppleScript

cd /Users/abhijeet/AndroidStudioProjects/MyFirstAndroidApp/app
cat app.iml

```

```XML

<?xml version="1.0" encoding="UTF-8"?>
<module external.linked.project.id=":app" external.linked.project.path="$MODULE_DIR$" external.root.project.path="$MODULE_DIR$/.." external.system.id="GRADLE" type="JAVA_MODULE" version="4">
  <component name="FacetManager">
    <facet type="android-gradle" name="Android-Gradle">
      <configuration>
        <option name="GRADLE_PROJECT_PATH" value=":app" />
        <option name="LAST_SUCCESSFUL_SYNC_AGP_VERSION" value="3.5.3" />
        <option name="LAST_KNOWN_AGP_VERSION" value="3.5.3" />
      </configuration>
    </facet>
    <facet type="android" name="Android">
      <configuration>
        <option name="SELECTED_BUILD_VARIANT" value="debug" />
        <option name="ASSEMBLE_TASK_NAME" value="assembleDebug" />
        <option name="COMPILE_JAVA_TASK_NAME" value="compileDebugSources" />
        <afterSyncTasks>
          <task>generateDebugSources</task>
        </afterSyncTasks>
        <option name="ALLOW_USER_CONFIGURATION" value="false" />
        <option name="MANIFEST_FILE_RELATIVE_PATH" value="/src/main/AndroidManifest.xml" />
        <option name="RES_FOLDER_RELATIVE_PATH" value="/src/main/res" />
        <option name="RES_FOLDERS_RELATIVE_PATH" value="" />
        <option name="TEST_RES_FOLDERS_RELATIVE_PATH" value="" />
        <option name="ASSETS_FOLDER_RELATIVE_PATH" value="/src/main/assets" />
      </configuration>
    </facet>
  </component>
  <component name="NewModuleRootManager" LANGUAGE_LEVEL="JDK_1_7">
    <output url="file://$MODULE_DIR$/build/intermediates/javac/debug/classes" />
    <output-test url="file://$MODULE_DIR$/build/intermediates/javac/debugUnitTest/classes" />
    <exclude-output />
    <content url="file://$MODULE_DIR$">
      <sourceFolder url="file://$MODULE_DIR$/build/generated/ap_generated_sources/debug/out" isTestSource="false" generated="true" />
      <sourceFolder url="file://$MODULE_DIR$/build/generated/aidl_source_output_dir/debug/compileDebugAidl/out" isTestSource="false" generated="true" />
      <sourceFolder url="file://$MODULE_DIR$/build/generated/source/buildConfig/debug" isTestSource="false" generated="true" />
      <sourceFolder url="file://$MODULE_DIR$/build/generated/renderscript_source_output_dir/debug/compileDebugRenderscript/out" isTestSource="false" generated="true" />
      <sourceFolder url="file://$MODULE_DIR$/build/generated/res/rs/debug" type="java-resource" generated="true" />
      <sourceFolder url="file://$MODULE_DIR$/build/generated/res/resValues/debug" type="java-resource" generated="true" />
      <sourceFolder url="file://$MODULE_DIR$/build/generated/ap_generated_sources/debugAndroidTest/out" isTestSource="true" generated="true" />
      <sourceFolder url="file://$MODULE_DIR$/build/generated/aidl_source_output_dir/debugAndroidTest/compileDebugAndroidTestAidl/out" isTestSource="true" generated="true" />
      <sourceFolder url="file://$MODULE_DIR$/build/generated/source/buildConfig/androidTest/debug" isTestSource="true" generated="true" />
      <sourceFolder url="file://$MODULE_DIR$/build/generated/renderscript_source_output_dir/debugAndroidTest/compileDebugAndroidTestRenderscript/out" isTestSource="true" generated="true" />
      <sourceFolder url="file://$MODULE_DIR$/build/generated/res/rs/androidTest/debug" type="java-test-resource" generated="true" />
      <sourceFolder url="file://$MODULE_DIR$/build/generated/res/resValues/androidTest/debug" type="java-test-resource" generated="true" />
      <sourceFolder url="file://$MODULE_DIR$/build/generated/ap_generated_sources/debugUnitTest/out" isTestSource="true" generated="true" />
      <sourceFolder url="file://$MODULE_DIR$/src/debug/res" type="java-resource" />
      <sourceFolder url="file://$MODULE_DIR$/src/debug/resources" type="java-resource" />
      <sourceFolder url="file://$MODULE_DIR$/src/debug/assets" type="java-resource" />
      <sourceFolder url="file://$MODULE_DIR$/src/debug/aidl" isTestSource="false" />
      <sourceFolder url="file://$MODULE_DIR$/src/debug/java" isTestSource="false" />
      <sourceFolder url="file://$MODULE_DIR$/src/debug/rs" isTestSource="false" />
      <sourceFolder url="file://$MODULE_DIR$/src/debug/shaders" isTestSource="false" />
      <sourceFolder url="file://$MODULE_DIR$/src/androidTestDebug/res" type="java-test-resource" />
      <sourceFolder url="file://$MODULE_DIR$/src/androidTestDebug/resources" type="java-test-resource" />
      <sourceFolder url="file://$MODULE_DIR$/src/androidTestDebug/assets" type="java-test-resource" />
      <sourceFolder url="file://$MODULE_DIR$/src/androidTestDebug/aidl" isTestSource="true" />
      <sourceFolder url="file://$MODULE_DIR$/src/androidTestDebug/java" isTestSource="true" />
      <sourceFolder url="file://$MODULE_DIR$/src/androidTestDebug/rs" isTestSource="true" />
      <sourceFolder url="file://$MODULE_DIR$/src/androidTestDebug/shaders" isTestSource="true" />
      <sourceFolder url="file://$MODULE_DIR$/src/testDebug/res" type="java-test-resource" />
      <sourceFolder url="file://$MODULE_DIR$/src/testDebug/resources" type="java-test-resource" />
      <sourceFolder url="file://$MODULE_DIR$/src/testDebug/assets" type="java-test-resource" />
      <sourceFolder url="file://$MODULE_DIR$/src/testDebug/aidl" isTestSource="true" />
      <sourceFolder url="file://$MODULE_DIR$/src/testDebug/java" isTestSource="true" />
      <sourceFolder url="file://$MODULE_DIR$/src/testDebug/rs" isTestSource="true" />
      <sourceFolder url="file://$MODULE_DIR$/src/testDebug/shaders" isTestSource="true" />
      <sourceFolder url="file://$MODULE_DIR$/src/main/res" type="java-resource" />
      <sourceFolder url="file://$MODULE_DIR$/src/main/resources" type="java-resource" />
      <sourceFolder url="file://$MODULE_DIR$/src/main/assets" type="java-resource" />
      <sourceFolder url="file://$MODULE_DIR$/src/main/aidl" isTestSource="false" />
      <sourceFolder url="file://$MODULE_DIR$/src/main/java" isTestSource="false" />
      <sourceFolder url="file://$MODULE_DIR$/src/main/rs" isTestSource="false" />
      <sourceFolder url="file://$MODULE_DIR$/src/main/shaders" isTestSource="false" />
      <sourceFolder url="file://$MODULE_DIR$/src/androidTest/res" type="java-test-resource" />
      <sourceFolder url="file://$MODULE_DIR$/src/androidTest/resources" type="java-test-resource" />
      <sourceFolder url="file://$MODULE_DIR$/src/androidTest/assets" type="java-test-resource" />
      <sourceFolder url="file://$MODULE_DIR$/src/androidTest/aidl" isTestSource="true" />
      <sourceFolder url="file://$MODULE_DIR$/src/androidTest/java" isTestSource="true" />
      <sourceFolder url="file://$MODULE_DIR$/src/androidTest/rs" isTestSource="true" />
      <sourceFolder url="file://$MODULE_DIR$/src/androidTest/shaders" isTestSource="true" />
      <sourceFolder url="file://$MODULE_DIR$/src/test/res" type="java-test-resource" />
      <sourceFolder url="file://$MODULE_DIR$/src/test/resources" type="java-test-resource" />
      <sourceFolder url="file://$MODULE_DIR$/src/test/assets" type="java-test-resource" />
      <sourceFolder url="file://$MODULE_DIR$/src/test/aidl" isTestSource="true" />
      <sourceFolder url="file://$MODULE_DIR$/src/test/java" isTestSource="true" />
      <sourceFolder url="file://$MODULE_DIR$/src/test/rs" isTestSource="true" />
      <sourceFolder url="file://$MODULE_DIR$/src/test/shaders" isTestSource="true" />
      <excludeFolder url="file://$MODULE_DIR$/build" />
    </content>
    <orderEntry type="jdk" jdkName="Android API 29 Platform" jdkType="Android SDK" />
    <orderEntry type="sourceFolder" forTests="false" />
    <orderEntry type="library" scope="TEST" name="Gradle: junit:junit:4.12@jar" level="project" />
    <orderEntry type="library" scope="TEST" name="Gradle: org.hamcrest:hamcrest-integration:1.3@jar" level="project" />
    <orderEntry type="library" scope="TEST" name="Gradle: org.hamcrest:hamcrest-library:1.3@jar" level="project" />
    <orderEntry type="library" scope="TEST" name="Gradle: org.hamcrest:hamcrest-core:1.3@jar" level="project" />
    <orderEntry type="library" scope="TEST" name="Gradle: net.sf.kxml:kxml2:2.3.0@jar" level="project" />
    <orderEntry type="library" scope="TEST" name="Gradle: com.squareup:javawriter:2.1.1@jar" level="project" />
    <orderEntry type="library" scope="TEST" name="Gradle: javax.inject:javax.inject:1@jar" level="project" />
    <orderEntry type="library" scope="TEST" name="Gradle: com.google.code.findbugs:jsr305:2.0.1@jar" level="project" />
    <orderEntry type="library" scope="TEST" name="Gradle: androidx.test.ext:junit:1.1.1@aar" level="project" />
    <orderEntry type="library" scope="TEST" name="Gradle: androidx.test.espresso:espresso-core:3.2.0@aar" level="project" />
    <orderEntry type="library" scope="TEST" name="Gradle: androidx.test:runner:1.2.0@aar" level="project" />
    <orderEntry type="library" scope="TEST" name="Gradle: androidx.test:core:1.2.0@aar" level="project" />
    <orderEntry type="library" scope="TEST" name="Gradle: androidx.test:monitor:1.2.0@aar" level="project" />
    <orderEntry type="library" scope="TEST" name="Gradle: androidx.test.espresso:espresso-idling-resource:3.2.0@aar" level="project" />
    <orderEntry type="library" name="Gradle: androidx.collection:collection:1.1.0@jar" level="project" />
    <orderEntry type="library" name="Gradle: androidx.lifecycle:lifecycle-common:2.1.0@jar" level="project" />
    <orderEntry type="library" name="Gradle: androidx.arch.core:core-common:2.1.0@jar" level="project" />
    <orderEntry type="library" name="Gradle: androidx.annotation:annotation:1.1.0@jar" level="project" />
    <orderEntry type="library" name="Gradle: androidx.constraintlayout:constraintlayout-solver:1.1.3@jar" level="project" />
    <orderEntry type="library" name="Gradle: androidx.appcompat:appcompat:1.1.0@aar" level="project" />
    <orderEntry type="library" name="Gradle: androidx.fragment:fragment:1.1.0@aar" level="project" />
    <orderEntry type="library" name="Gradle: androidx.appcompat:appcompat-resources:1.1.0@aar" level="project" />
    <orderEntry type="library" name="Gradle: androidx.drawerlayout:drawerlayout:1.0.0@aar" level="project" />
    <orderEntry type="library" name="Gradle: androidx.viewpager:viewpager:1.0.0@aar" level="project" />
    <orderEntry type="library" name="Gradle: androidx.loader:loader:1.0.0@aar" level="project" />
    <orderEntry type="library" name="Gradle: androidx.activity:activity:1.0.0@aar" level="project" />
    <orderEntry type="library" name="Gradle: androidx.vectordrawable:vectordrawable-animated:1.1.0@aar" level="project" />
    <orderEntry type="library" name="Gradle: androidx.vectordrawable:vectordrawable:1.1.0@aar" level="project" />
    <orderEntry type="library" name="Gradle: androidx.customview:customview:1.0.0@aar" level="project" />
    <orderEntry type="library" name="Gradle: androidx.core:core:1.1.0@aar" level="project" />
    <orderEntry type="library" name="Gradle: androidx.cursoradapter:cursoradapter:1.0.0@aar" level="project" />
    <orderEntry type="library" name="Gradle: androidx.versionedparcelable:versionedparcelable:1.1.0@aar" level="project" />
    <orderEntry type="library" name="Gradle: androidx.lifecycle:lifecycle-viewmodel:2.1.0@aar" level="project" />
    <orderEntry type="library" name="Gradle: androidx.lifecycle:lifecycle-runtime:2.1.0@aar" level="project" />
    <orderEntry type="library" name="Gradle: androidx.savedstate:savedstate:1.0.0@aar" level="project" />
    <orderEntry type="library" name="Gradle: androidx.lifecycle:lifecycle-livedata:2.0.0@aar" level="project" />
    <orderEntry type="library" name="Gradle: androidx.lifecycle:lifecycle-livedata-core:2.0.0@aar" level="project" />
    <orderEntry type="library" name="Gradle: androidx.interpolator:interpolator:1.0.0@aar" level="project" />
    <orderEntry type="library" name="Gradle: androidx.arch.core:core-runtime:2.0.0@aar" level="project" />
    <orderEntry type="library" name="Gradle: androidx.constraintlayout:constraintlayout:1.1.3@aar" level="project" />
  </component>
</module>

```


