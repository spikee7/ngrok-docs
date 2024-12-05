<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2024-12-05T15:38:30Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2pnsKX60xzgkRF3hdmNYCLazBs8",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2pnsKX60xzgkRF3hdmNYCLazBs8"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2pnsJ5CWTvziEl4xfJzCkUY3WFK",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2pnsJ5CWTvziEl4xfJzCkUY3WFK"
				},
				"enabled": true
			},
			"created_at": "2024-12-05T15:38:18Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2pnsJ8uAxL3vLjaqc7ZspDjdb8T",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2pnsJ8uAxL3vLjaqc7ZspDjdb8T"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
