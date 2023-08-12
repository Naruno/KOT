---
title: API REFERANCE
nav_order: 9
has_children: true
---

# API Referance

## Overview

The API provides the following endpoints for interacting with the KOT key-value database.

### `set_data`

- Method: POST
- Endpoint: `/controller/set`
- Parameters:
  - `database_name`: The name of the database.
  - `key`: The key to set.
  - `value`: The value to set for the key.

Sets the value for the given key in the specified database.

### `get_data`

- Method: POST
- Endpoint: `/controller/get`
- Parameters:
  - `database_name`: The name of the database.
  - `key`: The key to retrieve.

Retrieves the value for the given key from the specified database.

### `get_all`

- Method: POST
- Endpoint: `/controller/get_all`
- Parameters:
  - `database_name`: The name of the database.

Retrieves all the data from the specified database.

### `delete_data`

- Method: POST
- Endpoint: `/controller/delete`
- Parameters:
  - `database_name`: The name of the database.
  - `key`: The key to delete.

Deletes the value for the given key from the specified database.

### `list_databases`

- Method: GET
- Endpoint: `/database/list`

Lists all the databases.

### `pop_database`

- Method: POST
- Endpoint: `/database/pop`
- Parameters:
  - `database_name`: The name of the database.

Deletes the specified database.

### `pop_all_database`

- Method: POST
- Endpoint: `/database/pop_all`

Deletes all the databases.

### `rename_database`

- Method: POST
- Endpoint: `/database/rename`
- Parameters:
  - `database_name`: The name of the database.
  - `new_database_name`: The new name for the database.

Renames the specified database.

### `delete_database`

- Method: POST
- Endpoint: `/database/delete`
- Parameters:
  - `database_name`: The name of the database.

Deletes the specified database.

### `delete_all_database`

- Method: POST
- Endpoint: `/database/delete_all`

Deletes all the databases.