# This Fork #

Added methods to support https://s3.amazonaws.com/{bucketName} in FormBuilder. It didn't work for me with the https://{bucketname}.s3.amazonaws.com/ url. 

Methods are as follows:
- BeginAsyncUploadFormAlt as apposed to BeginAsyncUploadForm, HtmlHelper extension this version will output https://s3.amazonaws.com/{bucketName}


# Introduction #

Nupload makes it easy to support signed object downloads and asynchronous CORS-enabled form uploads to and from Amazon S3 and Google Cloud Storage

# How to Use #

Check out the sample application or read [the blog post about using Nupload](http://blog.appharbor.com/2013/01/10/asynchronous-browser-uploads-to-s3-and-gcs-using-cors-aspnet-mvc)
