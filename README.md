# iotb

IoT Backend

## Static Directory

Deploy index file to gs://iot-backend

```
gsutil -m rsync -r ./html gs://iot-backend/
```

Access by going to:

```
https://storage.googleapis.com/iot-backend
```
