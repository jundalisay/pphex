---
title: Overview
description: "" 
image: "/graphics/elixir.jpg"
tags: ['Elixir']
date: 2023-08-22
weight: 2
---


# Ecto

Handles external data such as databases and JSON APIs

- Repo
- Query
- Schema
- Changset

## Repo: communicates with external data source or database

Has common methods:
- get(): gets the record
- insert(): creates the record in that database
- update()
- delete()
- transaction()
...

Phoenix uses Repo through:
- `config.exs` as config `:appname, Appname.Repo,` ...
- `repo.ex` in `/lib/appname/repo.ex`

#### Common methods

``` elixir
Repo.count()
Repo.update_all("tablename", set: [updated_at: Ecto.DateTime.utc])
```
