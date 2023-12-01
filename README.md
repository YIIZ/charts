## Usage

### Install
```sh
# expose on `80` port, response 200 for `/up`
helm install my-web --repo https://yiiz.github.io/charts web --set "image=ghcr.io/my/image:latest,host=exampe.com,env.XX_KEY=$XX_KEY"
```
