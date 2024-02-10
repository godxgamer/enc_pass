# Encrypted Password API

This API endpoint allows you to generate an encrypted password using the specified parameters.

### Endpoint
- http://128.140.99.16:5634/api/pass_enc/


### Parameters

- `p`: The password to be encrypted. (Required)
- `v`: The version of encryption. (Optional, default is 10)
- `m`: The method of encryption. (Optional, default is fbapp)

## Example Usage

### Request

```http
GET /api/pass_enc/?p=Gamer@123&v=10&m=fbapp HTTP/1.1
Host: 128.140.99.16:5634
```

