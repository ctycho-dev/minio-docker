=== Docs

```
openssl req -x509 -nodes -days 730 -newkey rsa:2048 \
  -keyout /home/vmadmin/development/minIO/.minio/certs/ctycho-s3.key \
  -out /home/vmadmin/development/minIO/.minio/certs/ctycho-s3.crt
```