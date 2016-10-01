[![](https://images.microbadger.com/badges/version/nikkor/pure-ftpd-with-user.svg)](https://microbadger.com/images/nikkor/pure-ftpd-with-user "Get your own version badge on microbadger.com")

To run the container:

```bash
docker run -d --name ftpd_server -p 21:21 -p 30000-30009:30000-30009 -e "PUBLICHOST=localhost" nikkor/pure-ftpd-with-user
```

user: joe / 123456
