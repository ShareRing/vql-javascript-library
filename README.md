# vql-javascript-library
Library for customers to integrate Vql feature on their website.


# how to use
```
...
<div class="sharering-query" queryId="641ac231b10fe1005c09bb17" mode="dynamic" key="1234" qrcodeOwner="shareledger1fja6aazgvw6zfrh59xjc6w0jdpfhdkharz72lr" onscan="onScan">
  <div class="qrcode-content">
      <div id="qrcode"></div>
  </div>
</div>
...
<script src="https://../sharering.query.lib.prod.min.js"></script>    
<script>
  function onScan(data){
    //do something with result
  }  
</script>
```
