# flutter_problems
Document for Flutter related problems, guides,...

#Running Flutter Problems:
* Java Heap Size:
  Add this in android/gradle.properties:
    ```
    org.gradle.jvmargs=-Xmx1536M
    android.useAndroidX=true
    android.enableJetifier=true
    ```
