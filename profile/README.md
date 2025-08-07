# Welcome to the AREDL!
The All Rated Extreme Demons List (AREDL for short) is a Geometry Dash community project that aims to rank every rated extreme demon in the game by difficulty   
You can find more information about us on [our website](https://aredl.net) or on our [discord server](https://discord.gg/aredl)   
## AREDL Github Org
This Github organization holds the code for the different versions of both the AREDL website (frotend & backend) and the AREDL Manager discord bot. It has the following repositories:

### Current

-  **[AREDLV3-Frontend](https://github.com/All-Rated-Extreme-Demon-List/AREDLV3-Frontend) (Private)**: WIP Entire rewrite of the public website with React Router 7 and a new design.
-  **[aredl-backend-v2](https://github.com/All-Rated-Extreme-Demon-List/aredl-backend-v2) (Private)**: Currently deployed backend, with PostgreSQL & Rust using the Actix-web framework and the Diesel ORM. Available [here](https://api.aredl.net/v2/api), documentation [here](https://api.aredl.net/v2/docs).
-  **[AREDL-Staff-Portal](https://github.com/All-Rated-Extreme-Demon-List/AREDL-Staff-Portal) (Private)**: WIP Frontend to interact with the new backend for staff tasks.
-  **[GD-Fisher](https://github.com/All-Rated-Extreme-Demon-List/GD-Fisher)**: "Fishing" discord bot similar to the miso bot fish command, but with Geometry Dash levels instead of fish.
-  **[AREDL-Monitoring](https://github.com/All-Rated-Extreme-Demon-List/AREDL-Monitoring) (Private)**: Utility repo hosting a docker compose stack configuration used to log and monitor the API and backend server.
-  **[Thumbnails](https://github.com/All-Rated-Extreme-Demon-List/Thumbnails)**: Utility repo hosting different levels and packs thumbnails displayed on the V3 Frontend site. Uses the [Levels thumbnails geode mod repo](https://github.com/cdc-sys/level-thumbnails).
-  **[Polaris](https://github.com/All-Rated-Extreme-Demon-List/Polaris)**: Fork from [GDColon's Polaris discord XP bot](https://github.com/GDColon/Polaris-Open), used to self-host polaris for use on the AREDL discord server, deployed in a docker compose stack.
- **[AREDL-ManagerV3](https://github.com/All-Rated-Extreme-Demon-List/AREDL-ManagerV3) (Private)**: Discord bot that sends notifications for various events from the backend, like when records are accepted/rejected and when shifts expire. Also has commands to view information about levels and the leaderboard. Uses Discord.js.

### Archived/Deprecated

-  **[AREDL V1/V2](https://github.com/All-Rated-Extreme-Demon-List/AREDL)**: Old TSL-Layout website (main branch) as more recent V2 Website (aredl-revamp branch). Both use VueJS.
-  **[AREDL-ManagerV2](https://github.com/All-Rated-Extreme-Demon-List/AREDL-ManagerV2)**: AREDL Discord bot made to let people submit their records on discord, and automatically add those on a TSL layout github repo if they are accepted. Uses Discord.js.
-  **[AREDL-Old-Backend](https://github.com/All-Rated-Extreme-Demon-List/AREDL-Old-Backend)**: Old backend API used by the V2 website. Written in Go using the [pocketbase](https://pocketbase.io) framework.

## Credits
- [Simolater](https://github.com/Simolater): Backend V1, Backend V2, Frontend V2, Deployments
- [Minebox260](https://github.com/Minebox260): AREDL Manager V2, Frontend V3, Staff Portal, Backend V2
- [Oculations](https://github.com/ThatGuyNick05): Frontend V3, Staff Portal, Backend V2
- [WinDoge](https://github.com/WinDogePlays): AREDL Manager V2
- [Zoink Doink](https://github.com/zoinkdoink): Staff Portal
- [KrisGra](https://github.com/krisgrant): Frontend V1
- [sphericle](https://github.com/sphericle): Backend V2, Frontend V3, Staff Portal, AREDL Manager V3
- [TheShittyList](https://github.com/TheShittyList): original TSL template/layout used in Frontend V1 & Frontend V2
