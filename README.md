# ec2-dump
dumps raw aws ec2 data to a json file

## To use

### Get Dump

#### Set aws ENV to regions
Update `enviromentAwsRegionMap.json` to map your enviroment to an AWS region.

#### Install dependancies
```
npm install
```

#### Export your aws credentials
```
export AWS_ACCESS_KEY_ID=REDACT
export AWS_SECRET_ACCESS_KEY=REDACT
```

#### Run passing in enviroment to export
```
node ec2-dump next
```

### parse dump

#### getInstanceByTag
```
node getInstanceByTag.js next ForgeBucket
```
