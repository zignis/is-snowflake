# is-snowflake

Determine and validate snowflake IDs

## Install

```
yarn add is-snowflake
```

## Usage

```js
import { isSnowflake } from 'is-snowflake';

assert(isSnowflake('1706300963561668608') === true);
```

## What is a snowflake ID?

Twitter has a decent blog about it: https://blog.twitter.com/engineering/en_us/a/2010/announcing-snowflake