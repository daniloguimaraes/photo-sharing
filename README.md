# photo-sharing
Photo sharing SPA written in Javascript


## Functional Requirements

 - The user must be able to upload an image along with a brief caption for that image.
 - Images must either be public or private.
 - The user must be able to view all existing images along with their caption. Only public images or private images the user added must be displayed.
 - The user must be able to delete their existing images. The user must not be able to delete images they did not add.
 - Different users should be able to login to the application.
 - All data added must be persistent, such that the server and browser can be restarted without any loss of data.
 - The images displayed could update in real-time as new images are added.


## Technology Stack

 - Client side:
     - [Apollo Client][apollo-client]
     - [React][react]
 - Server side:
     - [Apollo Server (GraphQL)][apollo-server]
     - [ExpressJS][express]
     - [NeDB][nedb] and [nedb-promise][nedb-promise]

[apollo-client]:https://github.com/apollographql/apollo-client
[apollo-server]: https://github.com/apollographql/apollo-server
[express]: https://github.com/expressjs/express
[nedb]:https://github.com/louischatriot/nedb
[nedb-promise]: https://github.com/jrop/nedb-promise
[react]:https://github.com/facebook/react