# ghost-docker

```
docker run --name ghost \
-v /var/ghost-data:/var/lib/ghost/content \
-p 10090:2368 \
-e "HOST_URL=http://crackcreed.com" \
-d yuyangdocker/ghost
```
