# SSX API Reference

[Home](https://github.com/spruceid/ssx/blob/main/documentation/reference/ssx-sdk/index.md) > [@spruceid/ssx](./)

### ssx package

### Classes

| Class                             | Description                                                                                                       |
| --------------------------------- | ----------------------------------------------------------------------------------------------------------------- |
| [SSX](ssx.ssx/)                   | <p>SSX: Self-sovereign anything.</p><p>A toolbox for user-controlled identity, credentials, storage and more.</p> |
| [SSXConnected](ssx.ssxconnected/) | An intermediate SSX state: connected, but not signed-in.                                                          |
| [SSXInit](ssx.ssxinit/)           | Initializer for an SSXSession.                                                                                    |

### Enumerations

| Enumeration                                                         | Description                                        |
| ------------------------------------------------------------------- | -------------------------------------------------- |
| [SSXAlchemyProviderNetworks](ssx.ssxalchemyprovidernetworks.md)     | Enum of supported networks for Alchemy             |
| [SSXAnkrProviderNetworks](ssx.ssxankrprovidernetworks.md)           | Enum of supported networks for Ankr                |
| [SSXEtherscanProviderNetworks](ssx.ssxetherscanprovidernetworks.md) | Enum of supported networks for Etherscan           |
| [SSXInfuraProviderNetworks](ssx.ssxinfuraprovidernetworks.md)       | Enum of supported networks for Infura              |
| [SSXPocketProviderNetworks](ssx.ssxpocketprovidernetworks.md)       | Enum of supported networks for Pocket              |
| [SSXRPCProviders](ssx.ssxrpcproviders.md)                           | Enum of supported RPC providers                    |
| [StorageModule](ssx.storagemodule.md)                               | Selection and configuration of the storage module. |
| [StorageType](ssx.storagetype.md)                                   | Supported storage types.                           |

### Interfaces

| Interface                               | Description                                          |
| --------------------------------------- | ---------------------------------------------------- |
| [SiweConfig](ssx.siweconfig.md)         | Optional session configuration for the SIWE message. |
| [SSXConfig](ssx.ssxconfig/)             | Core config for SSX.                                 |
| [SSXExtension](ssx.ssxextension/)       | Interface for an extension to SSX.                   |
| [SSXProviders](ssx.ssxproviders/)       | SSX web3 configuration settings                      |
| [SSXProviderWeb3](ssx.ssxproviderweb3/) | Web3 provider configuration settings                 |
| [Storage\_2](ssx.storage\_2/)           | A Storage module.                                    |

### Type Aliases

| Type Alias                                                                  | Description                                                                                      |
| --------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------ |
| [ConfigOverrides](ssx.configoverrides.md)                                   | Overrides for the session configuration.                                                         |
| [ExtraFields](ssx.extrafields.md)                                           |                                                                                                  |
| [ServerHost](ssx.serverhost.md)                                             | The URL of the server running ssx-server. Providing this field enables SIWE server communication |
| [SSXAlchemyProvider](ssx.ssxalchemyprovider.md)                             | Alchemy provider settings                                                                        |
| [SSXAnkrProvider](ssx.ssxankrprovider.md)                                   | Ankr provider settings                                                                           |
| [SSXCloudflareProvider](ssx.ssxcloudflareprovider.md)                       | Cloudflare provider settings                                                                     |
| [SSXCustomProvider](ssx.ssxcustomprovider.md)                               | Custom provider settings                                                                         |
| [SSXEtherscanProvider](ssx.ssxetherscanprovider.md)                         | Etherscan provider settings                                                                      |
| [SSXInfuraProvider](ssx.ssxinfuraprovider.md)                               | Infura provider settings                                                                         |
| [SSXInfuraProviderProjectSettings](ssx.ssxinfuraproviderprojectsettings.md) | Infura provider project settings                                                                 |
| [SSXPocketProvider](ssx.ssxpocketprovider.md)                               | Pocket provider settings                                                                         |
| [SSXProviderServer](ssx.ssxproviderserver.md)                               | The ssx-powered server configuration settings                                                    |
| [SSXRPCProvider](ssx.ssxrpcprovider.md)                                     |                                                                                                  |
| [SSXSession](ssx.ssxsession.md)                                             | Representation of an active SSXSession.                                                          |
