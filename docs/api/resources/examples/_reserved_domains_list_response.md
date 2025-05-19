<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "reserved_domains": [
    {
      "acme_challenge_cname_target": null,
      "certificate": null,
      "certificate_management_policy": {
        "authority": "letsencrypt",
        "private_key_type": "ecdsa"
      },
      "certificate_management_status": {
        "provisioning_job": {
          "error_code": null,
          "msg": "Managed certificate provisioning in progress.",
          "retries_at": null,
          "started_at": "2025-05-19T10:06:58Z"
        },
        "renews_at": null
      },
      "cname_target": "4knqktdwka2umyjjc.2cgkvyudlzhartmej.local-ngrok-cname.com",
      "created_at": "2025-05-19T10:06:58Z",
      "description": "Device 0001 Dashboard",
      "domain": "manage-0002.app.example.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_2xJHNpR2r6Y0Z9LhlCeh78n1u9k",
      "metadata": "{\"service\": \"dashboard\"}",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_2xJHNpR2r6Y0Z9LhlCeh78n1u9k"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": {
        "id": "cert_2xJHNmg9SqJXoIp0l9F281TIQit",
        "uri": "https://api.ngrok.com/tls_certificates/cert_2xJHNmg9SqJXoIp0l9F281TIQit"
      },
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": "2udamkamcl8pjmrff.2cgkvyudlzhartmej.local-ngrok-cname.com",
      "created_at": "2025-05-19T10:06:58Z",
      "domain": "myapp.mydomain.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_2xJHNoOG37jWkWb1A5rgO5xNbDZ",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_2xJHNoOG37jWkWb1A5rgO5xNbDZ"
    }
  ],
  "uri": "https://api.ngrok.com/reserved_domains"
}
```
