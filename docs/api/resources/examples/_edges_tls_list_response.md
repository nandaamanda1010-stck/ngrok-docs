<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-07-16T10:08:24Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_2zx6iZZB12aTme94i2peaYUoC9y",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2zx6iZZB12aTme94i2peaYUoC9y"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_2zx6hLmzesVvFNAMIJ4017cWA5S",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_2zx6hLmzesVvFNAMIJ4017cWA5S"
        },
        "enabled": true
      },
      "created_at": "2025-07-16T10:08:14Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_2zx6hMxPs0fHViWUmhM0j2DDuwF",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2zx6hMxPs0fHViWUmhM0j2DDuwF"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
```
