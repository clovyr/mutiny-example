# ![logo-small](https://user-images.githubusercontent.com/72885/228417202-d123f7c5-8cab-405b-97a0-cb3c2e1c6b98.svg)

Mutiny Developer Sandbox


<img width="300" alt="phone" src="https://user-images.githubusercontent.com/72885/228417211-74f74ae2-1f96-4cbd-8ce4-71c014401e0a.png">

```
cd ~/git/github.com/MutinyWallet/mutiny-web
nvm install 16
pnpm install
echo Launching web server on https://8080-$(echo $HOSTNAME | cut -f1-3 -d'-').wnext.app
pnpm run dev --host 0.0.0.0 --port 8080
```
