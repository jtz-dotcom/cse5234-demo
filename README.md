# Nordform educational storefront demo

Public website: https://jtz-dotcom.github.io/cse5234-demo/

This is a CSE 5234 classroom project, not a real store. No real purchases or
payments are processed. Use only fictional contact and shipping details and the
displayed test card. Nothing will be shipped.

This repository contains only the compiled React frontend and public images.
The course source repository and backend deployment files remain private.
The storefront calls the team's AWS inventory and order microservices, backed
by a private RDS MySQL database. Demo orders are saved to that test database.

Open the Shop link to begin. The public site uses hash routes (for example,
`#/purchase`) so refreshing a checkout page works on static hosting.
