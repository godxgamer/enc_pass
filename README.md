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
#### Example Response
```
#PWD_FB4A:10:1707593014:AX9QABaI/tzcXEmmWvCq1f35da5NqeVC/Vf8DsOv1CSdQJ9RxwOcrn/XqSYYZ/LAi8sia6Xr1nnS8nKg6YQtn98eOnr+WWzV459UfuMUA5l5W0hN/9TjZujmnvQMgUfjVIzPgEh18RpAD27HuQ==

#PWD_BROWSER:10:1707593045:AX9QALucTC/BdUWtQaPSX4+hX5l8CGONp1g9yoXHOUr67gNMFg3xvDc/XPnRFXI31G5hkNCT34fgXxMgIJSfYaDr3vRKqQ+ZAYvpT6PRreNe999cOo0ofluRDzqWtzuZCjnUaHEpCJEDgYw8OA==

#PWD_INSTAGRAM_BROWSER:10:1707593073:AX9QAFVABEodYeWzEffc6PlB/hVoLkHa9YU+DF/ijB1J88cyTJabOF+d6KmHislofO5hBDajFdmKMQCYWlj1qKpdUwisJ6aN1AquNiY8t/hOmXdbTvq/K3lP8v4T+WnlArBxUEV2ywt1rD1BzA==

#PWD_INSTAGRAM:10:1707593103:AX9QAIHYJpHZwCg3s2jgkJqvzC9tO3QCvhZZfIO76buh4QYD9gJ8w6VVQ/Q/s8iEfuo2G/x4sAy2KkObhhuTdNCL/gZspTrXp8jVQFocYHD8y+/vUrx13Ec8zwnSQzH6e7aR3CaK8r6Ibe2HaA==
```
### How to Use
-You can make a GET request to the provided endpoint with the required parameters (p , v , m) to obtain the encrypted password.

### Contact
- For bulk account creation or any queries, contact the developer on Telegram: [@god_x_gamer](https://telegram.me/god_x_gamer).
- Join [@gxbytes](https://telegram.me/gxbytes) for latest updates 
- This API can be used in any language (Python, PHP, JavaScript, Go, Java) to create your own account registration automation.


### Disclaimer
- Use this script responsibly and in accordance with Instagram's terms of service. The developer is not responsible for any misuse or consequences.

