# lyric-offset

offsets for known cache_path

```csv
platform,songid,offset
```

to modify offset with `jq`:

```bash
tmpfile=`mktemp`
jq '.offset = OFFSET' PATH > "${tmpfile}"
mv "${tmpfile}" PATH
```
