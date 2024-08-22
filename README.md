# ibf
JavaScript library for ibf.tw
# main
```js
async function main(){
    const {ibf} = require('./ibf');
    const url= new ibf();
    let req=await url.short_url("url")
    console.log(req)
}
main()
```
