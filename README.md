UTVehiclesContent
=================
Assets of the vehicle framework UTVehicles for [Unreal Tournament](www.unrealtournament.com/)

This repository is a part of the *UTVehicles*-plugin which consists of the **code part** and the **asset part**. You can find the code repository in its [latest state here](https://github.com/UTCommunity/UTVehicles). Thisrepository is included as a sub-module in the code repo called [Content](Content/) which points to a specific state (to feature full compatibility to the code).

**You want to be part of the development team?** Join us! [![Join the UT Vehicles Community on Slack](http://utvehicles-slack.herokuapp.com/badge.svg)](http://utvehicles-slack.herokuapp.com/)

## Quick start

Check the [code repository](https://github.com/UTCommunity/UTVehicles) for usage instructions.

## What's included

The asset repository currently consists of a test vehicle and a test map. That map is split into a basic layout map (BSP and such) and a layer map (as persistent level) which is storing the vehicle placement. This is done in order to keep changes small. Whenever a new vehicle or existing vehicles are replaced, only the specific layer map needs to be updated (less binary updates for Git).

As the official **Hellbender** assets are not properly set up, there is a specifically imported mesh in the _restricted assets_ folder.

## License

Licensed under the terms of the latest version of the **Unreal® Engine End User License Agreement**, obtainable at [unrealengine.com/eula](//unrealengine.com/eula).

A copy of the license text, as obtained on 2015-06-26, is included in the [UE4EULA.pod](UE4EULA.pod) file (for reference purposes only).