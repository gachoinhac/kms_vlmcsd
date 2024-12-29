# kms_vlmcsd
Deploy kms_service/vlmcsd_service on Docker container (Re-write based on https://github.com/Wind4)

```bash
git clone https://github.com/gachoinhac/kms_vlmcsd.git vlmcsd
cd vlmcsd

# Use docker-compose service
docker-compose up -d

# or docker build image
docker build -t vlmcsd .
docker run -idt -p 1688:1688 vlmcsd
```
