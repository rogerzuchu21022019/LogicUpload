# LogicUpload

# Step1 : Check 

```
if (mUploadTask != null && mUploadTask.isInProgress()) {
    Toast.makeText(context:MainActivity.this, "Upload in progress",Toast.LENGTH_SHORT).show()
} else {
    uploadFile();
}
```
