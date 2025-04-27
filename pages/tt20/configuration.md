# Configuration

All about config is here!

## Config file

**What is it?**

Config file is where mod saves it's settings,\
so you don't need to toggle functions after each restart

**How do I find it?**

1. Navigate to your game folder
2. Go to `config` folder and then to `tt20`
3. Here it is! `config.json` is the main config file

BEGIN NOTE
**Note:** you need to start game with the mod once, so config files can generate
END NOTE

---

**Config explanation**

All options below require `boolean` (`true`/`false`)\
if you'll put something except `boolean` it will use default value

| Config key                      | Default value | Explanation                         |
|---------------------------------|---------------|-------------------------------------|
| `enabled`                       | `true`        | Is TT20 enabled                     |
| `block-entity-acceleration`     | `false`       | Ex. chest opening speed             |
| `block-breaking-acceleration`   | `true`        | Block breaking speed                |
| `potion-effect-acceleration`    | `true`        | Effect time                         |
| `fluid-acceleration`            | `true`        | Fluid speed                         |
| `pickup-acceleration`           | `true`        | Item pickup time                    |
| `eating-acceleration`           | `true`        | Food consuming speed                |
| `portal-acceleration`           | `true`        | Nether portal tp time               |
| `sleeping-acceleration`         | `true`        | In bed lay time                     |
| `server-watchdog`               | `true`        | Disable server if dead for a minute |
| `singleplayer-warning`          | `true`        | Warning in singleplayer             |
| `time-acceleration`             | `true`        | Day/Night time speed                |
| `random-tickspeed-acceleration` | `true`        | Ex. crop grow speed                 |
| `automatic-updater`             | `true`        | Mod update checker                  |

BEGIN NOTE
**Note:** be careful with json structure, don't brake it!
END NOTE

[Need some extra help?](https://discord.gg/7uYhxN7cFj)