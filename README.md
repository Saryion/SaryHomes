![Showcase of Homes GUI](https://i.imgur.com/6bx02LI.png)

![Showcase of Home Icons](https://i.imgur.com/kD98lcF.png)
# Features
* Homes system with GUI with pages.
* You can change the icon for each home in the GUI using right click.
* `/home` will take you to your default home, which can be set in the GUI by middle clicking a home.
* View information about your homes, such as it's location and biome it's in.
* You can set a limit of max homes by using the permission `saryhomes.maxhomes.<num>`. Player's with permission `saryhomes.unlimited` or `saryhomes.admin` can create unlimited homes.
* Admins can open anyones home GUI with `/homes <player>` and permission `saryhomes.admin`

### Commands
* `/home [home]`
* `/homes [player]`
* `/sethome <home>`
* `/delhome <home>`

### Permissions
* `saryhomes.command.home`
* `saryhomes.command.sethome`
* `saryhomes.command.delhome`
* `saryhomes.maxhomes.<num>`
* `saryhomes.unlimited`
* `saryhomes.admin`

### Customization
There is several options you can change in the scripts file. They are located at the beginning of the file, including messages and permissions. You can also add new icons in the `on load` event using function `add_icon(item name)`.

## Requirements (Dependencies)
The only addon this script requires is [Skript-GUI](https://github.com/APickledWalrus/skript-gui) for it's GUI capabilities.

## TODO
* Renaming of homes

## Disclaimer
I'm currently learning Skript, i'm very new. This is my first real project using it, and it's capabilities are pretty cool. So I know it's probably not as good as it can be, i'll improve in time.
