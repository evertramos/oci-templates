## create secret for registry

kubectl create secret docker-registry ocisecret --docker-server=sa-vinhedo-1.ocir.io --docker-username="axsowhb0isxx/john" --docker-password="+2ntS8U5Gdx7QSDkPZNE" --docker-email="onemrgreen@gmail.com"

## create secret for tls

kubectl create secret tls tls-secret --key cloudflare_certificate.key --cert cloudflare_certificate.pem