#To generate AAR library
######Import Gradle project to IDE
######Run gradle task: assemble
######Project aar will be generated in {project_root}\awareframework\build\outputs\aar
#To generate APK
######Import Gradle project to IDE
######Edit "apply plugin: 'com.android.library'" in {project_root}\awareframework\build.gradle to "apply plugin: 'com.android.application'"
######Run gradle task: assemble
######Project apk will be generated in {project_root}\awareframework\build\outputs\apk
####You can get generated AwareFramework aar from my other project: https://github.com/bambalooon/aware_plugins
