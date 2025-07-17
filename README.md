# LTFS Build docker action for Debian12 (Bookworm)

This action builds the LTFS package on Debian12

## Inputs

### `destination`

**Required** Destination of install。 Default is `/tmp/ltfs`。

## Outputs

None

## Usage

```
uses: LinearTapeFileSystem/Debian12-Build@v1.0
with:
  destination: '/tmp/ltfs'
```
