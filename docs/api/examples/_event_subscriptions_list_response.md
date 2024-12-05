<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"event_subscriptions": [
		{
			"created_at": "2024-12-05T15:38:25Z",
			"description": "ip policy creations",
			"destinations": [
				{
					"id": "ed_2pnsJz8Plc1gDyFaqqls7QB2Snn",
					"uri": "https://api.ngrok.com/event_destinations/ed_2pnsJz8Plc1gDyFaqqls7QB2Snn"
				}
			],
			"id": "esb_2pnsK0SRyE5tkId1HgXuJFViguN",
			"metadata": "{\"environment\": \"staging\"}",
			"sources": [
				{
					"type": "ip_policy_created.v0",
					"uri": "https://api.ngrok.com/event_subscriptions/esb_2pnsK0SRyE5tkId1HgXuJFViguN/sources/ip_policy_created.v0"
				}
			],
			"uri": "https://api.ngrok.com/event_subscriptions/esb_2pnsK0SRyE5tkId1HgXuJFViguN"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/event_subscriptions"
}
```
