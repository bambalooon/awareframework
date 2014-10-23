##Setup
#To generate AAR library
1. Import Gradle project to IDE
2. Run gradle task: assemble
3. Project aar will be generated in {project_root}\awareframework\build\outputs\aar
#To generate APK
1. Import Gradle project to IDE
2. Edit "apply plugin: 'com.android.library'" in {project_root}\awareframework\build.gradle
 to "apply plugin: 'com.android.application'"
3. Run gradle task: assemble
4. Project apk will be generated in {project_root}\awareframework\build\outputs\apk
#You can get generated AwareFramework aar from my other project: aware_plugins