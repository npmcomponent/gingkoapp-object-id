*This repository is a mirror of the [component](http://component.io) module [gingkoapp/object-id](http://github.com/gingkoapp/object-id). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/gingkoapp-object-id`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# object-id

  Generates unique MongoDB's ObjectId.
  [Read more about ObjectID](http://docs.mongodb.org/manual/core/object-id/).

## Installation

  Install with [component(1)](http://component.io):

    $ component install gingkoapp/object-id

## Example

```js
var objectId = require('object-id');

objectId(); //=> 36dd44706dc2783478000001
objectId(); //=> 36dd44706dc2783478000002
objectId(); //=> 36dd44706dc2783478000003
```

## License

  MIT, [Gingko App](https://gingkoapp.com)
