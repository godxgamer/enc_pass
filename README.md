# Encrypted Password API

This API endpoint allows you to generate an encrypted password using the specified parameters.

### Endpoint
- http://128.140.99.16:5634/api/pass_enc/


### Parameters

- `p`: The password to be encrypted. (Required)
- `v`: The version of encryption. (examle : 11,10,9,8,7,6)
- `m`: The method of encryption. (example : fbapp,fbweb,igapp,igweb)

## Example Usage

### Request

```http
GET /api/pass_enc/?p=Gamer@123&v=10&m=fbapp HTTP/1.1
Host: 128.140.99.16:5634
```
### How to Use
-You can make a GET request to the provided endpoint with the required parameters (p , v , m) to obtain the encrypted password.

### Contact
- For bulk account creation or any queries, contact the developer on Telegram: [@god_x_gamer](https://telegram.me/god_x_gamer).
- Join [@gxbytes](https://telegram.me/gxbytes) for latest updates 
- This API can be used in any language (Python, PHP, JavaScript, Go, Java) to create your own account registration automation.


### Disclaimer
- Use this script responsibly and in accordance with Instagram's terms of service. The developer is not responsible for any misuse or consequences.

