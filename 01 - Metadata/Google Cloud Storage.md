<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.google.gcs.storage" id="_Het-UP8GEemard-ILiH4Eg" name="storage" md:ref="platform:/plugin/com.indy.environment/technology/google.cloud.platform/storage/google.cloud.tech#UUID_TECH_GOOGLE_CLOUD_STORAGE?fileId=UUID_TECH_GOOGLE_CLOUD_STORAGE$type=tech$name=Google%20Cloud%20Storage?">
  <attribute defType="com.stambia.google.gcs.storage.credential" id="_I4jfFP8GEemard-ILiH4Eg" ref="Google%20Cloud%20Platform.md#_3vu88_8FEemard-ILiH4Eg?fileId=_zpqfcP8FEemard-ILiH4Eg$type=md$name=credentials?"/>
  <attribute defType="com.stambia.google.gcs.storage.module" id="_bNsOwDFYEeqEZPS85FB0HA" value="&lt;GOOGLE_PLATFORM_MODULE>"/>
  <node defType="com.stambia.google.gcs.bucket" id="_I-S6s_8GEemard-ILiH4Eg" name="demo_bucket_stb_a_managment">
    <attribute defType="com.stambia.google.gcs.bucket.bucketName" id="_LXEI4P8GEemard-ILiH4Eg" value="demo_bucket_stb_a_managment"/>
  </node>
  <node defType="com.stambia.google.gcs.bucket" id="_b-ClYP8KEemard-ILiH4Eg" name="demo_bucket_stb_c_blob_operations">
    <attribute defType="com.stambia.google.gcs.bucket.bucketName" id="_b-ClYf8KEemard-ILiH4Eg" value="demo_bucket_stb_c_blob_operations"/>
    <node defType="com.stambia.google.gcs.directory" id="_j6ytoP8XEemard-ILiH4Eg" name="folder_a">
      <attribute defType="com.stambia.google.gcs.directory.path" id="_l9K1EP8XEemard-ILiH4Eg" value="folder_a"/>
    </node>
    <node defType="com.stambia.google.gcs.directory" id="_mF7IcP8XEemard-ILiH4Eg" name="folder_b">
      <attribute defType="com.stambia.google.gcs.directory.path" id="_mkKjoP8XEemard-ILiH4Eg" value="folder_b"/>
    </node>
    <node defType="com.stambia.google.gcs.directory" id="_mYLwkv8sEemard-ILiH4Eg" name="folder_c">
      <attribute defType="com.stambia.google.gcs.directory.path" id="_mYLwk_8sEemard-ILiH4Eg" value="folder_c"/>
    </node>
    <node defType="com.stambia.google.gcs.directory" id="_nAoQov8sEemard-ILiH4Eg" name="folder_d">
      <attribute defType="com.stambia.google.gcs.directory.path" id="_nAoQo_8sEemard-ILiH4Eg" value="folder_d"/>
    </node>
    <node defType="com.stambia.google.gcs.directory" id="_wUcHkACbEeqN559Tk2m5oA" name="folder_e">
      <attribute defType="com.stambia.google.gcs.directory.path" id="_VLVxUACxEeqN559Tk2m5oA" value="folder_e"/>
      <node defType="com.stambia.google.gcs.directory" id="_wjFnkACbEeqN559Tk2m5oA" name="subfolder">
        <attribute defType="com.stambia.google.gcs.directory.path" id="_yKuTwACbEeqN559Tk2m5oA" value="subfolder"/>
      </node>
    </node>
  </node>
  <node defType="com.stambia.google.gcs.bucket" id="_SPQWdf8LEemard-ILiH4Eg" name="demo_bucket_stb_b_managment">
    <attribute defType="com.stambia.google.gcs.bucket.bucketName" id="_SPQWdv8LEemard-ILiH4Eg" value="demo_bucket_stb_b_managment"/>
  </node>
  <node defType="com.stambia.google.gcs.bucket" id="_A02ISv-_Eemyt-s1-ys73g" name="demo_bucket_stb_d_labels_and_life_cycle">
    <attribute defType="com.stambia.google.gcs.bucket.bucketName" id="_A02IS_-_Eemyt-s1-ys73g" value="demo_bucket_stb_d_labels_and_life_cycle"/>
    <attribute defType="com.stambia.google.gcs.bucket.locationType" id="_ME51UP_BEemyt-s1-ys73g" value="region"/>
    <attribute defType="com.stambia.google.gcs.bucket.location" id="_NBPhwP_BEemyt-s1-ys73g" value="europe-west1"/>
    <node defType="com.stambia.google.gcs.label" id="_FyaOcf-_Eemyt-s1-ys73g">
      <attribute defType="com.stambia.google.gcs.label.key" id="_G-SywP-_Eemyt-s1-ys73g" value="label_a"/>
      <attribute defType="com.stambia.google.gcs.label.value" id="_Hj8dgP-_Eemyt-s1-ys73g" value="value_a"/>
    </node>
    <node defType="com.stambia.google.gcs.label" id="_Hue5kf-_Eemyt-s1-ys73g">
      <attribute defType="com.stambia.google.gcs.label.key" id="_IaaygP-_Eemyt-s1-ys73g" value="label_b"/>
      <attribute defType="com.stambia.google.gcs.label.value" id="_I3MOEP-_Eemyt-s1-ys73g" value="value_b"/>
    </node>
    <node defType="com.stambia.google.gcs.lifecycleRule" id="_MxCNgP-_Eemyt-s1-ys73g" name="Delete_very_old_unLive_Blobs">
      <attribute defType="com.stambia.google.gcs.lifecycleRule.age" id="_MxCNgf-_Eemyt-s1-ys73g" value="100"/>
      <attribute defType="com.stambia.google.gcs.lifecycleRule.action" id="_MxCNgv-_Eemyt-s1-ys73g" value="Delete"/>
      <attribute defType="com.stambia.google.gcs.lifecycleRule.isLive" id="_MxCNg_-_Eemyt-s1-ys73g" value="false"/>
      <attribute defType="com.stambia.google.gcs.lifecycleRule.newerVersions" id="_MxCNhP-_Eemyt-s1-ys73g" value="3"/>
    </node>
    <node defType="com.stambia.google.gcs.lifecycleRule" id="_MxCNhf-_Eemyt-s1-ys73g" name="Set_old_blobs_to_ColdLine">
      <attribute defType="com.stambia.google.gcs.lifecycleRule.storageClassCondition" id="_MxCNhv-_Eemyt-s1-ys73g">
        <values>REGIONAL</values>
        <values>NEARLINE</values>
        <values>STANDARD</values>
      </attribute>
      <attribute defType="com.stambia.google.gcs.lifecycleRule.action" id="_MxCNh_-_Eemyt-s1-ys73g" value="Set Storage Class"/>
      <attribute defType="com.stambia.google.gcs.lifecycleRule.storageClass" id="_MxCNiP-_Eemyt-s1-ys73g" value="COLDLINE"/>
      <attribute defType="com.stambia.google.gcs.lifecycleRule.age" id="_MxCNif-_Eemyt-s1-ys73g" value="30"/>
    </node>
  </node>
</md:node>