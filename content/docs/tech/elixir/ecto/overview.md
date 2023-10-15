---
title: Ecto
description: Here are a few Enum methods
image: "/graphics/elixir.jpg"
tags: ['Phoenix']
date: 2022-03-15
weight: 51
---

Ecto has 4 components:

## Ecto.Changeset -- Changes data

These let us track and validate changes before they are applied to the data.


## Ecto.Query -- Reads data
 
Queries are used to retrieve information from a Repo. Ecto queries are secure and composable


## Ecto.Repo -- Where data is

A Repo is a wrapper around the data store. It lets us create, update, destroy and query existing entries. 

A repository needs an adapter and credentials to communicate to the database.


## Ecto.Schema -- How data is

Schemas are used to map external data into Elixir structs.  We often use them to map database tables to Elixir data. 








## get_by/3

`get_by(query, clauses, options)`


