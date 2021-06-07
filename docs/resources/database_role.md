---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "denodo_database_role Resource - terraform-provider-denodo"
subcategory: "Database role resource"
description: "Create, delete, read, or update a database role."
  
---

# denodo_database_role (Resource)





<!-- schema generated by tfplugindocs -->
## Schema

### Required

- **database_name** (String) Name of the database the role belongs too.
- **name** (String) Name of the role being created.
- **scheduler_admin** (Boolean) Scheduling admin role on the database.

### Optional

- **admin** (Boolean) Admin privilege over a database.
- **all_privilege** (Boolean) All privileges CONNECT, CREATE, CREATE_DATA_SOURCE, CREATE_VIEW, CREATE_DATA_SERVICE, CREATE_FOLDER, EXECUTE, METADATA, WRITE, and FILE.
- **connect** (Boolean) Connect privilege to the database.
- **create** (Boolean) Create privilege for all objects in a database.
- **create_data_service** (Boolean) Create data service privilege in a database.
- **create_data_source** (Boolean) Create data source privilege in a database.
- **create_folder** (Boolean) Create folder privilege in a database.
- **create_view** (Boolean) Create view privilege in a database.
- **execute** (Boolean) Execute privilege on objects in a database.
- **file** (Boolean) File privilege in a database to browse through directories.
- **grant** (Boolean) Grant privileges on a database.
- **id** (String) The ID of this resource.
- **meta_data** (Boolean) Metadata privilege to get view information in the database.
- **monitor_admin** (Boolean) Monitoring admin role on the database.
- **revoke** (Boolean) Revoke privileges on a database.
- **write** (Boolean) Write privileges on elements in a database.

