# C# Discord Bot with MySQL DB on DSharpPlus [.NET 7]
 .NET 7+ is required. Pull requests are welcomed.
***
> [Documentation](https://mentally-stable.gitbook.io/eremite/)

> [Invite Bot](https://discord.com/api/oauth2/authorize?client_id=739487241469952000&permissions=8&scope=bot) or mess with the bot in [our server #bot-commands](https://discord.gg/mentallystable4sure)
***
# This bot is in WIP state
Bot functions:
- Gift Welkin Moon by UID in Genshin Impact automatically from MooGold
- Pull characters
- Sacrifice characters
- Earn pills/primogems/mora
- Set main character/receive buffs
- Go on an Adventures
- Do dailies
- Buy/Sell fish/fishing rods in Liyue Harbor
- Fishing mechanic with perks

# How to setup
  <img src=https://github.com/limelight-mint/Eremite/blob/main/content/img_pull2.png width='450'></img>

  - Open startup_config.json and edit token from [your applications developer portal](https://discord.com/developers/applications)
  - Open dbconfig.json and edit with your mysql database credentials (you can use MAMP if you just want to test it locally or phpmyadmin)

  > CONFIGS NOTE: If you want to test server build navigate to [releases](https://github.com/MentallyStable4sure/Eremite/releases) since build already has all the configs in json, but if u want to start it as a project (in debug mode for example), you gotta move this juicy config folder into /bin/debug(or release)/net8.0/

### Want a custom DB?

 > CUSTOM DB NOTE: If you want to use something other beside MySQL (MSSQL/PostgreSQL/REST/etc.) feel free to modify [DbConnector.cs](Eremite/Services/DbConnector.cs), [QueryHandler.cs](Eremite/Services/QueryHandler.cs) and [DatabaseConfig.cs](Eremite/Data/DatabaseConfig.cs) since those are the connector and the db credentials model

  <img src=https://github.com/limelight-mint/Eremite/blob/main/content/img_profile.png width='450'></img>


***

# Credits

> Thanks to [@Escartem](https://github.com/Escartem) for French localization.
> No more using it but still: Thanks to [Enka.Network](https://github.com/EnkaNetwork) for [API](https://github.com/EnkaNetwork/API-docs) provided, and [DevilTakoyaki](https://twitter.com/deviltakoyaki) for materials provided.
