<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-05-19T10:07:19Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_2xJHPs27EXf390U1HntAOuzETDH",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2xJHPs27EXf390U1HntAOuzETDH"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2xJHQTWc0QMcWdOmjFegepPqshT",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-05-19T10:07:19Z",
      "uri": "https://api.ngrok.com/endpoints/ep_2xJHQTWc0QMcWdOmjFegepPqshT",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-05-19T10:07:17Z",
      "hostport": "6507b2b884dd.ngrok.paid:443",
      "id": "ep_2xJHQBr9129FRqUNxF6p2kxgCxD",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_2xJHNm2KooccQwQHqtO0l8G13Wh",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://6507b2b884dd.ngrok.paid",
      "tunnel": {
        "id": "tn_2xJHQBr9129FRqUNxF6p2kxgCxD",
        "uri": "https://api.ngrok.com/tunnels/tn_2xJHQBr9129FRqUNxF6p2kxgCxD"
      },
      "tunnel_session": {
        "id": "ts_2xJHQBHm8okRUTH24iQvHmKp916",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_2xJHQBHm8okRUTH24iQvHmKp916"
      },
      "type": "ephemeral",
      "updated_at": "2025-05-19T10:07:17Z",
      "upstream_url": "http://localhost:80",
      "url": "https://6507b2b884dd.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-05-19T10:07:14Z",
      "domain": {
        "id": "rd_2xJHPs27EXf390U1HntAOuzETDH",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2xJHPs27EXf390U1HntAOuzETDH"
      },
      "edge": {
        "id": "edgtls_2xJHPnpxHD0EQzqgVRhHgCMqOVf",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_2xJHPnpxHD0EQzqgVRhHgCMqOVf"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2xJHPrjtrANHCxgF3v4IByCQNzV",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-05-19T10:07:14Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```
