<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-07-16T10:08:19Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_2zx6hKelGh1bQghGmHmd9MslYjO",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2zx6hKelGh1bQghGmHmd9MslYjO"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2zx6hwSofFoadvd7ZfKOCS0XFWx",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-07-16T10:08:19Z",
      "uri": "https://api.ngrok.com/endpoints/ep_2zx6hwSofFoadvd7ZfKOCS0XFWx",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-07-16T10:08:17Z",
      "hostport": "b4479ad1b594.ngrok.paid:443",
      "id": "ep_2zx6hfWLyyiIngFM0Rop3uP4l0n",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_2zx6b7DDxLT1fziLiyXOo0qp7tE",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://b4479ad1b594.ngrok.paid",
      "tunnel": {
        "id": "tn_2zx6hfWLyyiIngFM0Rop3uP4l0n",
        "uri": "https://api.ngrok.com/tunnels/tn_2zx6hfWLyyiIngFM0Rop3uP4l0n"
      },
      "tunnel_session": {
        "id": "ts_2zx6he96dXPNVEl2K9NOc4nf3gp",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_2zx6he96dXPNVEl2K9NOc4nf3gp"
      },
      "type": "ephemeral",
      "updated_at": "2025-07-16T10:08:17Z",
      "upstream_url": "http://localhost:80",
      "url": "https://b4479ad1b594.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-07-16T10:08:15Z",
      "domain": {
        "id": "rd_2zx6hKelGh1bQghGmHmd9MslYjO",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2zx6hKelGh1bQghGmHmd9MslYjO"
      },
      "edge": {
        "id": "edgtls_2zx6hMxPs0fHViWUmhM0j2DDuwF",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_2zx6hMxPs0fHViWUmhM0j2DDuwF"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2zx6hGtaa9dP3FNeSOZnZA6IXFd",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-07-16T10:08:15Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```
