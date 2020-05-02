# F0d1e
An android App utilising the Restful Spoonacular API 
This is a simple app that displays recipes from search input
A recipe instruction is also shown 
Added TTS- Text to speech so that you can listen to the recipe

This project utilizes the following opensource libraries
Credits goes to:
1. Android Opensource Project
2. Square Refrofit 
3. Square Picasso
4. Spoonacular API
5. JakeWhaton Butterknife
6. Firebase Authentication

# Project Structure/Tree

Folder PATH listing
Volume serial number is 1AF1-7BF3
C:.
│   .gitignore
│   build.gradle
│   F0d1e.iml
│   gradle.properties
│   gradlew
│   gradlew.bat
│   local.properties
│   README.md
│   settings.gradle
│   tree.txt
│   
├───.gradle
│   ├───5.4.1
│   │   │   gc.properties
│   │   │   
│   │   ├───executionHistory
│   │   │       executionHistory.bin
│   │   │       executionHistory.lock
│   │   │       
│   │   ├───fileChanges
│   │   │       last-build.bin
│   │   │       
│   │   ├───fileContent
│   │   │       fileContent.lock
│   │   │       
│   │   ├───fileHashes
│   │   │       fileHashes.bin
│   │   │       fileHashes.lock
│   │   │       resourceHashesCache.bin
│   │   │       
│   │   ├───javaCompile
│   │   │       classAnalysis.bin
│   │   │       javaCompile.lock
│   │   │       taskHistory.bin
│   │   │       
│   │   └───vcsMetadata-1
│   ├───buildOutputCleanup
│   │       buildOutputCleanup.lock
│   │       cache.properties
│   │       outputFiles.bin
│   │       
│   └───vcs-1
│           gc.properties
│           
├───.idea
│   │   assetWizardSettings.xml
│   │   gradle.xml
│   │   misc.xml
│   │   modules.xml
│   │   runConfigurations.xml
│   │   vcs.xml
│   │   workspace.xml
│   │   
│   ├───caches
│   │       build_file_checksums.ser
│   │       
│   ├───codeStyles
│   │       codeStyleConfig.xml
│   │       Project.xml
│   │       
│   ├───dictionaries
│   │       F0d1e.xml
│   │       
│   └───libraries
│           Gradle__androidx_activity_activity_1_0_0_aar.xml
│           Gradle__androidx_annotation_annotation_1_1_0_jar.xml
│           Gradle__androidx_appcompat_appcompat_1_1_0_aar.xml
│           Gradle__androidx_appcompat_appcompat_resources_1_1_0_aar.xml
│           Gradle__androidx_arch_core_core_common_2_1_0_jar.xml
│           Gradle__androidx_arch_core_core_runtime_2_0_0_aar.xml
│           Gradle__androidx_asynclayoutinflater_asynclayoutinflater_1_0_0_aar.xml
│           Gradle__androidx_cardview_cardview_1_0_0_aar.xml
│           Gradle__androidx_collection_collection_1_1_0_jar.xml
│           Gradle__androidx_constraintlayout_constraintlayout_1_1_3_aar.xml
│           Gradle__androidx_constraintlayout_constraintlayout_solver_1_1_3_jar.xml
│           Gradle__androidx_coordinatorlayout_coordinatorlayout_1_0_0_aar.xml
│           Gradle__androidx_core_core_1_1_0_aar.xml
│           Gradle__androidx_cursoradapter_cursoradapter_1_0_0_aar.xml
│           Gradle__androidx_customview_customview_1_0_0_aar.xml
│           Gradle__androidx_documentfile_documentfile_1_0_0_aar.xml
│           Gradle__androidx_drawerlayout_drawerlayout_1_0_0_aar.xml
│           Gradle__androidx_exifinterface_exifinterface_1_0_0_aar.xml
│           Gradle__androidx_fragment_fragment_1_1_0_aar.xml
│           Gradle__androidx_interpolator_interpolator_1_0_0_aar.xml
│           Gradle__androidx_legacy_legacy_support_core_ui_1_0_0_aar.xml
│           Gradle__androidx_legacy_legacy_support_core_utils_1_0_0_aar.xml
│           Gradle__androidx_lifecycle_lifecycle_common_2_1_0_jar.xml
│           Gradle__androidx_lifecycle_lifecycle_livedata_2_0_0_aar.xml
│           Gradle__androidx_lifecycle_lifecycle_livedata_core_2_0_0_aar.xml
│           Gradle__androidx_lifecycle_lifecycle_runtime_2_1_0_aar.xml
│           Gradle__androidx_lifecycle_lifecycle_viewmodel_2_1_0_aar.xml
│           Gradle__androidx_loader_loader_1_0_0_aar.xml
│           Gradle__androidx_localbroadcastmanager_localbroadcastmanager_1_0_0_aar.xml
│           Gradle__androidx_print_print_1_0_0_aar.xml
│           Gradle__androidx_recyclerview_recyclerview_1_0_0_aar.xml
│           Gradle__androidx_savedstate_savedstate_1_0_0_aar.xml
│           Gradle__androidx_slidingpanelayout_slidingpanelayout_1_0_0_aar.xml
│           Gradle__androidx_swiperefreshlayout_swiperefreshlayout_1_0_0_aar.xml
│           Gradle__androidx_test_core_1_2_0_aar.xml
│           Gradle__androidx_test_espresso_espresso_core_3_2_0_aar.xml
│           Gradle__androidx_test_espresso_espresso_idling_resource_3_2_0_aar.xml
│           Gradle__androidx_test_ext_junit_1_1_1_aar.xml
│           Gradle__androidx_test_monitor_1_2_0_aar.xml
│           Gradle__androidx_test_runner_1_2_0_aar.xml
│           Gradle__androidx_transition_transition_1_0_0_aar.xml
│           Gradle__androidx_vectordrawable_vectordrawable_1_1_0_aar.xml
│           Gradle__androidx_vectordrawable_vectordrawable_animated_1_1_0_aar.xml
│           Gradle__androidx_versionedparcelable_versionedparcelable_1_1_0_aar.xml
│           Gradle__androidx_viewpager_viewpager_1_0_0_aar.xml
│           Gradle__com_google_android_material_material_1_0_0_aar.xml
│           Gradle__com_google_code_findbugs_jsr305_2_0_1_jar.xml
│           Gradle__com_google_code_gson_gson_2_8_5_jar.xml
│           Gradle__com_jakewharton_butterknife_10_2_1_aar.xml
│           Gradle__com_jakewharton_butterknife_annotations_10_2_1_jar.xml
│           Gradle__com_jakewharton_butterknife_runtime_10_2_1_aar.xml
│           Gradle__com_squareup_javawriter_2_1_1_jar.xml
│           Gradle__com_squareup_okhttp3_okhttp_3_14_4_jar.xml
│           Gradle__com_squareup_okio_okio_1_17_2_jar.xml
│           Gradle__com_squareup_picasso_picasso_2_71828_aar.xml
│           Gradle__com_squareup_retrofit2_converter_gson_2_7_0_jar.xml
│           Gradle__com_squareup_retrofit2_retrofit_2_7_0_jar.xml
│           Gradle__javax_inject_javax_inject_1_jar.xml
│           Gradle__junit_junit_4_12_jar.xml
│           Gradle__net_sf_kxml_kxml2_2_3_0_jar.xml
│           Gradle__net_yslibrary_keyboardvisibilityevent_keyboardvisibilityevent_2_3_0_aar.xml
│           Gradle__org_hamcrest_hamcrest_core_1_3_jar.xml
│           Gradle__org_hamcrest_hamcrest_integration_1_3_jar.xml
│           Gradle__org_hamcrest_hamcrest_library_1_3_jar.xml
│           
├───app
│   │   .gitignore
│   │   app.iml
│   │   build.gradle
│   │   proguard-rules.pro
│   │   
│   ├───build
│   │   ├───generated
│   │   │   ├───ap_generated_sources
│   │   │   │   └───debug
│   │   │   │       └───out
│   │   │   ├───not_namespaced_r_class_sources
│   │   │   │   └───debug
│   │   │   │       └───r
│   │   │   │           ├───androidx
│   │   │   │           │   ├───activity
│   │   │   │           │   │       R.java
│   │   │   │           │   │       
│   │   │   │           │   ├───appcompat
│   │   │   │           │   │   │   R.java
│   │   │   │           │   │   │   
│   │   │   │           │   │   └───resources
│   │   │   │           │   │           R.java
│   │   │   │           │   │           
│   │   │   │           │   ├───arch
│   │   │   │           │   │   └───core
│   │   │   │           │   │           R.java
│   │   │   │           │   │           
│   │   │   │           │   ├───asynclayoutinflater
│   │   │   │           │   │       R.java
│   │   │   │           │   │       
│   │   │   │           │   ├───cardview
│   │   │   │           │   │       R.java
│   │   │   │           │   │       
│   │   │   │           │   ├───constraintlayout
│   │   │   │           │   │   └───widget
│   │   │   │           │   │           R.java
│   │   │   │           │   │           
│   │   │   │           │   ├───coordinatorlayout
│   │   │   │           │   │       R.java
│   │   │   │           │   │       
│   │   │   │           │   ├───core
│   │   │   │           │   │       R.java
│   │   │   │           │   │       
│   │   │   │           │   ├───cursoradapter
│   │   │   │           │   │       R.java
│   │   │   │           │   │       
│   │   │   │           │   ├───customview
│   │   │   │           │   │       R.java
│   │   │   │           │   │       
│   │   │   │           │   ├───documentfile
│   │   │   │           │   │       R.java
│   │   │   │           │   │       
│   │   │   │           │   ├───drawerlayout
│   │   │   │           │   │       R.java
│   │   │   │           │   │       
│   │   │   │           │   ├───exifinterface
│   │   │   │           │   │       R.java
│   │   │   │           │   │       
│   │   │   │           │   ├───fragment
│   │   │   │           │   │       R.java
│   │   │   │           │   │       
│   │   │   │           │   ├───interpolator
│   │   │   │           │   │       R.java
│   │   │   │           │   │       
│   │   │   │           │   ├───legacy
│   │   │   │           │   │   ├───coreui
│   │   │   │           │   │   │       R.java
│   │   │   │           │   │   │       
│   │   │   │           │   │   └───coreutils
│   │   │   │           │   │           R.java
│   │   │   │           │   │           
│   │   │   │           │   ├───lifecycle
│   │   │   │           │   │   │   R.java
│   │   │   │           │   │   │   
│   │   │   │           │   │   ├───livedata
│   │   │   │           │   │   │   │   R.java
│   │   │   │           │   │   │   │   
│   │   │   │           │   │   │   └───core
│   │   │   │           │   │   │           R.java
│   │   │   │           │   │   │           
│   │   │   │           │   │   └───viewmodel
│   │   │   │           │   │           R.java
│   │   │   │           │   │           
│   │   │   │           │   ├───loader
│   │   │   │           │   │       R.java
│   │   │   │           │   │       
│   │   │   │           │   ├───localbroadcastmanager
│   │   │   │           │   │       R.java
│   │   │   │           │   │       
│   │   │   │           │   ├───print
│   │   │   │           │   │       R.java
│   │   │   │           │   │       
│   │   │   │           │   ├───recyclerview
│   │   │   │           │   │       R.java
│   │   │   │           │   │       
│   │   │   │           │   ├───savedstate
│   │   │   │           │   │       R.java
│   │   │   │           │   │       
│   │   │   │           │   ├───slidingpanelayout
│   │   │   │           │   │       R.java
│   │   │   │           │   │       
│   │   │   │           │   ├───swiperefreshlayout
│   │   │   │           │   │       R.java
│   │   │   │           │   │       
│   │   │   │           │   ├───transition
│   │   │   │           │   │       R.java
│   │   │   │           │   │       
│   │   │   │           │   ├───vectordrawable
│   │   │   │           │   │   │   R.java
│   │   │   │           │   │   │   
│   │   │   │           │   │   └───animated
│   │   │   │           │   │           R.java
│   │   │   │           │   │           
│   │   │   │           │   ├───versionedparcelable
│   │   │   │           │   │       R.java
│   │   │   │           │   │       
│   │   │   │           │   └───viewpager
│   │   │   │           │           R.java
│   │   │   │           │           
│   │   │   │           ├───butterknife
│   │   │   │           │   │   R.java
│   │   │   │           │   │   
│   │   │   │           │   └───runtime
│   │   │   │           │           R.java
│   │   │   │           │           
│   │   │   │           ├───com
│   │   │   │           │   ├───brian
│   │   │   │           │   │   └───f0d1e
│   │   │   │           │   │           R.java
│   │   │   │           │   │           
│   │   │   │           │   ├───google
│   │   │   │           │   │   └───android
│   │   │   │           │   │       └───material
│   │   │   │           │   │               R.java
│   │   │   │           │   │               
│   │   │   │           │   └───squareup
│   │   │   │           │       └───picasso
│   │   │   │           │               R.java
│   │   │   │           │               
│   │   │   │           └───net
│   │   │   │               └───yslibrary
│   │   │   │                   └───android
│   │   │   │                       └───keyboardvisibilityevent
│   │   │   │                               R.java
│   │   │   │                               
│   │   │   ├───res
│   │   │   │   ├───pngs
│   │   │   │   │   └───debug
│   │   │   │   └───resValues
│   │   │   │       └───debug
│   │   │   └───source
│   │   │       └───buildConfig
│   │   │           └───debug
│   │   │               └───com
│   │   │                   └───brian
│   │   │                       └───f0d1e
│   │   │                               BuildConfig.java
│   │   │                               
│   │   ├───intermediates
│   │   │   ├───annotation_processor_list
│   │   │   │   └───debug
│   │   │   │           annotationProcessors.json
│   │   │   │           
│   │   │   ├───apk_list
│   │   │   │   └───debug
│   │   │   │       └───mainApkListPersistenceDebug
│   │   │   │               apk-list.gson
│   │   │   │               
│   │   │   ├───blame
│   │   │   │   └───res
│   │   │   │       └───debug
│   │   │   │           ├───multi-v2
│   │   │   │           │       debug.json
│   │   │   │           │       values-af.json
│   │   │   │           │       values-am.json
│   │   │   │           │       values-ar.json
│   │   │   │           │       values-as.json
│   │   │   │           │       values-az.json
│   │   │   │           │       values-b+sr+Latn.json
│   │   │   │           │       values-be.json
│   │   │   │           │       values-bg.json
│   │   │   │           │       values-bn.json
│   │   │   │           │       values-bs.json
│   │   │   │           │       values-ca.json
│   │   │   │           │       values-cs.json
│   │   │   │           │       values-da.json
│   │   │   │           │       values-de.json
│   │   │   │           │       values-el.json
│   │   │   │           │       values-en-rAU.json
│   │   │   │           │       values-en-rCA.json
│   │   │   │           │       values-en-rGB.json
│   │   │   │           │       values-en-rIN.json
│   │   │   │           │       values-en-rXC.json
│   │   │   │           │       values-es-rUS.json
│   │   │   │           │       values-es.json
│   │   │   │           │       values-et.json
│   │   │   │           │       values-eu.json
│   │   │   │           │       values-fa.json
│   │   │   │           │       values-fi.json
│   │   │   │           │       values-fr-rCA.json
│   │   │   │           │       values-fr.json
│   │   │   │           │       values-gl.json
│   │   │   │           │       values-gu.json
│   │   │   │           │       values-h720dp-v13.json
│   │   │   │           │       values-hdpi-v4.json
│   │   │   │           │       values-hi.json
│   │   │   │           │       values-hr.json
│   │   │   │           │       values-hu.json
│   │   │   │           │       values-hy.json
│   │   │   │           │       values-in.json
│   │   │   │           │       values-is.json
│   │   │   │           │       values-it.json
│   │   │   │           │       values-iw.json
│   │   │   │           │       values-ja.json
│   │   │   │           │       values-ka.json
│   │   │   │           │       values-kk.json
│   │   │   │           │       values-km.json
│   │   │   │           │       values-kn.json
│   │   │   │           │       values-ko.json
│   │   │   │           │       values-ky.json
│   │   │   │           │       values-land.json
│   │   │   │           │       values-large-v4.json
│   │   │   │           │       values-ldltr-v21.json
│   │   │   │           │       values-lo.json
│   │   │   │           │       values-lt.json
│   │   │   │           │       values-lv.json
│   │   │   │           │       values-mk.json
│   │   │   │           │       values-ml.json
│   │   │   │           │       values-mn.json
│   │   │   │           │       values-mr.json
│   │   │   │           │       values-ms.json
│   │   │   │           │       values-my.json
│   │   │   │           │       values-nb.json
│   │   │   │           │       values-ne.json
│   │   │   │           │       values-night-v8.json
│   │   │   │           │       values-nl.json
│   │   │   │           │       values-or.json
│   │   │   │           │       values-pa.json
│   │   │   │           │       values-pl.json
│   │   │   │           │       values-port.json
│   │   │   │           │       values-pt-rBR.json
│   │   │   │           │       values-pt-rPT.json
│   │   │   │           │       values-pt.json
│   │   │   │           │       values-ro.json
│   │   │   │           │       values-ru.json
│   │   │   │           │       values-si.json
│   │   │   │           │       values-sk.json
│   │   │   │           │       values-sl.json
│   │   │   │           │       values-sq.json
│   │   │   │           │       values-sr.json
│   │   │   │           │       values-sv.json
│   │   │   │           │       values-sw.json
│   │   │   │           │       values-sw600dp-v13.json
│   │   │   │           │       values-ta.json
│   │   │   │           │       values-te.json
│   │   │   │           │       values-th.json
│   │   │   │           │       values-tl.json
│   │   │   │           │       values-tr.json
│   │   │   │           │       values-uk.json
│   │   │   │           │       values-ur.json
│   │   │   │           │       values-uz.json
│   │   │   │           │       values-v16.json
│   │   │   │           │       values-v17.json
│   │   │   │           │       values-v18.json
│   │   │   │           │       values-v21.json
│   │   │   │           │       values-v22.json
│   │   │   │           │       values-v23.json
│   │   │   │           │       values-v24.json
│   │   │   │           │       values-v25.json
│   │   │   │           │       values-v26.json
│   │   │   │           │       values-v28.json
│   │   │   │           │       values-vi.json
│   │   │   │           │       values-watch-v20.json
│   │   │   │           │       values-watch-v21.json
│   │   │   │           │       values-xlarge-v4.json
│   │   │   │           │       values-zh-rCN.json
│   │   │   │           │       values-zh-rHK.json
│   │   │   │           │       values-zh-rTW.json
│   │   │   │           │       values-zu.json
│   │   │   │           │       values.json
│   │   │   │           │       
│   │   │   │           └───single
│   │   │   │                   debug.json
│   │   │   │                   
│   │   │   ├───bundle_manifest
│   │   │   │   └───debug
│   │   │   │       └───processDebugManifest
│   │   │   │           └───bundle-manifest
│   │   │   │                   AndroidManifest.xml
│   │   │   │                   output.json
│   │   │   │                   
│   │   │   ├───check_manifest_result
│   │   │   │   └───debug
│   │   │   │       └───checkDebugManifest
│   │   │   │           └───out
│   │   │   ├───compatible_screen_manifest
│   │   │   │   └───debug
│   │   │   │       └───createDebugCompatibleScreenManifests
│   │   │   │           └───out
│   │   │   │                   output.json
│   │   │   │                   
│   │   │   ├───dex
│   │   │   │   └───debug
│   │   │   │       ├───mergeExtDexDebug
│   │   │   │       │   └───out
│   │   │   │       │           classes.dex
│   │   │   │       │           
│   │   │   │       ├───mergeLibDexDebug
│   │   │   │       │   └───out
│   │   │   │       └───mergeProjectDexDebug
│   │   │   │           └───out
│   │   │   │                   classes.dex
│   │   │   │                   
│   │   │   ├───duplicate_classes_check
│   │   │   │   └───debug
│   │   │   │       └───out
│   │   │   ├───external_file_lib_dex_archives
│   │   │   │   └───debug
│   │   │   │       └───out
│   │   │   ├───incremental
│   │   │   │   ├───debug-mergeJavaRes
│   │   │   │   │   │   merge-state
│   │   │   │   │   │   
│   │   │   │   │   └───zip-cache
│   │   │   │   │           17MlsvZBOLKbV8Ld9ceQPY8NyhA=
│   │   │   │   │           3sUHbZ_e0TQRIJY560YAfLETuq8=
│   │   │   │   │           3Y1Iw9srpYOmgewn_7E3Drtg5k8=
│   │   │   │   │           5RJfViBG9PhZ3+Q_88D2Q+3OFmI=
│   │   │   │   │           6+3jPMPsUMNqVJbC9185UT5E_Yg=
│   │   │   │   │           6f+dLmHXwp44F9AbxaMFiU7bte4=
│   │   │   │   │           80gZYORbI_KMYIiHS8ln7Bal8T0=
│   │   │   │   │           cyNyGARoeHzn1pCpvwwOdSnlTj8=
│   │   │   │   │           D2DQo_jCWatZATIAdu+_tKP8cmU=
│   │   │   │   │           e0GDIdtDtWl4EhmnDdGxTA+vz+M=
│   │   │   │   │           e0_x+dfff3H3bRJfcXJrfhckmHA=
│   │   │   │   │           e7_uPuDGVg+dXu0AEJBTeuD+JNw=
│   │   │   │   │           fahyqEJa3QlPaU9+iOQlEWzjJOo=
│   │   │   │   │           FJWVvc+dSr7cmha4VDDm+xOIt9o=
│   │   │   │   │           FvFkni5odBa+8j8nxrW8dXcjo1E=
│   │   │   │   │           G23asU8qXkEcWJiTjcAcD3Qrwa0=
│   │   │   │   │           gjMTVaaOOdOJ03l8K37fmYF185M=
│   │   │   │   │           GoL16DIGchwxblUJfYMEi+d9gIs=
│   │   │   │   │           gYqJa03YVdKpZrb4N2EatcA7G98=
│   │   │   │   │           hzEoHIULuX8VKis+g1ZdTS4Bu2g=
│   │   │   │   │           I3ATTHyGYa8Oyk06amGqrYIeGVY=
│   │   │   │   │           ie_BQLGACeLED9JoQG61LTFx9aY=
│   │   │   │   │           iN2oaAwablROJfmBQ4bFNb8v75E=
│   │   │   │   │           ioZurFkqM0+32ibM98LyVzFWY3I=
│   │   │   │   │           j0cUeAwYYpcqEMLHoae9uOnoLNg=
│   │   │   │   │           JxSboQGCnNizhnhN_e8BRV0TfvE=
│   │   │   │   │           JZblWS56VOcs6FbwMKyTQ3xekfY=
│   │   │   │   │           kIO9ZU9GnCivi2NdJXG3RRUWYmY=
│   │   │   │   │           kOoFbQS+vaXVn55hh+ohOJa_UeI=
│   │   │   │   │           lPntyiPyWJIzMt7D3DQ1EO5pLe0=
│   │   │   │   │           lSy542yshv_I1c_fC0ouMB1_RqI=
│   │   │   │   │           mtZsX6zjm32S7w617UYGH+_x1dE=
│   │   │   │   │           oddFEFdM9gzjovR0d2bWgplcUz4=
│   │   │   │   │           qj8n60hcdRj_5VScP7MJI5Ow4Hs=
│   │   │   │   │           QRu8sGLVW2W7iX68HORMxNUI_JY=
│   │   │   │   │           Rjr1aoY+OyORIc794cmbK7cMHXM=
│   │   │   │   │           svVH4PGQheFvZWbGKF+kuUv7Udo=
│   │   │   │   │           UAUehsJcXV3pBrbrfJUWjlfcxi8=
│   │   │   │   │           UWuJ1o58lEeotVHkIjqw3rwqVOk=
│   │   │   │   │           VxCTkgb6wRG4RcOLYADZ8OmoUAo=
│   │   │   │   │           vZF6nrx5_q3XochajSf51URrSKU=
│   │   │   │   │           w7mfH5JHtbA5GIlhgoO_laLExYo=
│   │   │   │   │           WYS0XuYIEIzPOL6rOMo9QNoA7kk=
│   │   │   │   │           X5Nbk2RpkOZI07N9vQIQFBrJZIY=
│   │   │   │   │           YbdHhUa62s9__33TFV45Y09EYH8=
│   │   │   │   │           YiERJQf6_f1GyEFIiX7QkrStbDw=
│   │   │   │   │           yvUXW5T7gms3x2M4SmO0iKrHYGc=
│   │   │   │   │           ZAMfPQbJ9t6eSNvQQq2U8jyTsro=
│   │   │   │   │           zg3bQ5KWMww3KQjDsJnH4w9d3Ts=
│   │   │   │   │           ZhTK6nN533YI7hXREOTXe59fWp0=
│   │   │   │   │           
│   │   │   │   ├───debug-mergeNativeLibs
│   │   │   │   │   │   merge-state
│   │   │   │   │   │   
│   │   │   │   │   └───zip-cache
│   │   │   │   │           17MlsvZBOLKbV8Ld9ceQPY8NyhA=
│   │   │   │   │           3sUHbZ_e0TQRIJY560YAfLETuq8=
│   │   │   │   │           3Y1Iw9srpYOmgewn_7E3Drtg5k8=
│   │   │   │   │           5RJfViBG9PhZ3+Q_88D2Q+3OFmI=
│   │   │   │   │           6+3jPMPsUMNqVJbC9185UT5E_Yg=
│   │   │   │   │           6f+dLmHXwp44F9AbxaMFiU7bte4=
│   │   │   │   │           80gZYORbI_KMYIiHS8ln7Bal8T0=
│   │   │   │   │           cyNyGARoeHzn1pCpvwwOdSnlTj8=
│   │   │   │   │           D2DQo_jCWatZATIAdu+_tKP8cmU=
│   │   │   │   │           e0GDIdtDtWl4EhmnDdGxTA+vz+M=
│   │   │   │   │           e0_x+dfff3H3bRJfcXJrfhckmHA=
│   │   │   │   │           e7_uPuDGVg+dXu0AEJBTeuD+JNw=
│   │   │   │   │           fahyqEJa3QlPaU9+iOQlEWzjJOo=
│   │   │   │   │           FJWVvc+dSr7cmha4VDDm+xOIt9o=
│   │   │   │   │           FvFkni5odBa+8j8nxrW8dXcjo1E=
│   │   │   │   │           G23asU8qXkEcWJiTjcAcD3Qrwa0=
│   │   │   │   │           gjMTVaaOOdOJ03l8K37fmYF185M=
│   │   │   │   │           GoL16DIGchwxblUJfYMEi+d9gIs=
│   │   │   │   │           gYqJa03YVdKpZrb4N2EatcA7G98=
│   │   │   │   │           hzEoHIULuX8VKis+g1ZdTS4Bu2g=
│   │   │   │   │           I3ATTHyGYa8Oyk06amGqrYIeGVY=
│   │   │   │   │           ie_BQLGACeLED9JoQG61LTFx9aY=
│   │   │   │   │           iN2oaAwablROJfmBQ4bFNb8v75E=
│   │   │   │   │           ioZurFkqM0+32ibM98LyVzFWY3I=
│   │   │   │   │           j0cUeAwYYpcqEMLHoae9uOnoLNg=
│   │   │   │   │           JxSboQGCnNizhnhN_e8BRV0TfvE=
│   │   │   │   │           JZblWS56VOcs6FbwMKyTQ3xekfY=
│   │   │   │   │           kIO9ZU9GnCivi2NdJXG3RRUWYmY=
│   │   │   │   │           kOoFbQS+vaXVn55hh+ohOJa_UeI=
│   │   │   │   │           lPntyiPyWJIzMt7D3DQ1EO5pLe0=
│   │   │   │   │           lSy542yshv_I1c_fC0ouMB1_RqI=
│   │   │   │   │           mtZsX6zjm32S7w617UYGH+_x1dE=
│   │   │   │   │           oddFEFdM9gzjovR0d2bWgplcUz4=
│   │   │   │   │           qj8n60hcdRj_5VScP7MJI5Ow4Hs=
│   │   │   │   │           QRu8sGLVW2W7iX68HORMxNUI_JY=
│   │   │   │   │           Rjr1aoY+OyORIc794cmbK7cMHXM=
│   │   │   │   │           svVH4PGQheFvZWbGKF+kuUv7Udo=
│   │   │   │   │           UAUehsJcXV3pBrbrfJUWjlfcxi8=
│   │   │   │   │           UWuJ1o58lEeotVHkIjqw3rwqVOk=
│   │   │   │   │           VxCTkgb6wRG4RcOLYADZ8OmoUAo=
│   │   │   │   │           vZF6nrx5_q3XochajSf51URrSKU=
│   │   │   │   │           w7mfH5JHtbA5GIlhgoO_laLExYo=
│   │   │   │   │           WYS0XuYIEIzPOL6rOMo9QNoA7kk=
│   │   │   │   │           X5Nbk2RpkOZI07N9vQIQFBrJZIY=
│   │   │   │   │           YbdHhUa62s9__33TFV45Y09EYH8=
│   │   │   │   │           YiERJQf6_f1GyEFIiX7QkrStbDw=
│   │   │   │   │           yvUXW5T7gms3x2M4SmO0iKrHYGc=
│   │   │   │   │           ZAMfPQbJ9t6eSNvQQq2U8jyTsro=
│   │   │   │   │           zg3bQ5KWMww3KQjDsJnH4w9d3Ts=
│   │   │   │   │           ZhTK6nN533YI7hXREOTXe59fWp0=
│   │   │   │   │           
│   │   │   │   ├───mergeDebugAssets
│   │   │   │   │       merger.xml
│   │   │   │   │       
│   │   │   │   ├───mergeDebugJniLibFolders
│   │   │   │   │       merger.xml
│   │   │   │   │       
│   │   │   │   ├───mergeDebugResources
│   │   │   │   │   │   compile-file-map.properties
│   │   │   │   │   │   merger.xml
│   │   │   │   │   │   
│   │   │   │   │   ├───merged.dir
│   │   │   │   │   └───stripped.dir
│   │   │   │   ├───mergeDebugShaders
│   │   │   │   │       merger.xml
│   │   │   │   │       
│   │   │   │   ├───packageDebug
│   │   │   │   │   └───tmp
│   │   │   │   │       └───debug
│   │   │   │   │           │   dex-renamer-state.txt
│   │   │   │   │           │   
│   │   │   │   │           └───zip-cache
│   │   │   │   │                   q5D2i4VOKk_4EvcDxQYLULhF1bc=
│   │   │   │   │                   rXMmxAt_SoC5E9NvR+uU8G4jJuU=
│   │   │   │   │                   
│   │   │   │   └───processDebugResources
│   │   │   ├───instant_app_manifest
│   │   │   │   └───debug
│   │   │   │           AndroidManifest.xml
│   │   │   │           output.json
│   │   │   │           
│   │   │   ├───javac
│   │   │   │   └───debug
│   │   │   │       └───classes
│   │   │   │           ├───androidx
│   │   │   │           │   ├───activity
│   │   │   │           │   │       R$attr.class
│   │   │   │           │   │       R$color.class
│   │   │   │           │   │       R$dimen.class
│   │   │   │           │   │       R$drawable.class
│   │   │   │           │   │       R$id.class
│   │   │   │           │   │       R$integer.class
│   │   │   │           │   │       R$layout.class
│   │   │   │           │   │       R$string.class
│   │   │   │           │   │       R$style.class
│   │   │   │           │   │       R$styleable.class
│   │   │   │           │   │       R.class
│   │   │   │           │   │       
│   │   │   │           │   ├───appcompat
│   │   │   │           │   │   │   R$anim.class
│   │   │   │           │   │   │   R$attr.class
│   │   │   │           │   │   │   R$bool.class
│   │   │   │           │   │   │   R$color.class
│   │   │   │           │   │   │   R$dimen.class
│   │   │   │           │   │   │   R$drawable.class
│   │   │   │           │   │   │   R$id.class
│   │   │   │           │   │   │   R$integer.class
│   │   │   │           │   │   │   R$interpolator.class
│   │   │   │           │   │   │   R$layout.class
│   │   │   │           │   │   │   R$string.class
│   │   │   │           │   │   │   R$style.class
│   │   │   │           │   │   │   R$styleable.class
│   │   │   │           │   │   │   R.class
│   │   │   │           │   │   │   
│   │   │   │           │   │   └───resources
│   │   │   │           │   │           R$attr.class
│   │   │   │           │   │           R$color.class
│   │   │   │           │   │           R$dimen.class
│   │   │   │           │   │           R$drawable.class
│   │   │   │           │   │           R$id.class
│   │   │   │           │   │           R$integer.class
│   │   │   │           │   │           R$layout.class
│   │   │   │           │   │           R$string.class
│   │   │   │           │   │           R$style.class
│   │   │   │           │   │           R$styleable.class
│   │   │   │           │   │           R.class
│   │   │   │           │   │           
│   │   │   │           │   ├───arch
│   │   │   │           │   │   └───core
│   │   │   │           │   │           R.class
│   │   │   │           │   │           
│   │   │   │           │   ├───asynclayoutinflater
│   │   │   │           │   │       R$attr.class
│   │   │   │           │   │       R$color.class
│   │   │   │           │   │       R$dimen.class
│   │   │   │           │   │       R$drawable.class
│   │   │   │           │   │       R$id.class
│   │   │   │           │   │       R$integer.class
│   │   │   │           │   │       R$layout.class
│   │   │   │           │   │       R$string.class
│   │   │   │           │   │       R$style.class
│   │   │   │           │   │       R$styleable.class
│   │   │   │           │   │       R.class
│   │   │   │           │   │       
│   │   │   │           │   ├───cardview
│   │   │   │           │   │       R$attr.class
│   │   │   │           │   │       R$color.class
│   │   │   │           │   │       R$dimen.class
│   │   │   │           │   │       R$style.class
│   │   │   │           │   │       R$styleable.class
│   │   │   │           │   │       R.class
│   │   │   │           │   │       
│   │   │   │           │   ├───constraintlayout
│   │   │   │           │   │   └───widget
│   │   │   │           │   │           R$attr.class
│   │   │   │           │   │           R$id.class
│   │   │   │           │   │           R$styleable.class
│   │   │   │           │   │           R.class
│   │   │   │           │   │           
│   │   │   │           │   ├───coordinatorlayout
│   │   │   │           │   │       R$attr.class
│   │   │   │           │   │       R$color.class
│   │   │   │           │   │       R$dimen.class
│   │   │   │           │   │       R$drawable.class
│   │   │   │           │   │       R$id.class
│   │   │   │           │   │       R$integer.class
│   │   │   │           │   │       R$layout.class
│   │   │   │           │   │       R$string.class
│   │   │   │           │   │       R$style.class
│   │   │   │           │   │       R$styleable.class
│   │   │   │           │   │       R.class
│   │   │   │           │   │       
│   │   │   │           │   ├───core
│   │   │   │           │   │       R$attr.class
│   │   │   │           │   │       R$color.class
│   │   │   │           │   │       R$dimen.class
│   │   │   │           │   │       R$drawable.class
│   │   │   │           │   │       R$id.class
│   │   │   │           │   │       R$integer.class
│   │   │   │           │   │       R$layout.class
│   │   │   │           │   │       R$string.class
│   │   │   │           │   │       R$style.class
│   │   │   │           │   │       R$styleable.class
│   │   │   │           │   │       R.class
│   │   │   │           │   │       
│   │   │   │           │   ├───cursoradapter
│   │   │   │           │   │       R.class
│   │   │   │           │   │       
│   │   │   │           │   ├───customview
│   │   │   │           │   │       R$attr.class
│   │   │   │           │   │       R$color.class
│   │   │   │           │   │       R$dimen.class
│   │   │   │           │   │       R$drawable.class
│   │   │   │           │   │       R$id.class
│   │   │   │           │   │       R$integer.class
│   │   │   │           │   │       R$layout.class
│   │   │   │           │   │       R$string.class
│   │   │   │           │   │       R$style.class
│   │   │   │           │   │       R$styleable.class
│   │   │   │           │   │       R.class
│   │   │   │           │   │       
│   │   │   │           │   ├───documentfile
│   │   │   │           │   │       R.class
│   │   │   │           │   │       
│   │   │   │           │   ├───drawerlayout
│   │   │   │           │   │       R$attr.class
│   │   │   │           │   │       R$color.class
│   │   │   │           │   │       R$dimen.class
│   │   │   │           │   │       R$drawable.class
│   │   │   │           │   │       R$id.class
│   │   │   │           │   │       R$integer.class
│   │   │   │           │   │       R$layout.class
│   │   │   │           │   │       R$string.class
│   │   │   │           │   │       R$style.class
│   │   │   │           │   │       R$styleable.class
│   │   │   │           │   │       R.class
│   │   │   │           │   │       
│   │   │   │           │   ├───exifinterface
│   │   │   │           │   │       R.class
│   │   │   │           │   │       
│   │   │   │           │   ├───fragment
│   │   │   │           │   │       R$attr.class
│   │   │   │           │   │       R$color.class
│   │   │   │           │   │       R$dimen.class
│   │   │   │           │   │       R$drawable.class
│   │   │   │           │   │       R$id.class
│   │   │   │           │   │       R$integer.class
│   │   │   │           │   │       R$layout.class
│   │   │   │           │   │       R$string.class
│   │   │   │           │   │       R$style.class
│   │   │   │           │   │       R$styleable.class
│   │   │   │           │   │       R.class
│   │   │   │           │   │       
│   │   │   │           │   ├───interpolator
│   │   │   │           │   │       R.class
│   │   │   │           │   │       
│   │   │   │           │   ├───legacy
│   │   │   │           │   │   ├───coreui
│   │   │   │           │   │   │       R$attr.class
│   │   │   │           │   │   │       R$color.class
│   │   │   │           │   │   │       R$dimen.class
│   │   │   │           │   │   │       R$drawable.class
│   │   │   │           │   │   │       R$id.class
│   │   │   │           │   │   │       R$integer.class
│   │   │   │           │   │   │       R$layout.class
│   │   │   │           │   │   │       R$string.class
│   │   │   │           │   │   │       R$style.class
│   │   │   │           │   │   │       R$styleable.class
│   │   │   │           │   │   │       R.class
│   │   │   │           │   │   │       
│   │   │   │           │   │   └───coreutils
│   │   │   │           │   │           R$attr.class
│   │   │   │           │   │           R$color.class
│   │   │   │           │   │           R$dimen.class
│   │   │   │           │   │           R$drawable.class
│   │   │   │           │   │           R$id.class
│   │   │   │           │   │           R$integer.class
│   │   │   │           │   │           R$layout.class
│   │   │   │           │   │           R$string.class
│   │   │   │           │   │           R$style.class
│   │   │   │           │   │           R$styleable.class
│   │   │   │           │   │           R.class
│   │   │   │           │   │           
│   │   │   │           │   ├───lifecycle
│   │   │   │           │   │   │   R.class
│   │   │   │           │   │   │   
│   │   │   │           │   │   ├───livedata
│   │   │   │           │   │   │   │   R.class
│   │   │   │           │   │   │   │   
│   │   │   │           │   │   │   └───core
│   │   │   │           │   │   │           R.class
│   │   │   │           │   │   │           
│   │   │   │           │   │   └───viewmodel
│   │   │   │           │   │           R.class
│   │   │   │           │   │           
│   │   │   │           │   ├───loader
│   │   │   │           │   │       R$attr.class
│   │   │   │           │   │       R$color.class
│   │   │   │           │   │       R$dimen.class
│   │   │   │           │   │       R$drawable.class
│   │   │   │           │   │       R$id.class
│   │   │   │           │   │       R$integer.class
│   │   │   │           │   │       R$layout.class
│   │   │   │           │   │       R$string.class
│   │   │   │           │   │       R$style.class
│   │   │   │           │   │       R$styleable.class
│   │   │   │           │   │       R.class
│   │   │   │           │   │       
│   │   │   │           │   ├───localbroadcastmanager
│   │   │   │           │   │       R.class
│   │   │   │           │   │       
│   │   │   │           │   ├───print
│   │   │   │           │   │       R.class
│   │   │   │           │   │       
│   │   │   │           │   ├───recyclerview
│   │   │   │           │   │       R$attr.class
│   │   │   │           │   │       R$color.class
│   │   │   │           │   │       R$dimen.class
│   │   │   │           │   │       R$drawable.class
│   │   │   │           │   │       R$id.class
│   │   │   │           │   │       R$integer.class
│   │   │   │           │   │       R$layout.class
│   │   │   │           │   │       R$string.class
│   │   │   │           │   │       R$style.class
│   │   │   │           │   │       R$styleable.class
│   │   │   │           │   │       R.class
│   │   │   │           │   │       
│   │   │   │           │   ├───savedstate
│   │   │   │           │   │       R.class
│   │   │   │           │   │       
│   │   │   │           │   ├───slidingpanelayout
│   │   │   │           │   │       R$attr.class
│   │   │   │           │   │       R$color.class
│   │   │   │           │   │       R$dimen.class
│   │   │   │           │   │       R$drawable.class
│   │   │   │           │   │       R$id.class
│   │   │   │           │   │       R$integer.class
│   │   │   │           │   │       R$layout.class
│   │   │   │           │   │       R$string.class
│   │   │   │           │   │       R$style.class
│   │   │   │           │   │       R$styleable.class
│   │   │   │           │   │       R.class
│   │   │   │           │   │       
│   │   │   │           │   ├───swiperefreshlayout
│   │   │   │           │   │       R$attr.class
│   │   │   │           │   │       R$color.class
│   │   │   │           │   │       R$dimen.class
│   │   │   │           │   │       R$drawable.class
│   │   │   │           │   │       R$id.class
│   │   │   │           │   │       R$integer.class
│   │   │   │           │   │       R$layout.class
│   │   │   │           │   │       R$string.class
│   │   │   │           │   │       R$style.class
│   │   │   │           │   │       R$styleable.class
│   │   │   │           │   │       R.class
│   │   │   │           │   │       
│   │   │   │           │   ├───transition
│   │   │   │           │   │       R$attr.class
│   │   │   │           │   │       R$color.class
│   │   │   │           │   │       R$dimen.class
│   │   │   │           │   │       R$drawable.class
│   │   │   │           │   │       R$id.class
│   │   │   │           │   │       R$integer.class
│   │   │   │           │   │       R$layout.class
│   │   │   │           │   │       R$string.class
│   │   │   │           │   │       R$style.class
│   │   │   │           │   │       R$styleable.class
│   │   │   │           │   │       R.class
│   │   │   │           │   │       
│   │   │   │           │   ├───vectordrawable
│   │   │   │           │   │   │   R$attr.class
│   │   │   │           │   │   │   R$color.class
│   │   │   │           │   │   │   R$dimen.class
│   │   │   │           │   │   │   R$drawable.class
│   │   │   │           │   │   │   R$id.class
│   │   │   │           │   │   │   R$integer.class
│   │   │   │           │   │   │   R$layout.class
│   │   │   │           │   │   │   R$string.class
│   │   │   │           │   │   │   R$style.class
│   │   │   │           │   │   │   R$styleable.class
│   │   │   │           │   │   │   R.class
│   │   │   │           │   │   │   
│   │   │   │           │   │   └───animated
│   │   │   │           │   │           R$attr.class
│   │   │   │           │   │           R$color.class
│   │   │   │           │   │           R$dimen.class
│   │   │   │           │   │           R$drawable.class
│   │   │   │           │   │           R$id.class
│   │   │   │           │   │           R$integer.class
│   │   │   │           │   │           R$layout.class
│   │   │   │           │   │           R$string.class
│   │   │   │           │   │           R$style.class
│   │   │   │           │   │           R$styleable.class
│   │   │   │           │   │           R.class
│   │   │   │           │   │           
│   │   │   │           │   ├───versionedparcelable
│   │   │   │           │   │       R.class
│   │   │   │           │   │       
│   │   │   │           │   └───viewpager
│   │   │   │           │           R$attr.class
│   │   │   │           │           R$color.class
│   │   │   │           │           R$dimen.class
│   │   │   │           │           R$drawable.class
│   │   │   │           │           R$id.class
│   │   │   │           │           R$integer.class
│   │   │   │           │           R$layout.class
│   │   │   │           │           R$string.class
│   │   │   │           │           R$style.class
│   │   │   │           │           R$styleable.class
│   │   │   │           │           R.class
│   │   │   │           │           
│   │   │   │           ├───butterknife
│   │   │   │           │   │   R$attr.class
│   │   │   │           │   │   R$color.class
│   │   │   │           │   │   R$dimen.class
│   │   │   │           │   │   R$drawable.class
│   │   │   │           │   │   R$id.class
│   │   │   │           │   │   R$integer.class
│   │   │   │           │   │   R$layout.class
│   │   │   │           │   │   R$string.class
│   │   │   │           │   │   R$style.class
│   │   │   │           │   │   R$styleable.class
│   │   │   │           │   │   R.class
│   │   │   │           │   │   
│   │   │   │           │   └───runtime
│   │   │   │           │           R$attr.class
│   │   │   │           │           R$color.class
│   │   │   │           │           R$dimen.class
│   │   │   │           │           R$drawable.class
│   │   │   │           │           R$id.class
│   │   │   │           │           R$integer.class
│   │   │   │           │           R$layout.class
│   │   │   │           │           R$string.class
│   │   │   │           │           R$style.class
│   │   │   │           │           R$styleable.class
│   │   │   │           │           R.class
│   │   │   │           │           
│   │   │   │           ├───com
│   │   │   │           │   ├───brian
│   │   │   │           │   │   └───f0d1e
│   │   │   │           │   │       │   BuildConfig.class
│   │   │   │           │   │       │   MainActivity$1.class
│   │   │   │           │   │       │   MainActivity.class
│   │   │   │           │   │       │   R$anim.class
│   │   │   │           │   │       │   R$animator.class
│   │   │   │           │   │       │   R$attr.class
│   │   │   │           │   │       │   R$bool.class
│   │   │   │           │   │       │   R$color.class
│   │   │   │           │   │       │   R$dimen.class
│   │   │   │           │   │       │   R$drawable.class
│   │   │   │           │   │       │   R$id.class
│   │   │   │           │   │       │   R$integer.class
│   │   │   │           │   │       │   R$interpolator.class
│   │   │   │           │   │       │   R$layout.class
│   │   │   │           │   │       │   R$mipmap.class
│   │   │   │           │   │       │   R$string.class
│   │   │   │           │   │       │   R$style.class
│   │   │   │           │   │       │   R$styleable.class
│   │   │   │           │   │       │   R.class
│   │   │   │           │   │       │   RecipeDetailsActivity$1.class
│   │   │   │           │   │       │   RecipeDetailsActivity$2.class
│   │   │   │           │   │       │   RecipeDetailsActivity$3.class
│   │   │   │           │   │       │   RecipeDetailsActivity.class
│   │   │   │           │   │       │   
│   │   │   │           │   │       ├───Adapter
│   │   │   │           │   │       │       InstructionAdapter$InstructionViewHolder.class
│   │   │   │           │   │       │       InstructionAdapter.class
│   │   │   │           │   │       │       MyAdapter$1.class
│   │   │   │           │   │       │       MyAdapter$RecipeViewHolder.class
│   │   │   │           │   │       │       MyAdapter.class
│   │   │   │           │   │       │       
│   │   │   │           │   │       ├───Model
│   │   │   │           │   │       │       InstructionResponse.class
│   │   │   │           │   │       │       Recipe.class
│   │   │   │           │   │       │       RecipiesResponse.class
│   │   │   │           │   │       │       Step.class
│   │   │   │           │   │       │       
│   │   │   │           │   │       └───Retrofit
│   │   │   │           │   │               ApiClient.class
│   │   │   │           │   │               ApiInterface.class
│   │   │   │           │   │               
│   │   │   │           │   ├───google
│   │   │   │           │   │   └───android
│   │   │   │           │   │       └───material
│   │   │   │           │   │               R$anim.class
│   │   │   │           │   │               R$animator.class
│   │   │   │           │   │               R$attr.class
│   │   │   │           │   │               R$bool.class
│   │   │   │           │   │               R$color.class
│   │   │   │           │   │               R$dimen.class
│   │   │   │           │   │               R$drawable.class
│   │   │   │           │   │               R$id.class
│   │   │   │           │   │               R$integer.class
│   │   │   │           │   │               R$interpolator.class
│   │   │   │           │   │               R$layout.class
│   │   │   │           │   │               R$string.class
│   │   │   │           │   │               R$style.class
│   │   │   │           │   │               R$styleable.class
│   │   │   │           │   │               R.class
│   │   │   │           │   │               
│   │   │   │           │   └───squareup
│   │   │   │           │       └───picasso
│   │   │   │           │               R.class
│   │   │   │           │               
│   │   │   │           └───net
│   │   │   │               └───yslibrary
│   │   │   │                   └───android
│   │   │   │                       └───keyboardvisibilityevent
│   │   │   │                               R.class
│   │   │   │                               
│   │   │   ├───manifest_merge_blame_file
│   │   │   │   └───debug
│   │   │   │           manifest-merger-blame-debug-report.txt
│   │   │   │           
│   │   │   ├───merged_assets
│   │   │   │   └───debug
│   │   │   │       └───out
│   │   │   ├───merged_java_res
│   │   │   │   └───debug
│   │   │   │           out.jar
│   │   │   │           
│   │   │   ├───merged_jni_libs
│   │   │   │   └───debug
│   │   │   │       └───out
│   │   │   ├───merged_manifests
│   │   │   │   └───debug
│   │   │   │           AndroidManifest.xml
│   │   │   │           output.json
│   │   │   │           
│   │   │   ├───merged_native_libs
│   │   │   │   └───debug
│   │   │   │       └───out
│   │   │   ├───merged_shaders
│   │   │   │   └───debug
│   │   │   │       └───out
│   │   │   ├───metadata_feature_manifest
│   │   │   │   └───debug
│   │   │   │       └───processDebugManifest
│   │   │   │           └───metadata-feature
│   │   │   │                   output.json
│   │   │   │                   
│   │   │   ├───processed_res
│   │   │   │   └───debug
│   │   │   │       └───processDebugResources
│   │   │   │           └───out
│   │   │   │                   output.json
│   │   │   │                   resources-debug.ap_
│   │   │   │                   
│   │   │   ├───res
│   │   │   │   ├───merged
│   │   │   │   │   └───debug
│   │   │   │   │           anim-v21_design_bottom_sheet_slide_in.xml.flat
│   │   │   │   │           anim-v21_design_bottom_sheet_slide_out.xml.flat
│   │   │   │   │           animator-v21_design_appbar_state_list_animator.xml.flat
│   │   │   │   │           animator_design_fab_hide_motion_spec.xml.flat
│   │   │   │   │           animator_design_fab_show_motion_spec.xml.flat
│   │   │   │   │           animator_mtrl_btn_state_list_anim.xml.flat
│   │   │   │   │           animator_mtrl_btn_unelevated_state_list_anim.xml.flat
│   │   │   │   │           animator_mtrl_chip_state_list_anim.xml.flat
│   │   │   │   │           animator_mtrl_fab_hide_motion_spec.xml.flat
│   │   │   │   │           animator_mtrl_fab_show_motion_spec.xml.flat
│   │   │   │   │           animator_mtrl_fab_transformation_sheet_collapse_spec.xml.flat
│   │   │   │   │           animator_mtrl_fab_transformation_sheet_expand_spec.xml.flat
│   │   │   │   │           anim_abc_fade_in.xml.flat
│   │   │   │   │           anim_abc_fade_out.xml.flat
│   │   │   │   │           anim_abc_grow_fade_in_from_bottom.xml.flat
│   │   │   │   │           anim_abc_popup_enter.xml.flat
│   │   │   │   │           anim_abc_popup_exit.xml.flat
│   │   │   │   │           anim_abc_shrink_fade_out_from_bottom.xml.flat
│   │   │   │   │           anim_abc_slide_in_bottom.xml.flat
│   │   │   │   │           anim_abc_slide_in_top.xml.flat
│   │   │   │   │           anim_abc_slide_out_bottom.xml.flat
│   │   │   │   │           anim_abc_slide_out_top.xml.flat
│   │   │   │   │           anim_abc_tooltip_enter.xml.flat
│   │   │   │   │           anim_abc_tooltip_exit.xml.flat
│   │   │   │   │           anim_btn_checkbox_to_checked_box_inner_merged_animation.xml.flat
│   │   │   │   │           anim_btn_checkbox_to_checked_box_outer_merged_animation.xml.flat
│   │   │   │   │           anim_btn_checkbox_to_checked_icon_null_animation.xml.flat
│   │   │   │   │           anim_btn_checkbox_to_unchecked_box_inner_merged_animation.xml.flat
│   │   │   │   │           anim_btn_checkbox_to_unchecked_check_path_merged_animation.xml.flat
│   │   │   │   │           anim_btn_checkbox_to_unchecked_icon_null_animation.xml.flat
│   │   │   │   │           anim_btn_radio_to_off_mtrl_dot_group_animation.xml.flat
│   │   │   │   │           anim_btn_radio_to_off_mtrl_ring_outer_animation.xml.flat
│   │   │   │   │           anim_btn_radio_to_off_mtrl_ring_outer_path_animation.xml.flat
│   │   │   │   │           anim_btn_radio_to_on_mtrl_dot_group_animation.xml.flat
│   │   │   │   │           anim_btn_radio_to_on_mtrl_ring_outer_animation.xml.flat
│   │   │   │   │           anim_btn_radio_to_on_mtrl_ring_outer_path_animation.xml.flat
│   │   │   │   │           anim_design_snackbar_in.xml.flat
│   │   │   │   │           anim_design_snackbar_out.xml.flat
│   │   │   │   │           color-v21_abc_btn_colored_borderless_text_material.xml.flat
│   │   │   │   │           color-v23_abc_btn_colored_borderless_text_material.xml.flat
│   │   │   │   │           color-v23_abc_btn_colored_text_material.xml.flat
│   │   │   │   │           color-v23_abc_color_highlight_material.xml.flat
│   │   │   │   │           color-v23_abc_tint_btn_checkable.xml.flat
│   │   │   │   │           color-v23_abc_tint_default.xml.flat
│   │   │   │   │           color-v23_abc_tint_edittext.xml.flat
│   │   │   │   │           color-v23_abc_tint_seek_thumb.xml.flat
│   │   │   │   │           color-v23_abc_tint_spinner.xml.flat
│   │   │   │   │           color-v23_abc_tint_switch_track.xml.flat
│   │   │   │   │           color-v23_design_tint_password_toggle.xml.flat
│   │   │   │   │           color_abc_background_cache_hint_selector_material_dark.xml.flat
│   │   │   │   │           color_abc_background_cache_hint_selector_material_light.xml.flat
│   │   │   │   │           color_abc_btn_colored_text_material.xml.flat
│   │   │   │   │           color_abc_hint_foreground_material_dark.xml.flat
│   │   │   │   │           color_abc_hint_foreground_material_light.xml.flat
│   │   │   │   │           color_abc_primary_text_disable_only_material_dark.xml.flat
│   │   │   │   │           color_abc_primary_text_disable_only_material_light.xml.flat
│   │   │   │   │           color_abc_primary_text_material_dark.xml.flat
│   │   │   │   │           color_abc_primary_text_material_light.xml.flat
│   │   │   │   │           color_abc_search_url_text.xml.flat
│   │   │   │   │           color_abc_secondary_text_material_dark.xml.flat
│   │   │   │   │           color_abc_secondary_text_material_light.xml.flat
│   │   │   │   │           color_abc_tint_btn_checkable.xml.flat
│   │   │   │   │           color_abc_tint_default.xml.flat
│   │   │   │   │           color_abc_tint_edittext.xml.flat
│   │   │   │   │           color_abc_tint_seek_thumb.xml.flat
│   │   │   │   │           color_abc_tint_spinner.xml.flat
│   │   │   │   │           color_abc_tint_switch_track.xml.flat
│   │   │   │   │           color_design_error.xml.flat
│   │   │   │   │           color_design_tint_password_toggle.xml.flat
│   │   │   │   │           color_mtrl_bottom_nav_colored_item_tint.xml.flat
│   │   │   │   │           color_mtrl_bottom_nav_item_tint.xml.flat
│   │   │   │   │           color_mtrl_btn_bg_color_selector.xml.flat
│   │   │   │   │           color_mtrl_btn_ripple_color.xml.flat
│   │   │   │   │           color_mtrl_btn_stroke_color_selector.xml.flat
│   │   │   │   │           color_mtrl_btn_text_btn_ripple_color.xml.flat
│   │   │   │   │           color_mtrl_btn_text_color_selector.xml.flat
│   │   │   │   │           color_mtrl_chip_background_color.xml.flat
│   │   │   │   │           color_mtrl_chip_close_icon_tint.xml.flat
│   │   │   │   │           color_mtrl_chip_ripple_color.xml.flat
│   │   │   │   │           color_mtrl_chip_text_color.xml.flat
│   │   │   │   │           color_mtrl_fab_ripple_color.xml.flat
│   │   │   │   │           color_mtrl_tabs_colored_ripple_color.xml.flat
│   │   │   │   │           color_mtrl_tabs_icon_color_selector.xml.flat
│   │   │   │   │           color_mtrl_tabs_icon_color_selector_colored.xml.flat
│   │   │   │   │           color_mtrl_tabs_legacy_text_color_selector.xml.flat
│   │   │   │   │           color_mtrl_tabs_ripple_color.xml.flat
│   │   │   │   │           color_mtrl_text_btn_text_color_selector.xml.flat
│   │   │   │   │           color_switch_thumb_material_dark.xml.flat
│   │   │   │   │           color_switch_thumb_material_light.xml.flat
│   │   │   │   │           drawable-anydpi-v21_design_ic_visibility.xml.flat
│   │   │   │   │           drawable-anydpi-v21_design_ic_visibility_off.xml.flat
│   │   │   │   │           drawable-hdpi-v4_abc_ab_share_pack_mtrl_alpha.9.png.flat
│   │   │   │   │           drawable-hdpi-v4_abc_btn_check_to_on_mtrl_000.png.flat
│   │   │   │   │           drawable-hdpi-v4_abc_btn_check_to_on_mtrl_015.png.flat
│   │   │   │   │           drawable-hdpi-v4_abc_btn_radio_to_on_mtrl_000.png.flat
│   │   │   │   │           drawable-hdpi-v4_abc_btn_radio_to_on_mtrl_015.png.flat
│   │   │   │   │           drawable-hdpi-v4_abc_btn_switch_to_on_mtrl_00001.9.png.flat
│   │   │   │   │           drawable-hdpi-v4_abc_btn_switch_to_on_mtrl_00012.9.png.flat
│   │   │   │   │           drawable-hdpi-v4_abc_cab_background_top_mtrl_alpha.9.png.flat
│   │   │   │   │           drawable-hdpi-v4_abc_ic_commit_search_api_mtrl_alpha.png.flat
│   │   │   │   │           drawable-hdpi-v4_abc_ic_menu_copy_mtrl_am_alpha.png.flat
│   │   │   │   │           drawable-hdpi-v4_abc_ic_menu_cut_mtrl_alpha.png.flat
│   │   │   │   │           drawable-hdpi-v4_abc_ic_menu_paste_mtrl_am_alpha.png.flat
│   │   │   │   │           drawable-hdpi-v4_abc_ic_menu_selectall_mtrl_alpha.png.flat
│   │   │   │   │           drawable-hdpi-v4_abc_ic_menu_share_mtrl_alpha.png.flat
│   │   │   │   │           drawable-hdpi-v4_abc_ic_star_black_16dp.png.flat
│   │   │   │   │           drawable-hdpi-v4_abc_ic_star_black_36dp.png.flat
│   │   │   │   │           drawable-hdpi-v4_abc_ic_star_black_48dp.png.flat
│   │   │   │   │           drawable-hdpi-v4_abc_ic_star_half_black_16dp.png.flat
│   │   │   │   │           drawable-hdpi-v4_abc_ic_star_half_black_36dp.png.flat
│   │   │   │   │           drawable-hdpi-v4_abc_ic_star_half_black_48dp.png.flat
│   │   │   │   │           drawable-hdpi-v4_abc_list_divider_mtrl_alpha.9.png.flat
│   │   │   │   │           drawable-hdpi-v4_abc_list_focused_holo.9.png.flat
│   │   │   │   │           drawable-hdpi-v4_abc_list_longpressed_holo.9.png.flat
│   │   │   │   │           drawable-hdpi-v4_abc_list_pressed_holo_dark.9.png.flat
│   │   │   │   │           drawable-hdpi-v4_abc_list_pressed_holo_light.9.png.flat
│   │   │   │   │           drawable-hdpi-v4_abc_list_selector_disabled_holo_dark.9.png.flat
│   │   │   │   │           drawable-hdpi-v4_abc_list_selector_disabled_holo_light.9.png.flat
│   │   │   │   │           drawable-hdpi-v4_abc_menu_hardkey_panel_mtrl_mult.9.png.flat
│   │   │   │   │           drawable-hdpi-v4_abc_popup_background_mtrl_mult.9.png.flat
│   │   │   │   │           drawable-hdpi-v4_abc_scrubber_control_off_mtrl_alpha.png.flat
│   │   │   │   │           drawable-hdpi-v4_abc_scrubber_control_to_pressed_mtrl_000.png.flat
│   │   │   │   │           drawable-hdpi-v4_abc_scrubber_control_to_pressed_mtrl_005.png.flat
│   │   │   │   │           drawable-hdpi-v4_abc_scrubber_primary_mtrl_alpha.9.png.flat
│   │   │   │   │           drawable-hdpi-v4_abc_scrubber_track_mtrl_alpha.9.png.flat
│   │   │   │   │           drawable-hdpi-v4_abc_spinner_mtrl_am_alpha.9.png.flat
│   │   │   │   │           drawable-hdpi-v4_abc_switch_track_mtrl_alpha.9.png.flat
│   │   │   │   │           drawable-hdpi-v4_abc_tab_indicator_mtrl_alpha.9.png.flat
│   │   │   │   │           drawable-hdpi-v4_abc_textfield_activated_mtrl_alpha.9.png.flat
│   │   │   │   │           drawable-hdpi-v4_abc_textfield_default_mtrl_alpha.9.png.flat
│   │   │   │   │           drawable-hdpi-v4_abc_textfield_search_activated_mtrl_alpha.9.png.flat
│   │   │   │   │           drawable-hdpi-v4_abc_textfield_search_default_mtrl_alpha.9.png.flat
│   │   │   │   │           drawable-hdpi-v4_abc_text_select_handle_left_mtrl_dark.png.flat
│   │   │   │   │           drawable-hdpi-v4_abc_text_select_handle_left_mtrl_light.png.flat
│   │   │   │   │           drawable-hdpi-v4_abc_text_select_handle_middle_mtrl_dark.png.flat
│   │   │   │   │           drawable-hdpi-v4_abc_text_select_handle_middle_mtrl_light.png.flat
│   │   │   │   │           drawable-hdpi-v4_abc_text_select_handle_right_mtrl_dark.png.flat
│   │   │   │   │           drawable-hdpi-v4_abc_text_select_handle_right_mtrl_light.png.flat
│   │   │   │   │           drawable-hdpi-v4_design_ic_visibility.png.flat
│   │   │   │   │           drawable-hdpi-v4_design_ic_visibility_off.png.flat
│   │   │   │   │           drawable-hdpi-v4_notification_bg_low_normal.9.png.flat
│   │   │   │   │           drawable-hdpi-v4_notification_bg_low_pressed.9.png.flat
│   │   │   │   │           drawable-hdpi-v4_notification_bg_normal.9.png.flat
│   │   │   │   │           drawable-hdpi-v4_notification_bg_normal_pressed.9.png.flat
│   │   │   │   │           drawable-hdpi-v4_notify_panel_notification_icon_bg.png.flat
│   │   │   │   │           drawable-ldrtl-hdpi-v17_abc_ic_menu_copy_mtrl_am_alpha.png.flat
│   │   │   │   │           drawable-ldrtl-hdpi-v17_abc_ic_menu_cut_mtrl_alpha.png.flat
│   │   │   │   │           drawable-ldrtl-hdpi-v17_abc_spinner_mtrl_am_alpha.9.png.flat
│   │   │   │   │           drawable-ldrtl-mdpi-v17_abc_ic_menu_copy_mtrl_am_alpha.png.flat
│   │   │   │   │           drawable-ldrtl-mdpi-v17_abc_ic_menu_cut_mtrl_alpha.png.flat
│   │   │   │   │           drawable-ldrtl-mdpi-v17_abc_spinner_mtrl_am_alpha.9.png.flat
│   │   │   │   │           drawable-ldrtl-xhdpi-v17_abc_ic_menu_copy_mtrl_am_alpha.png.flat
│   │   │   │   │           drawable-ldrtl-xhdpi-v17_abc_ic_menu_cut_mtrl_alpha.png.flat
│   │   │   │   │           drawable-ldrtl-xhdpi-v17_abc_spinner_mtrl_am_alpha.9.png.flat
│   │   │   │   │           drawable-ldrtl-xxhdpi-v17_abc_ic_menu_copy_mtrl_am_alpha.png.flat
│   │   │   │   │           drawable-ldrtl-xxhdpi-v17_abc_ic_menu_cut_mtrl_alpha.png.flat
│   │   │   │   │           drawable-ldrtl-xxhdpi-v17_abc_spinner_mtrl_am_alpha.9.png.flat
│   │   │   │   │           drawable-ldrtl-xxxhdpi-v17_abc_ic_menu_copy_mtrl_am_alpha.png.flat
│   │   │   │   │           drawable-ldrtl-xxxhdpi-v17_abc_ic_menu_cut_mtrl_alpha.png.flat
│   │   │   │   │           drawable-ldrtl-xxxhdpi-v17_abc_spinner_mtrl_am_alpha.9.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_ab_share_pack_mtrl_alpha.9.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_btn_check_to_on_mtrl_000.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_btn_check_to_on_mtrl_015.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_btn_radio_to_on_mtrl_000.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_btn_radio_to_on_mtrl_015.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_btn_switch_to_on_mtrl_00001.9.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_btn_switch_to_on_mtrl_00012.9.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_cab_background_top_mtrl_alpha.9.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_ic_commit_search_api_mtrl_alpha.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_ic_menu_copy_mtrl_am_alpha.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_ic_menu_cut_mtrl_alpha.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_ic_menu_paste_mtrl_am_alpha.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_ic_menu_selectall_mtrl_alpha.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_ic_menu_share_mtrl_alpha.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_ic_star_black_16dp.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_ic_star_black_36dp.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_ic_star_black_48dp.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_ic_star_half_black_16dp.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_ic_star_half_black_36dp.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_ic_star_half_black_48dp.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_list_divider_mtrl_alpha.9.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_list_focused_holo.9.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_list_longpressed_holo.9.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_list_pressed_holo_dark.9.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_list_pressed_holo_light.9.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_list_selector_disabled_holo_dark.9.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_list_selector_disabled_holo_light.9.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_menu_hardkey_panel_mtrl_mult.9.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_popup_background_mtrl_mult.9.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_scrubber_control_off_mtrl_alpha.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_scrubber_control_to_pressed_mtrl_000.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_scrubber_control_to_pressed_mtrl_005.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_scrubber_primary_mtrl_alpha.9.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_scrubber_track_mtrl_alpha.9.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_spinner_mtrl_am_alpha.9.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_switch_track_mtrl_alpha.9.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_tab_indicator_mtrl_alpha.9.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_textfield_activated_mtrl_alpha.9.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_textfield_default_mtrl_alpha.9.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_textfield_search_activated_mtrl_alpha.9.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_textfield_search_default_mtrl_alpha.9.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_text_select_handle_left_mtrl_dark.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_text_select_handle_left_mtrl_light.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_text_select_handle_middle_mtrl_dark.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_text_select_handle_middle_mtrl_light.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_text_select_handle_right_mtrl_dark.png.flat
│   │   │   │   │           drawable-mdpi-v4_abc_text_select_handle_right_mtrl_light.png.flat
│   │   │   │   │           drawable-mdpi-v4_design_ic_visibility.png.flat
│   │   │   │   │           drawable-mdpi-v4_design_ic_visibility_off.png.flat
│   │   │   │   │           drawable-mdpi-v4_notification_bg_low_normal.9.png.flat
│   │   │   │   │           drawable-mdpi-v4_notification_bg_low_pressed.9.png.flat
│   │   │   │   │           drawable-mdpi-v4_notification_bg_normal.9.png.flat
│   │   │   │   │           drawable-mdpi-v4_notification_bg_normal_pressed.9.png.flat
│   │   │   │   │           drawable-mdpi-v4_notify_panel_notification_icon_bg.png.flat
│   │   │   │   │           drawable-v21_abc_action_bar_item_background_material.xml.flat
│   │   │   │   │           drawable-v21_abc_btn_colored_material.xml.flat
│   │   │   │   │           drawable-v21_abc_dialog_material_background.xml.flat
│   │   │   │   │           drawable-v21_abc_edit_text_material.xml.flat
│   │   │   │   │           drawable-v21_abc_list_divider_material.xml.flat
│   │   │   │   │           drawable-v21_avd_hide_password.xml.flat
│   │   │   │   │           drawable-v21_avd_show_password.xml.flat
│   │   │   │   │           drawable-v21_design_bottom_navigation_item_background.xml.flat
│   │   │   │   │           drawable-v21_design_password_eye.xml.flat
│   │   │   │   │           drawable-v21_notification_action_background.xml.flat
│   │   │   │   │           drawable-v23_abc_control_background_material.xml.flat
│   │   │   │   │           drawable-v24_ic_launcher_foreground.xml.flat
│   │   │   │   │           drawable-watch-v20_abc_dialog_material_background.xml.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_ab_share_pack_mtrl_alpha.9.png.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_btn_check_to_on_mtrl_000.png.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_btn_check_to_on_mtrl_015.png.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_btn_radio_to_on_mtrl_000.png.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_btn_radio_to_on_mtrl_015.png.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_btn_switch_to_on_mtrl_00001.9.png.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_btn_switch_to_on_mtrl_00012.9.png.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_cab_background_top_mtrl_alpha.9.png.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_ic_commit_search_api_mtrl_alpha.png.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_ic_menu_copy_mtrl_am_alpha.png.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_ic_menu_cut_mtrl_alpha.png.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_ic_menu_paste_mtrl_am_alpha.png.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_ic_menu_selectall_mtrl_alpha.png.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_ic_menu_share_mtrl_alpha.png.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_ic_star_black_16dp.png.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_ic_star_black_36dp.png.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_ic_star_black_48dp.png.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_ic_star_half_black_16dp.png.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_ic_star_half_black_36dp.png.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_ic_star_half_black_48dp.png.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_list_divider_mtrl_alpha.9.png.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_list_focused_holo.9.png.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_list_longpressed_holo.9.png.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_list_pressed_holo_dark.9.png.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_list_pressed_holo_light.9.png.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_list_selector_disabled_holo_dark.9.png.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_list_selector_disabled_holo_light.9.png.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_menu_hardkey_panel_mtrl_mult.9.png.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_popup_background_mtrl_mult.9.png.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_scrubber_control_off_mtrl_alpha.png.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_scrubber_control_to_pressed_mtrl_000.png.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_scrubber_control_to_pressed_mtrl_005.png.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_scrubber_primary_mtrl_alpha.9.png.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_scrubber_track_mtrl_alpha.9.png.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_spinner_mtrl_am_alpha.9.png.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_switch_track_mtrl_alpha.9.png.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_tab_indicator_mtrl_alpha.9.png.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_textfield_activated_mtrl_alpha.9.png.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_textfield_default_mtrl_alpha.9.png.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_textfield_search_activated_mtrl_alpha.9.png.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_textfield_search_default_mtrl_alpha.9.png.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_text_select_handle_left_mtrl_dark.png.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_text_select_handle_left_mtrl_light.png.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_text_select_handle_middle_mtrl_dark.png.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_text_select_handle_middle_mtrl_light.png.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_text_select_handle_right_mtrl_dark.png.flat
│   │   │   │   │           drawable-xhdpi-v4_abc_text_select_handle_right_mtrl_light.png.flat
│   │   │   │   │           drawable-xhdpi-v4_design_ic_visibility.png.flat
│   │   │   │   │           drawable-xhdpi-v4_design_ic_visibility_off.png.flat
│   │   │   │   │           drawable-xhdpi-v4_notification_bg_low_normal.9.png.flat
│   │   │   │   │           drawable-xhdpi-v4_notification_bg_low_pressed.9.png.flat
│   │   │   │   │           drawable-xhdpi-v4_notification_bg_normal.9.png.flat
│   │   │   │   │           drawable-xhdpi-v4_notification_bg_normal_pressed.9.png.flat
│   │   │   │   │           drawable-xhdpi-v4_notify_panel_notification_icon_bg.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_ab_share_pack_mtrl_alpha.9.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_btn_check_to_on_mtrl_000.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_btn_check_to_on_mtrl_015.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_btn_radio_to_on_mtrl_000.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_btn_radio_to_on_mtrl_015.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_btn_switch_to_on_mtrl_00001.9.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_btn_switch_to_on_mtrl_00012.9.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_cab_background_top_mtrl_alpha.9.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_ic_commit_search_api_mtrl_alpha.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_ic_menu_copy_mtrl_am_alpha.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_ic_menu_cut_mtrl_alpha.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_ic_menu_paste_mtrl_am_alpha.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_ic_menu_selectall_mtrl_alpha.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_ic_menu_share_mtrl_alpha.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_ic_star_black_16dp.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_ic_star_black_36dp.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_ic_star_black_48dp.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_ic_star_half_black_16dp.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_ic_star_half_black_36dp.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_ic_star_half_black_48dp.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_list_divider_mtrl_alpha.9.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_list_focused_holo.9.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_list_longpressed_holo.9.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_list_pressed_holo_dark.9.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_list_pressed_holo_light.9.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_list_selector_disabled_holo_dark.9.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_list_selector_disabled_holo_light.9.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_menu_hardkey_panel_mtrl_mult.9.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_popup_background_mtrl_mult.9.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_scrubber_control_off_mtrl_alpha.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_scrubber_control_to_pressed_mtrl_000.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_scrubber_control_to_pressed_mtrl_005.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_scrubber_primary_mtrl_alpha.9.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_scrubber_track_mtrl_alpha.9.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_spinner_mtrl_am_alpha.9.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_switch_track_mtrl_alpha.9.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_tab_indicator_mtrl_alpha.9.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_textfield_activated_mtrl_alpha.9.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_textfield_default_mtrl_alpha.9.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_textfield_search_activated_mtrl_alpha.9.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_textfield_search_default_mtrl_alpha.9.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_text_select_handle_left_mtrl_dark.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_text_select_handle_left_mtrl_light.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_text_select_handle_middle_mtrl_dark.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_text_select_handle_middle_mtrl_light.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_text_select_handle_right_mtrl_dark.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_abc_text_select_handle_right_mtrl_light.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_design_ic_visibility.png.flat
│   │   │   │   │           drawable-xxhdpi-v4_design_ic_visibility_off.png.flat
│   │   │   │   │           drawable-xxxhdpi-v4_abc_btn_check_to_on_mtrl_000.png.flat
│   │   │   │   │           drawable-xxxhdpi-v4_abc_btn_check_to_on_mtrl_015.png.flat
│   │   │   │   │           drawable-xxxhdpi-v4_abc_btn_radio_to_on_mtrl_000.png.flat
│   │   │   │   │           drawable-xxxhdpi-v4_abc_btn_radio_to_on_mtrl_015.png.flat
│   │   │   │   │           drawable-xxxhdpi-v4_abc_btn_switch_to_on_mtrl_00001.9.png.flat
│   │   │   │   │           drawable-xxxhdpi-v4_abc_btn_switch_to_on_mtrl_00012.9.png.flat
│   │   │   │   │           drawable-xxxhdpi-v4_abc_ic_menu_copy_mtrl_am_alpha.png.flat
│   │   │   │   │           drawable-xxxhdpi-v4_abc_ic_menu_cut_mtrl_alpha.png.flat
│   │   │   │   │           drawable-xxxhdpi-v4_abc_ic_menu_paste_mtrl_am_alpha.png.flat
│   │   │   │   │           drawable-xxxhdpi-v4_abc_ic_menu_selectall_mtrl_alpha.png.flat
│   │   │   │   │           drawable-xxxhdpi-v4_abc_ic_menu_share_mtrl_alpha.png.flat
│   │   │   │   │           drawable-xxxhdpi-v4_abc_ic_star_black_16dp.png.flat
│   │   │   │   │           drawable-xxxhdpi-v4_abc_ic_star_black_36dp.png.flat
│   │   │   │   │           drawable-xxxhdpi-v4_abc_ic_star_black_48dp.png.flat
│   │   │   │   │           drawable-xxxhdpi-v4_abc_ic_star_half_black_16dp.png.flat
│   │   │   │   │           drawable-xxxhdpi-v4_abc_ic_star_half_black_36dp.png.flat
│   │   │   │   │           drawable-xxxhdpi-v4_abc_ic_star_half_black_48dp.png.flat
│   │   │   │   │           drawable-xxxhdpi-v4_abc_scrubber_control_to_pressed_mtrl_000.png.flat
│   │   │   │   │           drawable-xxxhdpi-v4_abc_scrubber_control_to_pressed_mtrl_005.png.flat
│   │   │   │   │           drawable-xxxhdpi-v4_abc_spinner_mtrl_am_alpha.9.png.flat
│   │   │   │   │           drawable-xxxhdpi-v4_abc_switch_track_mtrl_alpha.9.png.flat
│   │   │   │   │           drawable-xxxhdpi-v4_abc_tab_indicator_mtrl_alpha.9.png.flat
│   │   │   │   │           drawable-xxxhdpi-v4_abc_text_select_handle_left_mtrl_dark.png.flat
│   │   │   │   │           drawable-xxxhdpi-v4_abc_text_select_handle_left_mtrl_light.png.flat
│   │   │   │   │           drawable-xxxhdpi-v4_abc_text_select_handle_right_mtrl_dark.png.flat
│   │   │   │   │           drawable-xxxhdpi-v4_abc_text_select_handle_right_mtrl_light.png.flat
│   │   │   │   │           drawable-xxxhdpi-v4_design_ic_visibility.png.flat
│   │   │   │   │           drawable-xxxhdpi-v4_design_ic_visibility_off.png.flat
│   │   │   │   │           drawable_abc_btn_borderless_material.xml.flat
│   │   │   │   │           drawable_abc_btn_check_material.xml.flat
│   │   │   │   │           drawable_abc_btn_check_material_anim.xml.flat
│   │   │   │   │           drawable_abc_btn_default_mtrl_shape.xml.flat
│   │   │   │   │           drawable_abc_btn_radio_material.xml.flat
│   │   │   │   │           drawable_abc_btn_radio_material_anim.xml.flat
│   │   │   │   │           drawable_abc_cab_background_internal_bg.xml.flat
│   │   │   │   │           drawable_abc_cab_background_top_material.xml.flat
│   │   │   │   │           drawable_abc_ic_ab_back_material.xml.flat
│   │   │   │   │           drawable_abc_ic_arrow_drop_right_black_24dp.xml.flat
│   │   │   │   │           drawable_abc_ic_clear_material.xml.flat
│   │   │   │   │           drawable_abc_ic_go_search_api_material.xml.flat
│   │   │   │   │           drawable_abc_ic_menu_overflow_material.xml.flat
│   │   │   │   │           drawable_abc_ic_search_api_material.xml.flat
│   │   │   │   │           drawable_abc_ic_voice_search_api_material.xml.flat
│   │   │   │   │           drawable_abc_item_background_holo_dark.xml.flat
│   │   │   │   │           drawable_abc_item_background_holo_light.xml.flat
│   │   │   │   │           drawable_abc_list_selector_background_transition_holo_dark.xml.flat
│   │   │   │   │           drawable_abc_list_selector_background_transition_holo_light.xml.flat
│   │   │   │   │           drawable_abc_list_selector_holo_dark.xml.flat
│   │   │   │   │           drawable_abc_list_selector_holo_light.xml.flat
│   │   │   │   │           drawable_abc_ratingbar_indicator_material.xml.flat
│   │   │   │   │           drawable_abc_ratingbar_material.xml.flat
│   │   │   │   │           drawable_abc_ratingbar_small_material.xml.flat
│   │   │   │   │           drawable_abc_seekbar_thumb_material.xml.flat
│   │   │   │   │           drawable_abc_seekbar_tick_mark_material.xml.flat
│   │   │   │   │           drawable_abc_seekbar_track_material.xml.flat
│   │   │   │   │           drawable_abc_spinner_textfield_background_material.xml.flat
│   │   │   │   │           drawable_abc_switch_thumb_material.xml.flat
│   │   │   │   │           drawable_abc_tab_indicator_material.xml.flat
│   │   │   │   │           drawable_abc_textfield_search_material.xml.flat
│   │   │   │   │           drawable_abc_text_cursor_material.xml.flat
│   │   │   │   │           drawable_abc_vector_test.xml.flat
│   │   │   │   │           drawable_btn_checkbox_checked_mtrl.xml.flat
│   │   │   │   │           drawable_btn_checkbox_checked_to_unchecked_mtrl_animation.xml.flat
│   │   │   │   │           drawable_btn_checkbox_unchecked_mtrl.xml.flat
│   │   │   │   │           drawable_btn_checkbox_unchecked_to_checked_mtrl_animation.xml.flat
│   │   │   │   │           drawable_btn_radio_off_mtrl.xml.flat
│   │   │   │   │           drawable_btn_radio_off_to_on_mtrl_animation.xml.flat
│   │   │   │   │           drawable_btn_radio_on_mtrl.xml.flat
│   │   │   │   │           drawable_btn_radio_on_to_off_mtrl_animation.xml.flat
│   │   │   │   │           drawable_design_fab_background.xml.flat
│   │   │   │   │           drawable_design_snackbar_background.xml.flat
│   │   │   │   │           drawable_header.png.flat
│   │   │   │   │           drawable_ic_launcher_background.xml.flat
│   │   │   │   │           drawable_ic_mtrl_chip_checked_black.xml.flat
│   │   │   │   │           drawable_ic_mtrl_chip_checked_circle.xml.flat
│   │   │   │   │           drawable_ic_mtrl_chip_close_circle.xml.flat
│   │   │   │   │           drawable_mtrl_snackbar_background.xml.flat
│   │   │   │   │           drawable_mtrl_tabs_default_indicator.xml.flat
│   │   │   │   │           drawable_navigation_empty_icon.xml.flat
│   │   │   │   │           drawable_notification_bg.xml.flat
│   │   │   │   │           drawable_notification_bg_low.xml.flat
│   │   │   │   │           drawable_notification_icon_background.xml.flat
│   │   │   │   │           drawable_notification_tile_bg.xml.flat
│   │   │   │   │           drawable_searchview_rounded.xml.flat
│   │   │   │   │           drawable_tooltip_frame_dark.xml.flat
│   │   │   │   │           drawable_tooltip_frame_light.xml.flat
│   │   │   │   │           interpolator-v21_mtrl_fast_out_linear_in.xml.flat
│   │   │   │   │           interpolator-v21_mtrl_fast_out_slow_in.xml.flat
│   │   │   │   │           interpolator-v21_mtrl_linear_out_slow_in.xml.flat
│   │   │   │   │           interpolator_btn_checkbox_checked_mtrl_animation_interpolator_0.xml.flat
│   │   │   │   │           interpolator_btn_checkbox_checked_mtrl_animation_interpolator_1.xml.flat
│   │   │   │   │           interpolator_btn_checkbox_unchecked_mtrl_animation_interpolator_0.xml.flat
│   │   │   │   │           interpolator_btn_checkbox_unchecked_mtrl_animation_interpolator_1.xml.flat
│   │   │   │   │           interpolator_btn_radio_to_off_mtrl_animation_interpolator_0.xml.flat
│   │   │   │   │           interpolator_btn_radio_to_on_mtrl_animation_interpolator_0.xml.flat
│   │   │   │   │           interpolator_fast_out_slow_in.xml.flat
│   │   │   │   │           interpolator_mtrl_linear.xml.flat
│   │   │   │   │           layout-sw600dp-v13_design_layout_snackbar.xml.flat
│   │   │   │   │           layout-sw600dp-v13_mtrl_layout_snackbar.xml.flat
│   │   │   │   │           layout-v21_notification_action.xml.flat
│   │   │   │   │           layout-v21_notification_action_tombstone.xml.flat
│   │   │   │   │           layout-v21_notification_template_custom_big.xml.flat
│   │   │   │   │           layout-v21_notification_template_icon_group.xml.flat
│   │   │   │   │           layout-v26_abc_screen_toolbar.xml.flat
│   │   │   │   │           layout-watch-v20_abc_alert_dialog_button_bar_material.xml.flat
│   │   │   │   │           layout-watch-v20_abc_alert_dialog_title_material.xml.flat
│   │   │   │   │           layout_abc_action_bar_title_item.xml.flat
│   │   │   │   │           layout_abc_action_bar_up_container.xml.flat
│   │   │   │   │           layout_abc_action_menu_item_layout.xml.flat
│   │   │   │   │           layout_abc_action_menu_layout.xml.flat
│   │   │   │   │           layout_abc_action_mode_bar.xml.flat
│   │   │   │   │           layout_abc_action_mode_close_item_material.xml.flat
│   │   │   │   │           layout_abc_activity_chooser_view.xml.flat
│   │   │   │   │           layout_abc_activity_chooser_view_list_item.xml.flat
│   │   │   │   │           layout_abc_alert_dialog_button_bar_material.xml.flat
│   │   │   │   │           layout_abc_alert_dialog_material.xml.flat
│   │   │   │   │           layout_abc_alert_dialog_title_material.xml.flat
│   │   │   │   │           layout_abc_cascading_menu_item_layout.xml.flat
│   │   │   │   │           layout_abc_dialog_title_material.xml.flat
│   │   │   │   │           layout_abc_expanded_menu_layout.xml.flat
│   │   │   │   │           layout_abc_list_menu_item_checkbox.xml.flat
│   │   │   │   │           layout_abc_list_menu_item_icon.xml.flat
│   │   │   │   │           layout_abc_list_menu_item_layout.xml.flat
│   │   │   │   │           layout_abc_list_menu_item_radio.xml.flat
│   │   │   │   │           layout_abc_popup_menu_header_item_layout.xml.flat
│   │   │   │   │           layout_abc_popup_menu_item_layout.xml.flat
│   │   │   │   │           layout_abc_screen_content_include.xml.flat
│   │   │   │   │           layout_abc_screen_simple.xml.flat
│   │   │   │   │           layout_abc_screen_simple_overlay_action_mode.xml.flat
│   │   │   │   │           layout_abc_screen_toolbar.xml.flat
│   │   │   │   │           layout_abc_search_dropdown_item_icons_2line.xml.flat
│   │   │   │   │           layout_abc_search_view.xml.flat
│   │   │   │   │           layout_abc_select_dialog_material.xml.flat
│   │   │   │   │           layout_abc_tooltip.xml.flat
│   │   │   │   │           layout_activity_main.xml.flat
│   │   │   │   │           layout_activity_recipe_details.xml.flat
│   │   │   │   │           layout_content_recipe_details.xml.flat
│   │   │   │   │           layout_custom_dialog.xml.flat
│   │   │   │   │           layout_design_bottom_navigation_item.xml.flat
│   │   │   │   │           layout_design_bottom_sheet_dialog.xml.flat
│   │   │   │   │           layout_design_layout_snackbar.xml.flat
│   │   │   │   │           layout_design_layout_snackbar_include.xml.flat
│   │   │   │   │           layout_design_layout_tab_icon.xml.flat
│   │   │   │   │           layout_design_layout_tab_text.xml.flat
│   │   │   │   │           layout_design_menu_item_action_area.xml.flat
│   │   │   │   │           layout_design_navigation_item.xml.flat
│   │   │   │   │           layout_design_navigation_item_header.xml.flat
│   │   │   │   │           layout_design_navigation_item_separator.xml.flat
│   │   │   │   │           layout_design_navigation_item_subheader.xml.flat
│   │   │   │   │           layout_design_navigation_menu.xml.flat
│   │   │   │   │           layout_design_navigation_menu_item.xml.flat
│   │   │   │   │           layout_design_text_input_password_icon.xml.flat
│   │   │   │   │           layout_mtrl_layout_snackbar.xml.flat
│   │   │   │   │           layout_mtrl_layout_snackbar_include.xml.flat
│   │   │   │   │           layout_notification_template_part_chronometer.xml.flat
│   │   │   │   │           layout_notification_template_part_time.xml.flat
│   │   │   │   │           layout_recycler_row.xml.flat
│   │   │   │   │           layout_select_dialog_item_material.xml.flat
│   │   │   │   │           layout_select_dialog_multichoice_material.xml.flat
│   │   │   │   │           layout_select_dialog_singlechoice_material.xml.flat
│   │   │   │   │           layout_steplist_row.xml.flat
│   │   │   │   │           layout_support_simple_spinner_dropdown_item.xml.flat
│   │   │   │   │           mipmap-anydpi-v26_ic_launcher.xml.flat
│   │   │   │   │           mipmap-anydpi-v26_ic_launcher_round.xml.flat
│   │   │   │   │           mipmap-hdpi_ic_launcher.png.flat
│   │   │   │   │           mipmap-hdpi_ic_launcher_foreground.png.flat
│   │   │   │   │           mipmap-hdpi_ic_launcher_round.png.flat
│   │   │   │   │           mipmap-mdpi_ic_launcher.png.flat
│   │   │   │   │           mipmap-mdpi_ic_launcher_foreground.png.flat
│   │   │   │   │           mipmap-mdpi_ic_launcher_round.png.flat
│   │   │   │   │           mipmap-xhdpi_ic_launcher.png.flat
│   │   │   │   │           mipmap-xhdpi_ic_launcher_foreground.png.flat
│   │   │   │   │           mipmap-xhdpi_ic_launcher_round.png.flat
│   │   │   │   │           mipmap-xxhdpi_ic_launcher.png.flat
│   │   │   │   │           mipmap-xxhdpi_ic_launcher_foreground.png.flat
│   │   │   │   │           mipmap-xxhdpi_ic_launcher_round.png.flat
│   │   │   │   │           mipmap-xxxhdpi_ic_launcher.png.flat
│   │   │   │   │           mipmap-xxxhdpi_ic_launcher_foreground.png.flat
│   │   │   │   │           mipmap-xxxhdpi_ic_launcher_round.png.flat
│   │   │   │   │           values-af_values-af.arsc.flat
│   │   │   │   │           values-am_values-am.arsc.flat
│   │   │   │   │           values-ar_values-ar.arsc.flat
│   │   │   │   │           values-as_values-as.arsc.flat
│   │   │   │   │           values-az_values-az.arsc.flat
│   │   │   │   │           values-b+sr+Latn_values-b+sr+Latn.arsc.flat
│   │   │   │   │           values-be_values-be.arsc.flat
│   │   │   │   │           values-bg_values-bg.arsc.flat
│   │   │   │   │           values-bn_values-bn.arsc.flat
│   │   │   │   │           values-bs_values-bs.arsc.flat
│   │   │   │   │           values-ca_values-ca.arsc.flat
│   │   │   │   │           values-cs_values-cs.arsc.flat
│   │   │   │   │           values-da_values-da.arsc.flat
│   │   │   │   │           values-de_values-de.arsc.flat
│   │   │   │   │           values-el_values-el.arsc.flat
│   │   │   │   │           values-en-rAU_values-en-rAU.arsc.flat
│   │   │   │   │           values-en-rCA_values-en-rCA.arsc.flat
│   │   │   │   │           values-en-rGB_values-en-rGB.arsc.flat
│   │   │   │   │           values-en-rIN_values-en-rIN.arsc.flat
│   │   │   │   │           values-en-rXC_values-en-rXC.arsc.flat
│   │   │   │   │           values-es-rUS_values-es-rUS.arsc.flat
│   │   │   │   │           values-es_values-es.arsc.flat
│   │   │   │   │           values-et_values-et.arsc.flat
│   │   │   │   │           values-eu_values-eu.arsc.flat
│   │   │   │   │           values-fa_values-fa.arsc.flat
│   │   │   │   │           values-fi_values-fi.arsc.flat
│   │   │   │   │           values-fr-rCA_values-fr-rCA.arsc.flat
│   │   │   │   │           values-fr_values-fr.arsc.flat
│   │   │   │   │           values-gl_values-gl.arsc.flat
│   │   │   │   │           values-gu_values-gu.arsc.flat
│   │   │   │   │           values-h720dp-v13_values-h720dp-v13.arsc.flat
│   │   │   │   │           values-hdpi-v4_values-hdpi-v4.arsc.flat
│   │   │   │   │           values-hi_values-hi.arsc.flat
│   │   │   │   │           values-hr_values-hr.arsc.flat
│   │   │   │   │           values-hu_values-hu.arsc.flat
│   │   │   │   │           values-hy_values-hy.arsc.flat
│   │   │   │   │           values-in_values-in.arsc.flat
│   │   │   │   │           values-is_values-is.arsc.flat
│   │   │   │   │           values-it_values-it.arsc.flat
│   │   │   │   │           values-iw_values-iw.arsc.flat
│   │   │   │   │           values-ja_values-ja.arsc.flat
│   │   │   │   │           values-ka_values-ka.arsc.flat
│   │   │   │   │           values-kk_values-kk.arsc.flat
│   │   │   │   │           values-km_values-km.arsc.flat
│   │   │   │   │           values-kn_values-kn.arsc.flat
│   │   │   │   │           values-ko_values-ko.arsc.flat
│   │   │   │   │           values-ky_values-ky.arsc.flat
│   │   │   │   │           values-land_values-land.arsc.flat
│   │   │   │   │           values-large-v4_values-large-v4.arsc.flat
│   │   │   │   │           values-ldltr-v21_values-ldltr-v21.arsc.flat
│   │   │   │   │           values-lo_values-lo.arsc.flat
│   │   │   │   │           values-lt_values-lt.arsc.flat
│   │   │   │   │           values-lv_values-lv.arsc.flat
│   │   │   │   │           values-mk_values-mk.arsc.flat
│   │   │   │   │           values-ml_values-ml.arsc.flat
│   │   │   │   │           values-mn_values-mn.arsc.flat
│   │   │   │   │           values-mr_values-mr.arsc.flat
│   │   │   │   │           values-ms_values-ms.arsc.flat
│   │   │   │   │           values-my_values-my.arsc.flat
│   │   │   │   │           values-nb_values-nb.arsc.flat
│   │   │   │   │           values-ne_values-ne.arsc.flat
│   │   │   │   │           values-night-v8_values-night-v8.arsc.flat
│   │   │   │   │           values-nl_values-nl.arsc.flat
│   │   │   │   │           values-or_values-or.arsc.flat
│   │   │   │   │           values-pa_values-pa.arsc.flat
│   │   │   │   │           values-pl_values-pl.arsc.flat
│   │   │   │   │           values-port_values-port.arsc.flat
│   │   │   │   │           values-pt-rBR_values-pt-rBR.arsc.flat
│   │   │   │   │           values-pt-rPT_values-pt-rPT.arsc.flat
│   │   │   │   │           values-pt_values-pt.arsc.flat
│   │   │   │   │           values-ro_values-ro.arsc.flat
│   │   │   │   │           values-ru_values-ru.arsc.flat
│   │   │   │   │           values-si_values-si.arsc.flat
│   │   │   │   │           values-sk_values-sk.arsc.flat
│   │   │   │   │           values-sl_values-sl.arsc.flat
│   │   │   │   │           values-sq_values-sq.arsc.flat
│   │   │   │   │           values-sr_values-sr.arsc.flat
│   │   │   │   │           values-sv_values-sv.arsc.flat
│   │   │   │   │           values-sw600dp-v13_values-sw600dp-v13.arsc.flat
│   │   │   │   │           values-sw_values-sw.arsc.flat
│   │   │   │   │           values-ta_values-ta.arsc.flat
│   │   │   │   │           values-te_values-te.arsc.flat
│   │   │   │   │           values-th_values-th.arsc.flat
│   │   │   │   │           values-tl_values-tl.arsc.flat
│   │   │   │   │           values-tr_values-tr.arsc.flat
│   │   │   │   │           values-uk_values-uk.arsc.flat
│   │   │   │   │           values-ur_values-ur.arsc.flat
│   │   │   │   │           values-uz_values-uz.arsc.flat
│   │   │   │   │           values-v16_values-v16.arsc.flat
│   │   │   │   │           values-v17_values-v17.arsc.flat
│   │   │   │   │           values-v18_values-v18.arsc.flat
│   │   │   │   │           values-v21_values-v21.arsc.flat
│   │   │   │   │           values-v22_values-v22.arsc.flat
│   │   │   │   │           values-v23_values-v23.arsc.flat
│   │   │   │   │           values-v24_values-v24.arsc.flat
│   │   │   │   │           values-v25_values-v25.arsc.flat
│   │   │   │   │           values-v26_values-v26.arsc.flat
│   │   │   │   │           values-v28_values-v28.arsc.flat
│   │   │   │   │           values-vi_values-vi.arsc.flat
│   │   │   │   │           values-watch-v20_values-watch-v20.arsc.flat
│   │   │   │   │           values-watch-v21_values-watch-v21.arsc.flat
│   │   │   │   │           values-xlarge-v4_values-xlarge-v4.arsc.flat
│   │   │   │   │           values-zh-rCN_values-zh-rCN.arsc.flat
│   │   │   │   │           values-zh-rHK_values-zh-rHK.arsc.flat
│   │   │   │   │           values-zh-rTW_values-zh-rTW.arsc.flat
│   │   │   │   │           values-zu_values-zu.arsc.flat
│   │   │   │   │           values_values.arsc.flat
│   │   │   │   │           
│   │   │   │   └───symbol-table-with-package
│   │   │   │       └───debug
│   │   │   │               package-aware-r.txt
│   │   │   │               
│   │   │   ├───shader_assets
│   │   │   │   └───debug
│   │   │   │       └───compileDebugShaders
│   │   │   │           └───out
│   │   │   ├───signing_config
│   │   │   │   └───debug
│   │   │   │       └───out
│   │   │   │               signing-config.json
│   │   │   │               
│   │   │   ├───stripped_native_libs
│   │   │   │   └───debug
│   │   │   │       └───out
│   │   │   ├───symbols
│   │   │   │   └───debug
│   │   │   │           R.txt
│   │   │   │           
│   │   │   ├───transforms
│   │   │   │   └───dexBuilder
│   │   │   │       └───debug
│   │   │   │           │   __content__.json
│   │   │   │           │   
│   │   │   │           └───0
│   │   │   │               ├───androidx
│   │   │   │               │   ├───activity
│   │   │   │               │   │       R$attr.dex
│   │   │   │               │   │       R$color.dex
│   │   │   │               │   │       R$dimen.dex
│   │   │   │               │   │       R$drawable.dex
│   │   │   │               │   │       R$id.dex
│   │   │   │               │   │       R$integer.dex
│   │   │   │               │   │       R$layout.dex
│   │   │   │               │   │       R$string.dex
│   │   │   │               │   │       R$style.dex
│   │   │   │               │   │       R$styleable.dex
│   │   │   │               │   │       R.dex
│   │   │   │               │   │       
│   │   │   │               │   ├───appcompat
│   │   │   │               │   │   │   R$anim.dex
│   │   │   │               │   │   │   R$attr.dex
│   │   │   │               │   │   │   R$bool.dex
│   │   │   │               │   │   │   R$color.dex
│   │   │   │               │   │   │   R$dimen.dex
│   │   │   │               │   │   │   R$drawable.dex
│   │   │   │               │   │   │   R$id.dex
│   │   │   │               │   │   │   R$integer.dex
│   │   │   │               │   │   │   R$interpolator.dex
│   │   │   │               │   │   │   R$layout.dex
│   │   │   │               │   │   │   R$string.dex
│   │   │   │               │   │   │   R$style.dex
│   │   │   │               │   │   │   R$styleable.dex
│   │   │   │               │   │   │   R.dex
│   │   │   │               │   │   │   
│   │   │   │               │   │   └───resources
│   │   │   │               │   │           R$attr.dex
│   │   │   │               │   │           R$color.dex
│   │   │   │               │   │           R$dimen.dex
│   │   │   │               │   │           R$drawable.dex
│   │   │   │               │   │           R$id.dex
│   │   │   │               │   │           R$integer.dex
│   │   │   │               │   │           R$layout.dex
│   │   │   │               │   │           R$string.dex
│   │   │   │               │   │           R$style.dex
│   │   │   │               │   │           R$styleable.dex
│   │   │   │               │   │           R.dex
│   │   │   │               │   │           
│   │   │   │               │   ├───arch
│   │   │   │               │   │   └───core
│   │   │   │               │   │           R.dex
│   │   │   │               │   │           
│   │   │   │               │   ├───asynclayoutinflater
│   │   │   │               │   │       R$attr.dex
│   │   │   │               │   │       R$color.dex
│   │   │   │               │   │       R$dimen.dex
│   │   │   │               │   │       R$drawable.dex
│   │   │   │               │   │       R$id.dex
│   │   │   │               │   │       R$integer.dex
│   │   │   │               │   │       R$layout.dex
│   │   │   │               │   │       R$string.dex
│   │   │   │               │   │       R$style.dex
│   │   │   │               │   │       R$styleable.dex
│   │   │   │               │   │       R.dex
│   │   │   │               │   │       
│   │   │   │               │   ├───cardview
│   │   │   │               │   │       R$attr.dex
│   │   │   │               │   │       R$color.dex
│   │   │   │               │   │       R$dimen.dex
│   │   │   │               │   │       R$style.dex
│   │   │   │               │   │       R$styleable.dex
│   │   │   │               │   │       R.dex
│   │   │   │               │   │       
│   │   │   │               │   ├───constraintlayout
│   │   │   │               │   │   └───widget
│   │   │   │               │   │           R$attr.dex
│   │   │   │               │   │           R$id.dex
│   │   │   │               │   │           R$styleable.dex
│   │   │   │               │   │           R.dex
│   │   │   │               │   │           
│   │   │   │               │   ├───coordinatorlayout
│   │   │   │               │   │       R$attr.dex
│   │   │   │               │   │       R$color.dex
│   │   │   │               │   │       R$dimen.dex
│   │   │   │               │   │       R$drawable.dex
│   │   │   │               │   │       R$id.dex
│   │   │   │               │   │       R$integer.dex
│   │   │   │               │   │       R$layout.dex
│   │   │   │               │   │       R$string.dex
│   │   │   │               │   │       R$style.dex
│   │   │   │               │   │       R$styleable.dex
│   │   │   │               │   │       R.dex
│   │   │   │               │   │       
│   │   │   │               │   ├───core
│   │   │   │               │   │       R$attr.dex
│   │   │   │               │   │       R$color.dex
│   │   │   │               │   │       R$dimen.dex
│   │   │   │               │   │       R$drawable.dex
│   │   │   │               │   │       R$id.dex
│   │   │   │               │   │       R$integer.dex
│   │   │   │               │   │       R$layout.dex
│   │   │   │               │   │       R$string.dex
│   │   │   │               │   │       R$style.dex
│   │   │   │               │   │       R$styleable.dex
│   │   │   │               │   │       R.dex
│   │   │   │               │   │       
│   │   │   │               │   ├───cursoradapter
│   │   │   │               │   │       R.dex
│   │   │   │               │   │       
│   │   │   │               │   ├───customview
│   │   │   │               │   │       R$attr.dex
│   │   │   │               │   │       R$color.dex
│   │   │   │               │   │       R$dimen.dex
│   │   │   │               │   │       R$drawable.dex
│   │   │   │               │   │       R$id.dex
│   │   │   │               │   │       R$integer.dex
│   │   │   │               │   │       R$layout.dex
│   │   │   │               │   │       R$string.dex
│   │   │   │               │   │       R$style.dex
│   │   │   │               │   │       R$styleable.dex
│   │   │   │               │   │       R.dex
│   │   │   │               │   │       
│   │   │   │               │   ├───documentfile
│   │   │   │               │   │       R.dex
│   │   │   │               │   │       
│   │   │   │               │   ├───drawerlayout
│   │   │   │               │   │       R$attr.dex
│   │   │   │               │   │       R$color.dex
│   │   │   │               │   │       R$dimen.dex
│   │   │   │               │   │       R$drawable.dex
│   │   │   │               │   │       R$id.dex
│   │   │   │               │   │       R$integer.dex
│   │   │   │               │   │       R$layout.dex
│   │   │   │               │   │       R$string.dex
│   │   │   │               │   │       R$style.dex
│   │   │   │               │   │       R$styleable.dex
│   │   │   │               │   │       R.dex
│   │   │   │               │   │       
│   │   │   │               │   ├───exifinterface
│   │   │   │               │   │       R.dex
│   │   │   │               │   │       
│   │   │   │               │   ├───fragment
│   │   │   │               │   │       R$attr.dex
│   │   │   │               │   │       R$color.dex
│   │   │   │               │   │       R$dimen.dex
│   │   │   │               │   │       R$drawable.dex
│   │   │   │               │   │       R$id.dex
│   │   │   │               │   │       R$integer.dex
│   │   │   │               │   │       R$layout.dex
│   │   │   │               │   │       R$string.dex
│   │   │   │               │   │       R$style.dex
│   │   │   │               │   │       R$styleable.dex
│   │   │   │               │   │       R.dex
│   │   │   │               │   │       
│   │   │   │               │   ├───interpolator
│   │   │   │               │   │       R.dex
│   │   │   │               │   │       
│   │   │   │               │   ├───legacy
│   │   │   │               │   │   ├───coreui
│   │   │   │               │   │   │       R$attr.dex
│   │   │   │               │   │   │       R$color.dex
│   │   │   │               │   │   │       R$dimen.dex
│   │   │   │               │   │   │       R$drawable.dex
│   │   │   │               │   │   │       R$id.dex
│   │   │   │               │   │   │       R$integer.dex
│   │   │   │               │   │   │       R$layout.dex
│   │   │   │               │   │   │       R$string.dex
│   │   │   │               │   │   │       R$style.dex
│   │   │   │               │   │   │       R$styleable.dex
│   │   │   │               │   │   │       R.dex
│   │   │   │               │   │   │       
│   │   │   │               │   │   └───coreutils
│   │   │   │               │   │           R$attr.dex
│   │   │   │               │   │           R$color.dex
│   │   │   │               │   │           R$dimen.dex
│   │   │   │               │   │           R$drawable.dex
│   │   │   │               │   │           R$id.dex
│   │   │   │               │   │           R$integer.dex
│   │   │   │               │   │           R$layout.dex
│   │   │   │               │   │           R$string.dex
│   │   │   │               │   │           R$style.dex
│   │   │   │               │   │           R$styleable.dex
│   │   │   │               │   │           R.dex
│   │   │   │               │   │           
│   │   │   │               │   ├───lifecycle
│   │   │   │               │   │   │   R.dex
│   │   │   │               │   │   │   
│   │   │   │               │   │   ├───livedata
│   │   │   │               │   │   │   │   R.dex
│   │   │   │               │   │   │   │   
│   │   │   │               │   │   │   └───core
│   │   │   │               │   │   │           R.dex
│   │   │   │               │   │   │           
│   │   │   │               │   │   └───viewmodel
│   │   │   │               │   │           R.dex
│   │   │   │               │   │           
│   │   │   │               │   ├───loader
│   │   │   │               │   │       R$attr.dex
│   │   │   │               │   │       R$color.dex
│   │   │   │               │   │       R$dimen.dex
│   │   │   │               │   │       R$drawable.dex
│   │   │   │               │   │       R$id.dex
│   │   │   │               │   │       R$integer.dex
│   │   │   │               │   │       R$layout.dex
│   │   │   │               │   │       R$string.dex
│   │   │   │               │   │       R$style.dex
│   │   │   │               │   │       R$styleable.dex
│   │   │   │               │   │       R.dex
│   │   │   │               │   │       
│   │   │   │               │   ├───localbroadcastmanager
│   │   │   │               │   │       R.dex
│   │   │   │               │   │       
│   │   │   │               │   ├───print
│   │   │   │               │   │       R.dex
│   │   │   │               │   │       
│   │   │   │               │   ├───recyclerview
│   │   │   │               │   │       R$attr.dex
│   │   │   │               │   │       R$color.dex
│   │   │   │               │   │       R$dimen.dex
│   │   │   │               │   │       R$drawable.dex
│   │   │   │               │   │       R$id.dex
│   │   │   │               │   │       R$integer.dex
│   │   │   │               │   │       R$layout.dex
│   │   │   │               │   │       R$string.dex
│   │   │   │               │   │       R$style.dex
│   │   │   │               │   │       R$styleable.dex
│   │   │   │               │   │       R.dex
│   │   │   │               │   │       
│   │   │   │               │   ├───savedstate
│   │   │   │               │   │       R.dex
│   │   │   │               │   │       
│   │   │   │               │   ├───slidingpanelayout
│   │   │   │               │   │       R$attr.dex
│   │   │   │               │   │       R$color.dex
│   │   │   │               │   │       R$dimen.dex
│   │   │   │               │   │       R$drawable.dex
│   │   │   │               │   │       R$id.dex
│   │   │   │               │   │       R$integer.dex
│   │   │   │               │   │       R$layout.dex
│   │   │   │               │   │       R$string.dex
│   │   │   │               │   │       R$style.dex
│   │   │   │               │   │       R$styleable.dex
│   │   │   │               │   │       R.dex
│   │   │   │               │   │       
│   │   │   │               │   ├───swiperefreshlayout
│   │   │   │               │   │       R$attr.dex
│   │   │   │               │   │       R$color.dex
│   │   │   │               │   │       R$dimen.dex
│   │   │   │               │   │       R$drawable.dex
│   │   │   │               │   │       R$id.dex
│   │   │   │               │   │       R$integer.dex
│   │   │   │               │   │       R$layout.dex
│   │   │   │               │   │       R$string.dex
│   │   │   │               │   │       R$style.dex
│   │   │   │               │   │       R$styleable.dex
│   │   │   │               │   │       R.dex
│   │   │   │               │   │       
│   │   │   │               │   ├───transition
│   │   │   │               │   │       R$attr.dex
│   │   │   │               │   │       R$color.dex
│   │   │   │               │   │       R$dimen.dex
│   │   │   │               │   │       R$drawable.dex
│   │   │   │               │   │       R$id.dex
│   │   │   │               │   │       R$integer.dex
│   │   │   │               │   │       R$layout.dex
│   │   │   │               │   │       R$string.dex
│   │   │   │               │   │       R$style.dex
│   │   │   │               │   │       R$styleable.dex
│   │   │   │               │   │       R.dex
│   │   │   │               │   │       
│   │   │   │               │   ├───vectordrawable
│   │   │   │               │   │   │   R$attr.dex
│   │   │   │               │   │   │   R$color.dex
│   │   │   │               │   │   │   R$dimen.dex
│   │   │   │               │   │   │   R$drawable.dex
│   │   │   │               │   │   │   R$id.dex
│   │   │   │               │   │   │   R$integer.dex
│   │   │   │               │   │   │   R$layout.dex
│   │   │   │               │   │   │   R$string.dex
│   │   │   │               │   │   │   R$style.dex
│   │   │   │               │   │   │   R$styleable.dex
│   │   │   │               │   │   │   R.dex
│   │   │   │               │   │   │   
│   │   │   │               │   │   └───animated
│   │   │   │               │   │           R$attr.dex
│   │   │   │               │   │           R$color.dex
│   │   │   │               │   │           R$dimen.dex
│   │   │   │               │   │           R$drawable.dex
│   │   │   │               │   │           R$id.dex
│   │   │   │               │   │           R$integer.dex
│   │   │   │               │   │           R$layout.dex
│   │   │   │               │   │           R$string.dex
│   │   │   │               │   │           R$style.dex
│   │   │   │               │   │           R$styleable.dex
│   │   │   │               │   │           R.dex
│   │   │   │               │   │           
│   │   │   │               │   ├───versionedparcelable
│   │   │   │               │   │       R.dex
│   │   │   │               │   │       
│   │   │   │               │   └───viewpager
│   │   │   │               │           R$attr.dex
│   │   │   │               │           R$color.dex
│   │   │   │               │           R$dimen.dex
│   │   │   │               │           R$drawable.dex
│   │   │   │               │           R$id.dex
│   │   │   │               │           R$integer.dex
│   │   │   │               │           R$layout.dex
│   │   │   │               │           R$string.dex
│   │   │   │               │           R$style.dex
│   │   │   │               │           R$styleable.dex
│   │   │   │               │           R.dex
│   │   │   │               │           
│   │   │   │               ├───butterknife
│   │   │   │               │   │   R$attr.dex
│   │   │   │               │   │   R$color.dex
│   │   │   │               │   │   R$dimen.dex
│   │   │   │               │   │   R$drawable.dex
│   │   │   │               │   │   R$id.dex
│   │   │   │               │   │   R$integer.dex
│   │   │   │               │   │   R$layout.dex
│   │   │   │               │   │   R$string.dex
│   │   │   │               │   │   R$style.dex
│   │   │   │               │   │   R$styleable.dex
│   │   │   │               │   │   R.dex
│   │   │   │               │   │   
│   │   │   │               │   └───runtime
│   │   │   │               │           R$attr.dex
│   │   │   │               │           R$color.dex
│   │   │   │               │           R$dimen.dex
│   │   │   │               │           R$drawable.dex
│   │   │   │               │           R$id.dex
│   │   │   │               │           R$integer.dex
│   │   │   │               │           R$layout.dex
│   │   │   │               │           R$string.dex
│   │   │   │               │           R$style.dex
│   │   │   │               │           R$styleable.dex
│   │   │   │               │           R.dex
│   │   │   │               │           
│   │   │   │               ├───com
│   │   │   │               │   ├───brian
│   │   │   │               │   │   └───f0d1e
│   │   │   │               │   │       │   BuildConfig.dex
│   │   │   │               │   │       │   MainActivity$1.dex
│   │   │   │               │   │       │   MainActivity.dex
│   │   │   │               │   │       │   R$anim.dex
│   │   │   │               │   │       │   R$animator.dex
│   │   │   │               │   │       │   R$attr.dex
│   │   │   │               │   │       │   R$bool.dex
│   │   │   │               │   │       │   R$color.dex
│   │   │   │               │   │       │   R$dimen.dex
│   │   │   │               │   │       │   R$drawable.dex
│   │   │   │               │   │       │   R$id.dex
│   │   │   │               │   │       │   R$integer.dex
│   │   │   │               │   │       │   R$interpolator.dex
│   │   │   │               │   │       │   R$layout.dex
│   │   │   │               │   │       │   R$mipmap.dex
│   │   │   │               │   │       │   R$string.dex
│   │   │   │               │   │       │   R$style.dex
│   │   │   │               │   │       │   R$styleable.dex
│   │   │   │               │   │       │   R.dex
│   │   │   │               │   │       │   RecipeDetailsActivity$1.dex
│   │   │   │               │   │       │   RecipeDetailsActivity$2.dex
│   │   │   │               │   │       │   RecipeDetailsActivity$3.dex
│   │   │   │               │   │       │   RecipeDetailsActivity.dex
│   │   │   │               │   │       │   
│   │   │   │               │   │       ├───Adapter
│   │   │   │               │   │       │       InstructionAdapter$InstructionViewHolder.dex
│   │   │   │               │   │       │       InstructionAdapter.dex
│   │   │   │               │   │       │       MyAdapter$1.dex
│   │   │   │               │   │       │       MyAdapter$RecipeViewHolder.dex
│   │   │   │               │   │       │       MyAdapter.dex
│   │   │   │               │   │       │       
│   │   │   │               │   │       ├───Model
│   │   │   │               │   │       │       InstructionResponse.dex
│   │   │   │               │   │       │       Recipe.dex
│   │   │   │               │   │       │       RecipiesResponse.dex
│   │   │   │               │   │       │       Step.dex
│   │   │   │               │   │       │       
│   │   │   │               │   │       └───Retrofit
│   │   │   │               │   │               ApiClient.dex
│   │   │   │               │   │               ApiInterface.dex
│   │   │   │               │   │               
│   │   │   │               │   ├───google
│   │   │   │               │   │   └───android
│   │   │   │               │   │       └───material
│   │   │   │               │   │               R$anim.dex
│   │   │   │               │   │               R$animator.dex
│   │   │   │               │   │               R$attr.dex
│   │   │   │               │   │               R$bool.dex
│   │   │   │               │   │               R$color.dex
│   │   │   │               │   │               R$dimen.dex
│   │   │   │               │   │               R$drawable.dex
│   │   │   │               │   │               R$id.dex
│   │   │   │               │   │               R$integer.dex
│   │   │   │               │   │               R$interpolator.dex
│   │   │   │               │   │               R$layout.dex
│   │   │   │               │   │               R$string.dex
│   │   │   │               │   │               R$style.dex
│   │   │   │               │   │               R$styleable.dex
│   │   │   │               │   │               R.dex
│   │   │   │               │   │               
│   │   │   │               │   └───squareup
│   │   │   │               │       └───picasso
│   │   │   │               │               R.dex
│   │   │   │               │               
│   │   │   │               └───net
│   │   │   │                   └───yslibrary
│   │   │   │                       └───android
│   │   │   │                           └───keyboardvisibilityevent
│   │   │   │                                   R.dex
│   │   │   │                                   
│   │   │   └───validate_signing_config
│   │   │       └───debug
│   │   │           └───out
│   │   ├───outputs
│   │   │   ├───apk
│   │   │   │   └───debug
│   │   │   │           app-debug.apk
│   │   │   │           output.json
│   │   │   │           
│   │   │   └───logs
│   │   │           manifest-merger-debug-report.txt
│   │   │           
│   │   └───tmp
│   │       └───compileDebugJavaWithJavac
│   └───src
│       ├───androidTest
│       │   └───java
│       │       └───com
│       │           └───brian
│       │               └───f0d1e
│       │                       ExampleInstrumentedTest.java
│       │                       
│       ├───main
│       │   │   AndroidManifest.xml
│       │   │   ic_launcher-playstore.png
│       │   │   
│       │   ├───java
│       │   │   └───com
│       │   │       └───brian
│       │   │           └───f0d1e
│       │   │               │   MainActivity.java
│       │   │               │   RecipeDetailsActivity.java
│       │   │               │   
│       │   │               ├───Adapter
│       │   │               │       InstructionAdapter.java
│       │   │               │       MyAdapter.java
│       │   │               │       
│       │   │               ├───Model
│       │   │               │       InstructionResponse.java
│       │   │               │       Recipe.java
│       │   │               │       RecipiesResponse.java
│       │   │               │       Step.java
│       │   │               │       
│       │   │               └───Retrofit
│       │   │                       ApiClient.java
│       │   │                       ApiInterface.java
│       │   │                       
│       │   └───res
│       │       ├───drawable
│       │       │       header.png
│       │       │       ic_launcher_background.xml
│       │       │       searchview_rounded.xml
│       │       │       
│       │       ├───drawable-v24
│       │       │       ic_launcher_foreground.xml
│       │       │       
│       │       ├───layout
│       │       │       activity_main.xml
│       │       │       activity_recipe_details.xml
│       │       │       content_recipe_details.xml
│       │       │       recycler_row.xml
│       │       │       steplist_row.xml
│       │       │       
│       │       ├───mipmap-anydpi-v26
│       │       │       ic_launcher.xml
│       │       │       ic_launcher_round.xml
│       │       │       
│       │       ├───mipmap-hdpi
│       │       │       ic_launcher.png
│       │       │       ic_launcher_foreground.png
│       │       │       ic_launcher_round.png
│       │       │       
│       │       ├───mipmap-mdpi
│       │       │       ic_launcher.png
│       │       │       ic_launcher_foreground.png
│       │       │       ic_launcher_round.png
│       │       │       
│       │       ├───mipmap-xhdpi
│       │       │       ic_launcher.png
│       │       │       ic_launcher_foreground.png
│       │       │       ic_launcher_round.png
│       │       │       
│       │       ├───mipmap-xxhdpi
│       │       │       ic_launcher.png
│       │       │       ic_launcher_foreground.png
│       │       │       ic_launcher_round.png
│       │       │       
│       │       ├───mipmap-xxxhdpi
│       │       │       ic_launcher.png
│       │       │       ic_launcher_foreground.png
│       │       │       ic_launcher_round.png
│       │       │       
│       │       └───values
│       │               colors.xml
│       │               dimens.xml
│       │               ic_launcher_background.xml
│       │               strings.xml
│       │               styles.xml
│       │               
│       └───test
│           └───java
│               └───com
│                   └───brian
│                       └───f0d1e
│                               ExampleUnitTest.java
│                               
└───gradle
    └───wrapper
            gradle-wrapper.jar
            gradle-wrapper.properties
            




