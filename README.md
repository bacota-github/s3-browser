This is a simple javascript function to interactively browse a folder in s3.  An example use is [here](http://14strings.com/browse-tabs.html)

It requires vue.js and and the aws-sdk.  It's called with the name fo an s3 bucket and the name of the folder, as in 
```
    <script type="text/javascript">
      browse('14strings.com', 'tabs', 'folder-id')
    </script>
```

