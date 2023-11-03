# A Meetgard and EVMGames boilerplate for Unity
This is a boilerplate project. It includes EVMGames/Meetgard and all the required dependencies, and will be tagged with local or specific versions of those dependency packages.

Unity version
-------------

The current status is meant to be used in Unity 2020.3 or better. The upper version is not yet determined, and lower versions are not supported (i.e. it may work, but with no responsibilities from the development side).

Dependencies versioning and status
----------------------------------

So far this project relies on a set of packages that I could consider, at best, in beta status. These packages are not officially released and they are tagged 0.0.1. The referenced packages exist into this organization and must be cloned individually besides this boilerplate (i.e. as a sibling directory). They are:

 - com.alephvault.unity.support: [Clone it - 0.0.3](https://github.com/AlephVault/unity-support/tree/0.0.3).
 - com.alephvault.unity.support.generic: [Clone it - 0.0.1](https://github.com/AlephVault/unity-support-generic/tree/0.0.1).
 - com.alephvault.unity.boilerplates: [Clone it - 0.0.1](https://github.com/AlephVault/unity-boilerplates/tree/0.0.1).
 - com.alephvault.unity.binary: [Clone it - 0.0.2](https://github.com/AlephVault/unity-binary/tree/0.0.2).
 - com.alephvault.unity.layout: [Clone it - 0.0.1](https://github.com/AlephVault/unity-layout/tree/0.0.1).
 - com.alephvault.unity.menuactions: [Clone it - 0.0.1](https://github.com/AlephVault/unity-menu-actions/tree/0.0.1).
 - com.alephvault.unity.meetgard: [Clone it - 0.0.5](https://github.com/AlephVault/unity-meetgard/tree/0.0.5).
 - com.alephvault.unity.meetgard.auth: [Clone it - 0.0.4](https://github.com/AlephVault/unity-meetgard-auth/tree/0.0.4).
 - com.alephvault.unity.meetgard.scopes: [Clone it - 0.0.3](https://github.com/AlephVault/unity-meetgard-scopes/tree/0.0.3).
 - com.alephvault.unity.remotestorage: [Clone it - 0.0.2](https://github.com/AlephVault/unity-remotestorage/tree/0.0.2).
 - com.alephvault.unity.ipfs [Clone it - 0.0.1](https://github.com/AlephVault/unity-ipfs/tree/0.0.1).
 - com.alephvault.unity.evmgames [Clone it - 0.0.2](https://github.com/AlephVault/unity-evmgames/tree/0.0.2).
 - com.alephvault.unity.evmgames.auth [Clone it - 0.0.3](https://github.com/AlephVault/unity-evmgames-auth/tree/0.0.3).
 - com.alephvault.unity.evmgames.livecache [Clone it - 0.0.2](https://github.com/AlephVault/unity-evmgames-livecache/tree/0.0.2).
 - com.alephvault.unity.evmgames.localstorage [Clone it - 0.0.1](https://github.com/AlephVault/unity-evmgames-localstorage/tree/0.0.1).

You can run the attached scripts to clone the dependencies after cloning this project:

 - Windows: clone-all.sh
 - Unix-based (bash): clone-all.bat
 
If you have these repositories already cloned for another boilerplate and version, you can just go inside and checkout the proper (remote, typically) tags instead.

Plugins
-------

In order to use this boilerplate, as described in the documentation for com.alephvault.unity.evmgames, 6 compiled DLL files are needed in the `Plugins/` directory.

These files can be found as part of a compressed file available in this boilerplate: `evmgames-plugins.zip`. That file contained the required DLL files, which must be placed directly into the `Plugins/` directory.
They're tested in .NET Framework 4.6.1.


