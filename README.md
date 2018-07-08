# chaoscraft


## Install:

### Step 1:
Install Git
https://git-scm.com/downloads


### Step 2:
Install NodeJS
https://nodejs.org/en/

### Step 3:
Pull down the code
```
git clone https://github.com/schematical/chaoscraft.git
```

### Step 4:
Run NPM install
```
cd ./chaoscraft
npm install
```

### Step 5:
Build the code
```
npm build
```

### Step 6:
Start it
```
npm start
```



## Docker Build:
```
docker build -t chaoscraft-bot .
```

Run it locally:
```
docker run -it --net=host chaoscraft-bot
```

## Random Notes:

https://github.com/PrismarineJS/mineflayer/blob/master/doc/api.md#move

https://github.com/PrismarineJS/mineflayer-navigate/blob/master/index.js


## Finds Block At:
https://github.com/PrismarineJS/mineflayer/blob/master/doc/api.md#botblockatpoint


## Can Craft:
You will need to do a little bit more logic to determine this:

https://github.com/PrismarineJS/mineflayer/blob/master/doc/api.md#botrecipesforitemtype-metadata-minresultcount-craftingtable




{
  "domain": null,
  "_events": {},
  "_eventsCount": 0,
  "id": 26842,
  "type": "object",
  "position": {
    "x": 265.1096849302338,
    "y": 64,
    "z": 226.74282263306264
  },
  "velocity": {
    "x": -0.000625,
    "y": 0,
    "z": 0.0003125
  },
  "yaw": 2.6016314162540475,
  "pitch": 0,
  "onGround": true,
  "height": 0,
  "effects": {},
  "equipment": [
    null,
    null,
    null,
    null,
    null
  ],
  "isValid": true,
  "metadata": {
    "0": 0,
    "1": 300,
    "2": "",
    "3": false,
    "4": false,
    "5": false,
    "6": {
      "blockId": 12,
      "itemCount": 1,
      "itemDamage": 0
    }
  },
  "objectType": "Dropped item",
  "displayName": "Dropped item",
  "entityType": 2,
  "name": "item",
  "kind": "Drops"
}












Entity