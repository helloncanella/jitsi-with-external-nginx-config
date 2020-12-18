# Jitsi server

1. Install docker

```
sudo snap install docker
```

2. Configure Jitsi

Follow along the `jitsi/README.md`

3. Configure Nginx's ssl

  1. Move cert files to the folders `nginx/ssl/certs` and `nginx/ssl/private`
  3. `cd nginx; cp env.example .env`
  2. Fill `nginx/.env` with the names of the files found in the folders `ningx/ssl/certs/` and `nginx/ssl/private`

4. Deploy

On the root of the project issue:

```
sudo ./deploy.sh
```


