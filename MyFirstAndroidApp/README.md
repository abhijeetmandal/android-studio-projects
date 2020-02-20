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