# Guidelines

## Client Side - ReactJSX

-   ### [Use Typescript (TSX)](https://www.typescriptlang.org/docs/handbook/react.html)

-   ### All code needs to be documented with JSDoc and better-docs comments. [Reference](https://gist.github.com/aniketbiprojit/faae9a4113786c37025ba934d45be1ca)

-   ### Different folders for containers, actions, constant and features.

    -   #### Components : includes folders for stateful classes and their respective SCSS.
    -   #### Features: Functionality added to the components in a stateless or stateful manner or hooks. Not required to be created explicitly.
    -   #### Containers: Bind one or more components or features together and exports a default function to return these in a stateless manner.
    -   #### Constants: routes.json, actions.json, etc.
    -   #### Actions : Reducers and Actions for react-redux

-   ### Stateful Classes
