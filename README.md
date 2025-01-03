<div id="top"</div>
<div align="center" ><img width="30%" alt="DaFaFlare Icon" src="https://i.ibb.co.com/VJTL6Zz/favicon.png"></div>

# DaFaFlare - Enhanced DDoS Protection for GTPS

DaFaFlare is a powerful DDoS Protection System built for Growtopia Private Server using Javascript HTTPS.
It provides Auto Blacklisted IP, User-Agent Filter, Random Custom Status HTTPS Code.

## License
This project is distributed under MIT License. For detailed terms, please refer to the [LICENSE](LICENSE)

## ✅ Features
- Auto Blacklisted IP
- User-Agent Filter
- Random Custom Status HTTPS Code
- Server Monitoring (console/logs)

## ❓ How to Install
1. Clone the repository:
   
   ```
   git clone https://github.com/dafarvn/GTPS-HTTPS2.git ./
   ```
2. Install required necessary dependencies:

   ```
   npm install
   ```

3. Set up system by modifying `setting.json` with your server information and security configurations.
   
   Default configurations:
   ```
   {
      "Server": {
         "loginurl": "loginurl.com",
          "ip": "127.0.0.1", // change to your server ip
          "port": 17091,
          "maintenance": false, // true or false
          "maintenanceMessage": "Server is currently under maintenance. Please try again later!" // maintenance message
      },
      "Settings": {
          "setTimeout": 30000, // requests not completed within 30 sec will abort
          "keepAliveTimeout": 5000, // responsiveness for accept requests
          "headersTimeout": 10000
      },
      "autoBlacklist": {
          "rateLimitWindow": 30000,
          "maxRequests": 100, // max requests for user 
          "blacklistDuration": 3600 // 1 hour blacklist
      }
   }
   ```

4. Power up DaFaFlare:

   ```
   npm run https
   ```

## ❗ Information
Next features, will be updated regularly on GitHub. For further feature requests or protection, please contact Discord or Whatsapp

<a href="https://github.com/dafarvn"><img alt="Link to my GitHub" src="https://img.shields.io/github/followers/dafarvn?style=for-the-badge&color=181717&logo=github&logoColor=181717&label=@dafarvn" height="22px"></a>
<a href="https://discord.com/channels/@me/1136638093101891665"><img alt="link to my Discord" src="https://img.shields.io/static/v1?label&message=dfarvn&color=000000&style=for-the-badge&logo=discord" height="22px"/></a>
<a href="https://wa.me/+6285175265241"><img alt="Link to my Whatsapp" src="https://img.shields.io/static/v1?label&message=DaFa Rizki Revansyah&color=000000&style=for-the-badge&logo=whatsapp" height="22px"/></a>
