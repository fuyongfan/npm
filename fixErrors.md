## npm install 报错 
1. unable to verify the first certificate
   - 原因：npm 走的是https协议， 需要验证数字证书
   - 解决方法：取消ssl验证：npm config set strict-ssl false