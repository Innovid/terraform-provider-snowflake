---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "snowflake_materialized_views Data Source - terraform-provider-snowflake"
subcategory: ""
description: |-
  
---

# snowflake_materialized_views (Data Source)



## Example Usage

```terraform
data "snowflake_materialized_views" "current" {
    database = "MYDB"
    schema   = "MYSCHEMA"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `database` (String) The database from which to return the schemas from.
- `schema` (String) The schema from which to return the views from.

### Read-Only

- `id` (String) The ID of this resource.
- `materialized_views` (List of Object) The views in the schema (see [below for nested schema](#nestedatt--materialized_views))

<a id="nestedatt--materialized_views"></a>
### Nested Schema for `materialized_views`

Read-Only:

- `comment` (String)
- `database` (String)
- `name` (String)
- `schema` (String)


