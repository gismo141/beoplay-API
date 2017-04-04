# Beoplay API

** This is a work in progress **

## Getter-Functions

| Function | API-Call |
|:---|:----|
| Get Volume | `<IP_ADDRESS>/api/getData?path=BeoSound:/volume&roles=value`|

## Setter Functions

The `{{{payload}}}` contains the value to set.

| Function | API-Call |
|:---|:----|
| Set Volume | `<IP_ADDRESS>/api/setData?path=BeoSound:/setVolume&roles=activate&value={"type":"beoSoundVolumeData","beoSoundVolumeData":{"volume":{{{payload}}},"volumeSource":"website"}}`|
