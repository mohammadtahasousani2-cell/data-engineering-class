\# Activity 3: API Contract Design



\## Endpoint

`GET /api/v1/activities`



\## Purpose

Retrieve a list of activities.



\## Request

\- Method: `GET`

\- Path: `/api/v1/activities`

\- Query parameters: None



\## Successful Response

Status: `200 OK`

```json

{

&#x20; "data": \[

{

"id": 1,

"name": "Sample Activity",

"description": "Example activity"

}

&#x20; ]

}



