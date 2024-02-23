# older
Simple function to check if a file is older, useful for cache related operations.

## Installation

```shell
npm i older
```

## Usage

```JavaScript
import older from 'older';
```

## Example

```JavaScript
import older from 'older';

if(older('extracted.json', 'scraped.html')){ // if extracted.json is older than scraped.html

  // scraped html is newer and contains updated data, extracted.json must be re-created
  extractAndSaveData({from:'scraped.html', into:'extracted.json'});

}
```

## Testing

```shell

npm run test

```
