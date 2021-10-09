# README

### restoring single file
cd into the `$DEST/bin` directory first and type:
```
restore \
    --time 1999-12-24T21:33 \
    --dest /opt/duplicacy/restore/ \
    --storage storage_id \
    --key /home/user/private_key.pem \
    /home/user/file/to/be/restored.txt
```

## Frequently Asked Questions (FAQs)

**Q: Why is nothing happening even though I correctly typed in all the infos needed by the script?**  
**A:** make sure your repo in `$DEST` is still setup (`.duplicacy` directory must be present), otherwise restoration won't succeed.
