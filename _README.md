# Jared notes

## Setup

## Install `platformio`

```
virtualenv -p python3 env
source env/bin/activate.fish
pip install -U platformio
```

Install TMCStepper library:

```
arduino-cli lib install TMCStepper
```

## Compile with Arduino CLI

```
platformio run -e rambo
```

## Loading it

```
platformio run --target upload -e rambo
```

## Post processing

Lives here: 

https://github.com/martindb/mpcnc_posts_processor