# What is this?

Get perfect shadows every time for the non-designer.

# installation

npm i shadowizard --save-dev

Then...

```
import { shadowizard } from 'shadowizard;

shadowizard({
  shadow_type : 'soft',
  padding     : false
});
```

## options

Shadowizard supports 2 options, both of which are optional:
* *shadow_type* - _hard | soft_ (defaults to soft)
* *padding* - _boolean_ (Defaults to false)
