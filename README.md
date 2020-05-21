# upload_file
upload  file with go

api
```
curl --location --request POST 'localhost:3000/upload' --form 'file=@ksniff.zip'
wget http://localhost:3000/download?filename=KB_vol1_08.jpg
```
env
```
GOOS=linux;GOARCH=amd64
```
