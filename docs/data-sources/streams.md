---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "ksql_streams Data Source - terraform-provider-ksql"
subcategory: ""
description: |-
  Use this data source to get information about KSQL Streams for use in other resources.
---

# ksql_streams (Data Source)

Use this data source to get information about KSQL Streams for use in other resources.



<!-- schema generated by tfplugindocs -->
## Schema

### Optional

- `id` (String) The ID of this resource.
- `tag` (String) The tag to filter the streams.
- `topic` (String) The topic to filter the streams.

### Read-Only

- `streams` (List of Object) The streams found. (see [below for nested schema](#nestedatt--streams))

<a id="nestedatt--streams"></a>
### Nested Schema for `streams`

Read-Only:

- `name` (String)
- `topic` (String)

