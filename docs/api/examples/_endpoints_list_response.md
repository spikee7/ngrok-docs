<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2024-12-05T15:38:21Z",
			"hostport": "9c1c95d0f7f0.ngrok.paid:443",
			"id": "ep_2pnsJOkn89ne9i1K3JryKhFkxAn",
			"name": "command_line",
			"principal": {
				"id": "usr_2pnsH5wt36MtNP5f2EkeRozi2QM",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://9c1c95d0f7f0.ngrok.paid",
			"tunnel": {
				"id": "tn_2pnsJOkn89ne9i1K3JryKhFkxAn",
				"uri": "https://api.ngrok.com/tunnels/tn_2pnsJOkn89ne9i1K3JryKhFkxAn"
			},
			"tunnel_session": {
				"id": "ts_2pnsJPFkzZ7A4GciliUWB9sSKqa",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2pnsJPFkzZ7A4GciliUWB9sSKqa"
			},
			"type": "ephemeral",
			"updated_at": "2024-12-05T15:38:21Z",
			"upstream_url": "http://localhost:80",
			"url": "https://9c1c95d0f7f0.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2024-12-05T15:38:19Z",
			"domain": {
				"id": "rd_2pnsJ2DZqULPl2nIuJkEgGE5d31",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2pnsJ2DZqULPl2nIuJkEgGE5d31"
			},
			"edge": {
				"id": "edgtls_2pnsJ8uAxL3vLjaqc7ZspDjdb8T",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2pnsJ8uAxL3vLjaqc7ZspDjdb8T"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2pnsJ8ejQdCjDmk7a6o7TeCZ4lb",
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2024-12-05T15:38:19Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
