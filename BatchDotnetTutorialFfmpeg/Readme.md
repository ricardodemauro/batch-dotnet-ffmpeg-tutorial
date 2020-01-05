# Setup

### Application package Id and version

This assumes the Windows ffmpeg app package is already added to the Batch account with this Id and version. 
First download ffmpeg zipfile from https://ffmpeg.zeranoe.com/builds/win64/static/ffmpeg-3.4-win64-static.zip.
To add package to the Batch account, see https://docs.microsoft.com/azure/batch/batch-application-packages.

### Configuration

Add missing configuration using your account information

```json
{
  "BatchAccountName": "",
  "BatchAccountKey": "",
  "BatchAccountUrl": "",

  "StorageAccountName": "",
  "StorageAccountKey": "",
}
```