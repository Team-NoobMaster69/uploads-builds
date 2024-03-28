### Build the service

Upload your builds with the following methods:

```makefile
wget https://raw.githubusercontent.com/Fornax96/pdup/master/pdup && chmod +x pdup && ./pdup test.txt
```

OBS: PixelDrain has a limit of 5GB per day to use, but it is very fast and offers other services for those who are logged in.

```makefile
https://rclone.org/drive/ rclone copy caminho-do-zip host:pasta
```

OBS: Set up google drive on your server first before using rclone or read the wiki.

```makefile
curl bashupload.com -T your_file.txt
```

OBS: Bashupload is for small files and not builds, so don't expect it to host a large file for more than 10 minutes.

```makefile
curl -sL https://git.io/file-transfer | sh && ./transfer test.txt
```

OBS: The file transfer follows the same path as bashupload, it does not leave the large file hosted for a long time.

```makefile
wget https://raw.githubusercontent.com/Sushrut1101/GoFile-Upload/master/upload.sh && chmod +x upload.sh && ./upload.sh <arquivo>
```

OBS: GoFile is an innovative method that few use, but which also proves to be very useful.

That's all, perhaps the list will be updated in the near future. xD
