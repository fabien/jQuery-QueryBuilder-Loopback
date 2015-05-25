# jQuery QueryBuilder Loopback

Allows to export [jQuery QueryBuilder](http://mistic100.github.io/jQuery-QueryBuilder) rules as a Loopback statement

Created by Fabien Franzen.

### Dependencies
 * jQuery QueryBuilder >= 2.0

## Usage

The plugin adds a new public method to all QueryBuilder instances.

### getLoopback

Performs validation and returns the rules as a valid Loopback statement.

```js
var loopback = $('#builder').queryBuilder('getLoopback');
```

### Operators configuration

The Loopback plugin requires special configuration for operators to convert rules. This configuration is stored in the ```loopbackOperators``` option, see the source code for more details.