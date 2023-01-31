### Assignment

The following use case is a baseline. The only hard requirements we impose are the use of React and Typescript. You have complete freedom over all other libraries and tools. You may use a different API than the one suggested as long as you remain true to the spirit of the assignment. Please the requirements section for details.
The following use case is a baseline. The only hard requirements we impose are the use of React and Typescript. You have complete freedom over all other libraries and tools. You may use a different API than the one suggested as long as you remain true to the spirit of the assignment. 

### Use case

In this assignment you will create a small [React](https://reactjs.org/) project
that consumes the [SpaceX GraphQL API](https://api.spacex.land/graphql/) to
that consumes the [SpaceX Api](https://studio.apollographql.com/public/SpaceX-pxxbxen/home?variant=current) to
display information about their launches. The end user needs to be able to
select multiple launches from the list that you display and request the
estimated total energy that these launches consumed. The result needs to be

The front end application should:

- Query [SpaceX GraphQL API](https://api.spacex.land/graphql/) for launches.
- Query [SpaceX Api](https://studio.apollographql.com/public/SpaceX-pxxbxen/home?variant=current) for launches.
  You decide which launches to display and whether or not to include filters.
- Display launch information
- Allow the user to select multiple launches
- It costs about 15 kg of fuel bring 1 kg of mass to the Lower Earth Orbit
- The fuel has an energetic value of 1.35\*10^7 Joules / kg

### Requirements
### What we would like to see

You are asked to create a simple application using [React](https://reactjs.org/) and
[TypeScript](https://www.typescriptlang.org/).

We would like to see at least:

- The application should consume an API and retrieve a list of items.
- A user should be able to view the list of items.
- A user should be able to select some items in the list and view aggregated information about the items selected.
- Optional: Assume you have access to a `user` object at the top level of your application ( retrieved from the auth system ). Filter out some items from the list based on the user's permissions to view these items. You are free to mock the `user` object and the `permissions` structure however you see fit.
- Optional: The aggregated information should be displayed with the help of a data visualization tool ( graphs, charts, anything you think is useful).
- Optional: If you're using a UI library, pick one component you believe you will need and customize it, visually or in terms of provided features.

But it will be great if you can cover some of this topics which we consider will bring more substance to the use case presentation: 

-  Assume you have access to a `user` object at the top level of your application ( retrieved from the auth system ). Filter out some items from the list based on the user's permissions to view these items. You are free to mock the `user` object and the `permissions` structure however you see fit.
-  Using a data visualization library/framework, compare data from multiple launches in one view.
-  If you're using a UI library, pick one component you believe you will need and customize it, visually or in terms of provided functionality.

- You can use any UI library (some examples are [Material UI](https://mui.com/),
  [Ant Design](https://ant.design/)) or none at all.
  [GraphQL request](https://github.com/prisma-labs/graphql-request),
  [Relay](https://relay.dev/)).

- You can use a different API than the one suggested in the prompt if it doesn't work or you have a personal preference. However, it should return a list of items you later display and interact with on the page to fulfil the other requirements / user stories.

A couple of other example APIs are:
### Notes
If you want to run the API locally you can use this alternative project:

- a different [SpaceX Api](https://studio.apollographql.com/public/SpaceX-pxxbxen/home?variant=current)
- [Star Wars Api](https://studio.apollographql.com/public/SpaceX-pxxbxen/home?variant=current)
- [Pokemon Api](https://studio.apollographql.com/public/poke-gql/home?variant=current)
- [Countries Api](https://studio.apollographql.com/public/countries/home?variant=current)
- https://github.com/SpaceXLand/api
