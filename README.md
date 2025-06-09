# Unity.xxHash

Extremely fast non-cryptographic hash algorithm [xxhash](http://www.xxhash.com/)

Simple UPM package for Unity for my personal use (fork).

## Installation

Add the dependency to your `manifest.json`

```json
{
  "dependencies": {
    "jd.boiv.in.xxhash": "https://github.com/starburst997/Unity.xxHash.git"
  }
}
```

## Usage

Simply call the following to get an id:

```csharp
var hash = xxHash64.ComputeHash(data, data.Length);
Debug.Log($"Hash: {hash}");
```

## TODO

- Better readme

## Credits

Based on [xxHash.st](https://github.com/uranium62/xxHash) which is based on the og [xxHash](https://github.com/Cyan4973/xxHash).