# Welcome to the AREDL!
The All Rated Extreme Demons List (AREDL for short) is a Geometry Dash community project that aims to rank every rated extreme demon in the game by difficulty   
You can find more information about us on [our website](https://aredl.net) or on our [Discord server](https://Discord.gg/aredl)   
## AREDL Github Org
This Github organization holds the code for the different versions of both the AREDL website (frontend & backend) and the AREDL Manager Discord bot. It has the following repositories:

### Current

-  **[AREDLV3-Frontend](https://github.com/All-Rated-Extreme-Demon-List/AREDLV3-Frontend) (Private)**: Public website with React Router 7 and a new design.
-  **[aredl-backend-v2](https://github.com/All-Rated-Extreme-Demon-List/aredl-backend-v2):** REST API backend, using PostgreSQL & Rust with the Actix-web framework and the Diesel ORM. Available [here](https://api.aredl.net/v2/api), documentation [here](https://api.aredl.net/v2/docs).
-  **[AREDL-Staff-Portal](https://github.com/All-Rated-Extreme-Demon-List/AREDL-Staff-Portal) (Private)**: Frontend to interact with the backend for staff tasks.
-  **[AREDL-ManagerV3](https://github.com/All-Rated-Extreme-Demon-List/AREDL-ManagerV3) **: Discord bot that sends notifications for various events from the backend, like when records are accepted/rejected and when shifts expire. Also has commands to view information about levels and the leaderboard. Uses Discord.js.
-  **[GD-Fisher](https://github.com/All-Rated-Extreme-Demon-List/GD-Fisher)**: "Fishing" Discord bot similar to the Miso bot fish command, but with Geometry Dash levels instead of fish.
-  **[Polaris](https://github.com/All-Rated-Extreme-Demon-List/Polaris)**: Fork of [Colon's Polaris Discord bot](https://github.com/GDColon/Polaris-Open), used to self-host Polaris for use on the AREDL Discord server, deployed in a docker compose stack.
-  **[AREDL-Monitoring](https://github.com/All-Rated-Extreme-Demon-List/AREDL-Monitoring) (Private)**: Utility repo hosting a Docker compose stack configuration used to log and monitor the API and backend server.
-  **[Thumbnails](https://github.com/All-Rated-Extreme-Demon-List/Thumbnails)**: Utility repo hosting different levels and packs thumbnails displayed on the V3 Frontend site. Uses the [Levels thumbnails Geode mod API](https://github.com/cdc-sys/level-thumbnails).
- **[Guidelines](https://github.com/All-Rated-Extreme-Demon-List/guidelines)**: Repository that stores the markdown files used to build the [Guidelines page](https://aredl.net/guidelines/) on our website. Feel free to open a pull request to add/fix anything!

### Archived/Deprecated

-  **[AREDL V1/V2](https://github.com/All-Rated-Extreme-Demon-List/AREDL)**: Old TSL-Layout website (main branch) as more recent V2 Website (aredl-revamp branch). Both use VueJS.
-  **[AREDL-ManagerV2](https://github.com/All-Rated-Extreme-Demon-List/AREDL-ManagerV2)**: AREDL Discord bot made to let people submit their records on Discord, and automatically add those on a TSL layout github repo if they are accepted. Uses Discord.js.
-  **[AREDL-Old-Backend](https://github.com/All-Rated-Extreme-Demon-List/AREDL-Old-Backend)**: Old backend API used by the V2 website. Written in Go using the [pocketbase](https://pocketbase.io) framework.

## Credits
- [Simolater](https://github.com/Simolater): Backend V1, Backend V2, Frontend V2, Deployments
- [Minebox260](https://github.com/Minebox260): AREDL Manager V2, AREDL Manager V3, Frontend V3, Staff Portal, Backend V2
- [Oculations](https://github.com/ThatGuyNick05): Frontend V3, Staff Portal, Backend V2
- [sphericle](https://github.com/sphericle): Backend V2, Frontend V3, Staff Portal, AREDL Manager V3, Guidelines
- [WinDoge](https://github.com/WinDogePlays): AREDL Manager V2
- [Zoink Doink](https://github.com/zoinkdoink): Staff Portal
- [KrisGra](https://github.com/krisgrant): Frontend V1
  
- [TheShittyList](https://github.com/TheShittyList): original TSL template/layout used in Frontend V1 & Frontend V2
- [Colon](https://github.com/GDColon): Creator of the original [Polaris](https://github.com/GDColon/Polaris-Open) bot
