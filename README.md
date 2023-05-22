# BoostyAPI
Figuring out Boosty's public API and writing documentation for it.

<h2><u>Note: this repository is work-in-progress.</u></h2>

Google Sheets link: https://docs.google.com/spreadsheets/d/1lxdKjmIvfWAhktv2Wvkdp2gEGr0knQWBPnGxfOUM6xA/edit?usp=sharing


## Base API Route
`https://api.boosty.to/v1`



## List of API endpoints
| Endpoint                                    | Description                                              | Parameters       | Parameter Description                                                    | Examples | Notes |
|---------------------------------------------|----------------------------------------------------------|------------------|--------------------------------------------------------------------------|----------|-------|
| /blog/**\<blog_name\>**                     |                                                          |                  |                                                                          |          |       |
| /blog/**\<blog_name\>**/subscription_level/ | Retrieve information about subscription levels of a blog |                  |                                                                          |          |       |
|                                             |                                                          | \<blog_name\>    | **String**<br>The name of the blog                                       |          |       |
|                                             |                                                          | ?show_free_level | Whether to show the free "Follower" level<br>Type: **Boolean** (`false`) |          |       |


## Contributing
If you found a Boosty API endpoint which is not listed here, feel free to create an issue!

