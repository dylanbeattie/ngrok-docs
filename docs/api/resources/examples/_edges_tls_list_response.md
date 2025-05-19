<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-05-19T10:07:24Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_2xJHR6EQstmzLjet7QTQpaWvGbm",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2xJHR6EQstmzLjet7QTQpaWvGbm"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_2xJHPm4DEDv8o4kWf9Yhh25EY6Z",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_2xJHPm4DEDv8o4kWf9Yhh25EY6Z"
        },
        "enabled": true
      },
      "created_at": "2025-05-19T10:07:14Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_2xJHPnpxHD0EQzqgVRhHgCMqOVf",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2xJHPnpxHD0EQzqgVRhHgCMqOVf"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
```
